<template>
  <div>
    <TopHeader />
    <header id="header" data-menu-padding="28" data-sticky-menu-padding="8">
      <div id="header-wrap" class="gradient-header">
        <div class="container">
          <div class="header-row">
            <!-- Logo
						============================================= -->
            <div id="logo" class="logo mb-0">
              <h2 class="mb-0">LOGO</h2>
            </div>
            <!-- <div id="logo">
              <a href="index.html" class="standard-logo"
                ><img
                  src="demos/medical/images/logo-medical.png"
                  alt="Canvas Logo"
              /></a>

              <a href="index.html" class="retina-logo"
                ><img
                  src="demos/medical/images/logo-medical@2x.png"
                  alt="Canvas Logo"
              /></a>
            </div> -->
            <!-- #logo end -->

            <div id="primary-menu-trigger">
              <svg class="svg-trigger" viewBox="0 0 100 100">
                <path
                  d="m 30,33 h 40 c 3.722839,0 7.5,3.126468 7.5,8.578427 0,5.451959 -2.727029,8.421573 -7.5,8.421573 h -20"
                ></path>
                <path d="m 30,50 h 40"></path>
                <path
                  d="m 70,67 h -40 c 0,0 -7.5,-0.802118 -7.5,-8.365747 0,-7.563629 7.5,-8.634253 7.5,-8.634253 h 20"
                ></path>
              </svg>
            </div>

            <!-- Primary Navigation
						============================================= -->
            <nav class="primary-menu style-3 menu-spacing-margin">
              <ul class="menu-container">
                <li class="menu-item ">
                  <NuxtLink class="menu-link" :to="'/'">
                    <div>หน้าแรก</div>
                  </NuxtLink>
                </li>
                <li class="menu-item">
                  <NuxtLink :to="'/member'" class="menu-link">
                    <div>หลักสูตร</div>
                  </NuxtLink>
                </li>
                <li class="menu-item">
                  <a class="menu-link" href="demo-medical-departments.html">
                    <div>ข่าวสารจากเรา</div>
                  </a>
                </li>
                <li class="menu-item">
                  <a class="menu-link" href="demo-medical-appointment.html">
                    <div>บริการนักศึกษา</div>
                  </a>
                </li>
                <li class="menu-item">
                  <a class="menu-link" href="demo-medical-doctors.html">
                    <div>เกี่ยวกับเรา</div>
                  </a>
                  <ul class="sub-menu-container">
                    <li class="menu-item">
                      <a
                        class="menu-link"
                        href="demo-medical-doctors-lists.html"
                      >
                        <div>
                          2 columns - List style
                        </div>
                      </a>
                    </li>
                    <li class="menu-item">
                      <a class="menu-link" href="demo-medical-doctors-3.html">
                        <div>3 columns</div>
                      </a>
                    </li>
                    <li class="menu-item">
                      <a class="menu-link" href="demo-medical-doctors.html">
                        <div>4 columns</div>
                      </a>
                    </li>
                  </ul>
                </li>
                <li class="menu-item">
                  <a class="menu-link" href="demo-medical-contact.html">
                    <div>ติดต่อเรา</div>
                  </a>
                </li>
              </ul>
            </nav>
            <!-- #primary-menu end -->
          </div>
        </div>
      </div>
      <div class="header-wrap-clone"></div>
    </header>
  </div>
</template>

<script></script>

<style></style>
