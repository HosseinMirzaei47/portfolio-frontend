<template>
  <header>
    <div class="header-area">
      <div id="sticky-header" class="main-header-area">
        <div class="container-fluid">
          <div class="row align-items-center">
            <div class="col-xl-3 col-lg-2">
              <div class="logo">
                <a href="#">
                  <img
                    src="data:image/webp;base64,UklGRjoCAABXRUJQVlA4TC0CAAAvlcAIEIcw//M//2obSWqTn3n/kNEPAfjHw0Uj4TAoGAIGgYEgICDbtlKHEUMSNT74/9/NBSFtZx1E9N+B27aRpJm9Lzlts31D+j92MDP/LXti5sPSEHXMQlaIB126EaVovUepdDEP2olQyH5AOGVetcM1ULFlA+PQNaqWSicD484XeOyDkOlcDW7mq06IoYPOep5lvAJk5GDm0rXwwcyMzsyKxniQ0z4ALREZRWV/NCc4TZGma3uj/b20fjEFBAIZzq6J4LQPMEQW6tNrWzeJKqq+hS/a+HwzbXIQVCCOy96Jri/bRTysRIbqA9NPH01k7nJ8hMs+wNoIw0zBRFq5q/m9q/Vh58hQ0Tg+ezdsLm9UW2aiGwMcGzmtZeSgDkvGywPvzslr7+a2g2BxCERn730JjDXYGHLGuELpSimgdyU3eNTktffgccE6nnafbNmVQ7SzPtadfgL5EDYYvfdyw0iHxnz1ISIFun746c8frOR7cCZ7kKGV2M0kGzmmUU/vW4L2bg5j2Rp90UXb1KxDZ9E5Tng9Qtze+UVT5DFkCGa+hyz2vzVY6RyQYFGEoL0Pw8quYnYBC+qhpLtUIzPHASED/3Sf2W9Fu+hpRg36q4/0KkkrpU0RGVmHG9rpCPGB/SrvcW12Be/qXbWUZ0HdfEBRjaOaex8930aAD+y1yNjtoNqm37lJGfYyMhsMh2OvcgUI2AdJidsCnZI/2FS/Zh8cv8ieYD/4P+tICQA="
                    alt=""
              
                  />
                </a>
              </div>
            </div>
            <div class="col-xl-9 col-lg-10">
              <div class="main-menu d-none d-lg-block text-right">
                <nav>
                  <ul id="navigation">
                    <li><a class="active" href="#">home</a></li>
                    <li><a href="#">Projects</a></li>
                    <li>
                      <a href="#">Discuss Projects <i class="ti-angle-down"></i></a>
                    </li>
                    <li><a href="#">Contact</a></li>
                  </ul>
                </nav>
              </div>
            </div>
            <div class="col-12">
              <div class="mobile_menu d-block d-lg-none">
                <div class="slicknav_menu">
                  <a
                    href="#"
                    aria-haspopup="true"
                    role="button"
                    tabindex="0"
                    class="slicknav_btn slicknav_collapsed"
                    style=""
                    ><span class="slicknav_menutxt">MENU</span
                    ><span class="slicknav_icon"
                      ><span class="slicknav_icon-bar"></span
                      ><span class="slicknav_icon-bar"></span
                      ><span class="slicknav_icon-bar"></span></span
                  ></a>
                  <ul
                    class="slicknav_nav slicknav_hidden"
                    style="display: none"
                    aria-hidden="true"
                    role="menu"
                  >
                    <li>
                      <a class="active" href="#" role="menuitem" tabindex="-1"
                        >home</a
                      >
                    </li>
                    <li>
                      <a href="#" role="menuitem" tabindex="-1">Projects</a>
                    </li>
                    <li class="slicknav_collapsed slicknav_parent">
                      <a
                        href="#"
                        role="menuitem"
                        aria-haspopup="true"
                        tabindex="-1"
                        class="slicknav_item slicknav_row"
                        style=""
                      >
                        <a href="#" tabindex="-1"
                          >Discuss Projects <i class="ti-angle-down"></i
                        ></a>
                        <span class="slicknav_arrow">+</span></a
                      >
                    </li>
                    <li class="slicknav_collapsed slicknav_parent">
                      <a
                        href="#"
                        role="menuitem"
                        aria-haspopup="true"
                        tabindex="-1"
                        class="slicknav_item slicknav_row"
                        style=""
                        ><a href="#" tabindex="-1"
                          >pages <i class="ti-angle-down"></i
                        ></a>
                        <span class="slicknav_arrow">+</span></a
                      >
                      <ul
                        class="submenu slicknav_hidden"
                        role="menu"
                        style="display: none"
                        aria-hidden="true"
                      >
                        <li>
                          <a role="menuitem" href="#" tabindex="-1"
                            >Portfolio work</a
                          >
                        </li>
                        <li>
                          <a role="menuitem" href="#" tabindex="-1"
                            >work details</a
                          >
                        </li>
                        <li>
                          <a role="menuitem" href="#" tabindex="-1">Services</a>
                        </li>
                        <li>
                          <a role="menuitem" href="#" tabindex="-1">elements</a>
                        </li>
                      </ul>
                    </li>
                    <li>
                      <a role="menuitem" href="#" tabindex="-1">Contact</a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
