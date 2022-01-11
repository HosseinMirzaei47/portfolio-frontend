<template>
  <div class="container-fluid m-0 p-0">
    <div id="home-page" class="home-page">
      <Menu />

      <div class="top-container">
        <div class="my-auto pt-4">
          <div class="text-center mb-3 d-none d-lg-block">
            <h1 class="blueText">{{ title }} - {{ occupation }}</h1>
            <div class="outline_text d-none d-lg-block">Portfolio</div>
            <h1 id="biography">{{ biography }}</h1>
          </div>
        </div>
      </div>
    </div>

    <MyProjects />

    <div class="discuss_projects">
      <div class="outline_text white project d-none d-lg-block">Let’s talk</div>
      <div class="container">
        <div class="row">
          <div class="col-xl-12">
            <div class="project_text text-center">
              <h3>Let’s start your project with us</h3>
              <h2>hosseinhidd@gmail.com</h2>
            </div>
          </div>
        </div>
      </div>
    </div>

    <Footer />
  </div>
</template>

<script>
import axios from "axios";
import MyProjects from "./MyProjects.vue";
import Menu from "./Menu.vue";
import Footer from "./Footer.vue";

export default {
  components: {
    Menu,
    MyProjects,
    Footer,
  },
  data() {
    return {
      title: "Hossein Mirzazadeh",
      occupation: "Android Developer",
      biography: "Loading data from remote: http://localhost:3900/api/info. Make sure to have the backend server running and then try again!",
    };
  },
  created() {
    // Back ro ham khodam neveshtam. Project back ro ham ba node js mongodb atlas too quera ferestadam baratoon
    axios.get("http://localhost:3900/api/info").then((response) => {
      this.title = response.data[0].name;
      this.occupation = response.data[0].profession;
      // this.biography = response.data[0].summary;
    });
  },
};
</script>

<style scoped>
#home-page {
  background-color: #040e27;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

.discuss_projects {
  background: #0181f5;
  padding: 170px 0 155px 0;
  position: relative;
  z-index: 13;
  z-index: 13;
}

.discuss_projects .project_text h3 {
  color: #fff;
  font-size: 60px;
  font-weight: 400;
  margin-bottom: 52px;
}

.discuss_projects .project_text h2 {
  color: #fff;
}

.outline_text.project {
  -webkit-text-stroke: 1px #349af7;
  -webkit-text-fill-color: transparent;
  top: 44%;
  -webkit-transform: translateY(-55%);
  -moz-transform: translateY(-55%);
  -ms-transform: translateY(-55%);
  transform: translateY(-55%);
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.app_store_img {
  max-height: 80px;
}

.top-container {
  margin: 120px 100px;
}

#biography {
  color: #fff;
  font-size: 50px;
  font-weight: 400;
  position: relative;
  z-index: 1;
  display: block;
  margin-bottom: 22px;
}

.blueText {
  margin-top: 60px;
  font-size: 30px;
  font-weight: 400;
  color: #0181f5;
  position: relative;
  z-index: 1;
  display: block;
  margin-bottom: 22px;
}

.home-page {
  padding: 4px;
  height: 80vh;
}

.outline_text {
  position: absolute;
  left: 0;
  right: 0;
  text-align: center;
  top: 16.57%;
  font-size: 150px;
  text-transform: uppercase;
  z-index: 1;
  -webkit-text-stroke: 1px #1e273d;
  -webkit-text-fill-color: transparent;
  font-weight: 800;
}
</style>
