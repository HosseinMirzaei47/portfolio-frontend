<template>
  <footer class="footer">
    <div class="footer_top">
      <div class="container">
        <div class="row">
          <div class="col-xl-4 col-md-6 col-lg-4">
            <div class="footer_widget">
              <div class="logo_footer">
                <a href="index.html">
                  <img
                    src="data:image/webp;base64,UklGRjoCAABXRUJQVlA4TC0CAAAvlcAIEIcw//M//2obSWqTn3n/kNEPAfjHw0Uj4TAoGAIGgYEgICDbtlKHEUMSNT74/9/NBSFtZx1E9N+B27aRpJm9Lzlts31D+j92MDP/LXti5sPSEHXMQlaIB126EaVovUepdDEP2olQyH5AOGVetcM1ULFlA+PQNaqWSicD484XeOyDkOlcDW7mq06IoYPOep5lvAJk5GDm0rXwwcyMzsyKxniQ0z4ALREZRWV/NCc4TZGma3uj/b20fjEFBAIZzq6J4LQPMEQW6tNrWzeJKqq+hS/a+HwzbXIQVCCOy96Jri/bRTysRIbqA9NPH01k7nJ8hMs+wNoIw0zBRFq5q/m9q/Vh58hQ0Tg+ezdsLm9UW2aiGwMcGzmtZeSgDkvGywPvzslr7+a2g2BxCERn730JjDXYGHLGuELpSimgdyU3eNTktffgccE6nnafbNmVQ7SzPtadfgL5EDYYvfdyw0iHxnz1ISIFun746c8frOR7cCZ7kKGV2M0kGzmmUU/vW4L2bg5j2Rp90UXb1KxDZ9E5Tng9Qtze+UVT5DFkCGa+hyz2vzVY6RyQYFGEoL0Pw8quYnYBC+qhpLtUIzPHASED/3Sf2W9Fu+hpRg36q4/0KkkrpU0RGVmHG9rpCPGB/SrvcW12Be/qXbWUZ0HdfEBRjaOaex8930aAD+y1yNjtoNqm37lJGfYyMhsMh2OvcgUI2AdJidsCnZI/2FS/Zh8cv8ieYD/4P+tICQA="
                    alt=""
                  />
                </a>
              </div>
            </div>
          </div>
          <div class="col-xl-3 col-md-6 col-lg-3">
            <div class="footer_widget">
              <h3 class="footer_title">Services</h3>
              <ul>
                <li><a href="#">Web Design</a></li>
                <li><a href="#">3D Modeling</a></li>
                <li><a href="#">Architectural Design</a></li>
              </ul>
            </div>
          </div>
          <div class="col-xl-3 col-md-6 col-lg-3">
            <div class="footer_widget">
              <h3 class="footer_title">Useful Links</h3>
              <ul>
                <li><a href="#">Work</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
              </ul>
            </div>
          </div>
          <div class="col-xl-2 col-md-6 col-lg-2">
            <div class="footer_widget">
              <h3 class="footer_title">Follow Us</h3>
              <ul>
                <li><a href="#">Dribbble</a></li>
                <li><a href="#">Behance</a></li>
                <li><a href="#">Instagram</a></li>
                <li><a href="#">Facebook</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="copy-right_text">
      <div class="container">
        <div class="row">
          <div class="col-xl-12">
            <p class="copy_right text-center">
              Copyright © 2021 All rights reserved
              <i class="fa fa-heart-o" aria-hidden="true"></i> by
              <a href="#">Hossein Mirzazadeh</a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  background-repeat: no-repeat;
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  background: #040e27;
}

.footer .footer_top {
  padding-top: 116px;
  padding-bottom: 190px;
}

@media (max-width: 767px) {
  .footer .footer_top {
    padding-top: 60px;
    padding-bottom: 30px;
  }
}

.footer .footer_top .footer_widget {
  margin-bottom: 30px;
}

.footer .footer_top .footer_widget .footer_title {
  font-size: 20px;
  font-weight: 400;
  color: #fff;
  text-transform: capitalize;
  margin-bottom: 40px;
}

@media (max-width: 767px) {
  .footer .footer_top .footer_widget .footer_title {
    margin-bottom: 20px;
  }
}

.footer .footer_top .footer_widget ul li {
  color: #aab1b7;
  font-size: 14px;
  line-height: 42px;
}

.footer .footer_top .footer_widget ul li a {
  color: #aab1b7;
  font-weight: 400;
}

.footer .footer_top .footer_widget ul li a:hover {
  color: #fff;
}

.footer .footer_top .footer_widget p {
  color: #596672;
  font-size: 14px;
  font-weight: 400;
  line-height: 42px;
}

.footer .footer_top .footer_widget p a {
  color: #596672;
}

.footer .footer_top .footer_widget p a:hover {
  color: #fff;
}
</style>