.header-area {
  left: 0;
  right: 0;
  width: 100%;
  top: 0;
  z-index: 99;
  position: absolute;
}

.header-area .main-header-area {
  padding: 29px 85px;
  background: #fff;
  background: transparent;
}


.header-area .main-header-area .main-menu {
  text-align: center;
  padding: 12px 0;
}

.header-area .main-header-area .main-menu ul li {
  display: inline-block;
  position: relative;
  margin: 0 0 0 47px;
}

.header-area .main-header-area .main-menu ul li a {
  color: #fff;
  font-size: 15px;
  text-transform: capitalize;
  font-weight: 400;
  display: inline-block;
  padding: 0px 0px 0px 0px;
  position: relative;
  text-transform: capitalize;
}

.header-area .main-header-area .main-menu ul li a i {
  font-size: 9px;
}

.header-area .main-header-area .main-menu ul li a:hover::before {
  opacity: 1;
  transform: scaleX(1);
}

.header-area .main-header-area .main-menu ul li a.active::before {
  opacity: 1;
  transform: scaleX(1);
}

.header-area .main-header-area .main-menu ul li .submenu {
  position: absolute;
  left: 0;
  top: 160%;
  background: #fff;
  width: 200px;
  z-index: 2;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.02);
  opacity: 0;
  visibility: hidden;
  text-align: left;
  -webkit-transition: 0.6s;
  -moz-transition: 0.6s;
  -o-transition: 0.6s;
  transition: 0.6s;
}

.header-area .main-header-area .main-menu ul li .submenu li {
  display: block;
  margin-left: 0;
}

.header-area .main-header-area .main-menu ul li .submenu li a {
  padding: 10px 25px;
  position: inherit;
  -webkit-transition: 0.3s;
  -moz-transition: 0.3s;
  -o-transition: 0.3s;
  transition: 0.3s;
  display: block;
  color: #000;
}

.header-area .main-header-area .main-menu ul li .submenu li a::before {
  display: none;
}

.header-area .main-header-area .main-menu ul li .submenu li:hover a {
  color: #000;
}

.header-area .main-header-area .main-menu ul li:hover > .submenu {
  opacity: 1;
  visibility: visible;
  top: 150%;
}

.header-area .main-header-area .main-menu ul li:hover > a::before {
  opacity: 1;
  transform: scaleX(1);
}

.header-area .main-header-area .main-menu ul li:first-child a {
  padding-left: 0;
}

.header-area .main-header-area.sticky {
  box-shadow: 0px 3px 16px 0px rgba(0, 0, 0, 0.1);
  position: fixed;
  width: 100%;
  top: -70px;
  left: 0;
  right: 0;
  z-index: 990;
  transform: translateY(70px);
  transition: transform 500ms ease, background 500ms ease;
  -webkit-transition: transform 500ms ease, background 500ms ease;
  box-shadow: 0px 3px 16px 0px rgba(0, 0, 0, 0.1);
  background: #040e27;
}

.header-area .main-header-area.sticky .main-menu {
  padding: 0;
}
</style>