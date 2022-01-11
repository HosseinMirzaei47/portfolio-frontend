<template>
  <div class="portfolio_wrap">
    <div class="single_gallery">
      <div class="thumb">
        <img
          src="https://i.pinimg.com/originals/c1/fa/4b/c1fa4b497b23b997a96ae9bb159da096.jpg"
          alt=""
        />
      </div>
      <div class="gallery_hover">
        <div class="hover_inner">
          <span>Event Scheduler</span>
          <a href="#"> <h3>Calendar</h3></a>
        </div>
      </div>
    </div>
    <div class="single_gallery small_width">
      <div class="thumb">
        <img
          src="https://miro.medium.com/max/2000/1*GeTCIQUOELGaWD68jHj0_w.jpeg"
          alt=""
        />
      </div>
      <div class="gallery_hover">
        <div class="hover_inner">
          <span>Android Application</span>
          <a href="#"> <h3>Time Tracker</h3></a>
        </div>
      </div>
    </div>
    <div class="single_gallery">
      <div class="thumb">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/f/f9/Money_Cash.jpg"
          alt=""
        />
      </div>
      <div class="gallery_hover">
        <div class="hover_inner">
          <span>Stock Market</span>
          <a href="#"> <h3>Signal</h3></a>
        </div>
      </div>
    </div>
    <div class="single_gallery">
      <div class="thumb">
        <img
          src="https://api.time.com/wp-content/uploads/2020/03/gym-coronavirus.jpg?w=824&quality=70"
          alt=""
        />
      </div>
      <div class="gallery_hover">
        <div class="hover_inner">
          <span>Exercise</span>
          <a href="#"> <h3>Health Club</h3></a>
        </div>
      </div>
    </div>
    <div class="single_gallery">
      <div class="thumb">
        <img
          src="https://www.gannett-cdn.com/presto/2020/10/29/PLSJ/586a55d2-38c4-4378-a29d-f86e76f0d256-Checklist_WEB.jpg"
          alt=""
        />
      </div>
      <div class="gallery_hover">
        <div class="hover_inner">
          <span>Scheduler</span>
          <a href="#"> <h3>Todo List</h3></a>
        </div>
      </div>
    </div>
    <div class="single_gallery small_width">
      <div class="thumb">
        <img
          src="https://cdn.vox-cdn.com/thumbor/6nuGrh340E58tg1mJUoaW5CyKEA=/0x0:5500x3671/1200x800/filters:focal(2310x1396:3190x2276)/cdn.vox-cdn.com/uploads/chorus_image/image/66563372/GettyImages_849177432.0.jpg"
          alt=""
        />
      </div>
      <div class="gallery_hover">
        <div class="hover_inner">
          <span>Housework</span>
          <a href="#"> <h3>Cooking Recipes</h3></a>
        </div>
      </div>
    </div>
    <div class="single_gallery">
      <div class="thumb">
        <img
          src="https://ifccd.net/uploads/image/internet-trading.jpg"
          alt=""
        />
      </div>
      <div class="gallery_hover">
        <div class="hover_inner">
          <span>Trading</span>
          <a href="#"> <h3>Stock Market</h3></a>
        </div>
      </div>
    </div>
    <div class="single_gallery small_width">
      <div class="thumb">
        <img
          src="https://files.virgool.io/upload/users/58301/posts/msp73madrgl1/hwrdinyi3tal.jpeg"
          alt=""
        />
      </div>
      <div class="gallery_hover">
        <div class="hover_inner">
          <span>English Application</span>
          <a href="#"> <h3>Duolingo</h3></a>
        </div>
      </div>
    </div>
    <div class="single_gallery">
      <div class="thumb">
        <img
          src="https://pianonava.com/wp-content/uploads/2018/06/piano-02-1030x682.jpg"
          alt=""
        />
      </div>
      <div class="gallery_hover">
        <div class="hover_inner">
          <span>Instruments</span>
          <a href="#"> <h3>Music Player</h3></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.portfolio_area .more_works {
  background: #040e27;
  padding: 35px 0;
}

.portfolio_area .more_works a {
  font-size: 20px;
  color: #fff;
  font-weight: 400;
}

.portfolio_wrap {
  overflow: hidden;
}

.single_gallery {
  overflow: hidden;
  width: 35%;
  position: relative;
  z-index: 6;
  float: left;
}

@media (max-width: 767px) {
  .single_gallery {
    width: 100%;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  .single_gallery {
    width: 50%;
  }
}

@media (min-width: 992px) and (max-width: 1200px) {
  .single_gallery {
    width: 50%;
  }
}

@media (min-width: 1200px) and (max-width: 1500px) {
  .single_gallery {
    width: 33.33333%;
  }
}

.single_gallery::before {
  width: 351px;
  height: 351px;
  background: #0181f5;
  content: "";
  position: absolute;
  left: 0;
  -webkit-border-radius: 50%;
  -moz-border-radius: 50%;
  border-radius: 50%;
  left: -26%;
  bottom: -30%;
  z-index: 1;
  opacity: 0;
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
}

@media (max-width: 767px) {
  .single_gallery::before {
    width: 250px;
    height: 250px;
  }
}

.single_gallery.small_width {
  width: 30%;
}

@media (max-width: 767px) {
  .single_gallery.small_width {
    width: 100%;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  .single_gallery.small_width {
    width: 50%;
  }
}

@media (min-width: 992px) and (max-width: 1200px) {
  .single_gallery.small_width {
    width: 50%;
  }
}

@media (min-width: 1200px) and (max-width: 1500px) {
  .single_gallery.small_width {
    width: 33.33333%;
  }
}

.single_gallery .thumb {
  border-radius: 0;
  height: 484px;
}

@media (min-width: 768px) and (max-width: 991px) {
  .single_gallery .thumb {
    height: 300px;
  }
}

@media (min-width: 992px) and (max-width: 1200px) {
  .single_gallery .thumb {
    height: 370px;
  }
}

@media (min-width: 1200px) and (max-width: 1500px) {
  .single_gallery .thumb {
    height: 350px;
  }
}

@media (max-width: 767px) {
  .single_gallery .thumb {
    height: auto;
  }
}

.single_gallery .thumb img {
  width: 100%;
  height: 100%;
  -webkit-transform: scale(1.2);
  -moz-transform: scale(1.2);
  -ms-transform: scale(1.2);
  transform: scale(1.2);
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
}

.single_gallery .gallery_hover {
  position: absolute;
  left: 0;
  bottom: 0;
}

.single_gallery .gallery_hover .hover_inner {
  position: relative;
  z-index: 12;
  padding-bottom: 60px;
  padding-left: 40px;
}

@media (max-width: 767px) {
  .single_gallery .gallery_hover .hover_inner {
    padding-left: 15px;
    padding-bottom: 20px;
  }
}

.single_gallery .gallery_hover .hover_inner span {
  display: block;
  font-size: 14px;
  color: #b3d9fc;
  font-weight: 400;
  margin-bottom: 13px;
  position: relative;
  left: 10%;
  opacity: 0;
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
}

@media (max-width: 767px) {
  .single_gallery .gallery_hover .hover_inner span {
    font-size: 14px;
  }
}

.single_gallery .gallery_hover .hover_inner h3 {
  font-size: 30px;
  color: #fff;
  font-weight: 400;
  line-height: 1;
  position: relative;
  left: 15%;
  opacity: 0;
  -webkit-transition: 0.4s;
  -moz-transition: 0.4s;
  -o-transition: 0.4s;
  transition: 0.4s;
}

@media (max-width: 767px) {
  .single_gallery .gallery_hover .hover_inner h3 {
    font-size: 20px;
  }
}

.single_gallery:hover::before {
  opacity: 1;
  left: -6%;
  bottom: -20%;
}

@media (max-width: 767px) {
  .single_gallery:hover::before {
    left: -10%;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  .single_gallery:hover::before {
    left: -13%;
  }
}

@media (min-width: 1200px) and (max-width: 1500px) {
  .single_gallery:hover::before {
    left: -10%;
  }
}

.single_gallery:hover .hover_inner h3,
.single_gallery:hover .hover_inner span {
  opacity: 1 !important;
  left: 0%;
}

.single_gallery:hover .thumb img {
  -webkit-transform: scale(1);
  -moz-transform: scale(1);
  -ms-transform: scale(1);
  transform: scale(1);
}
</style>