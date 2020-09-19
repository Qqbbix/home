<template>
<div>
    <b-carousel id="carousel-fade" style="text-shadow: 0px 0px 2px #000" fade indicators controls img-height="300">
        <b-carousel-slide>
            <template v-slot:img>
                <a href="http://dot.pi.ac.th/#/dashboard/tab">
                    <img class="d-block img-fluid w-100" width="1024" height="480" src="~assets/images/pidata.png" alt="image slot" />
                </a>
            </template>
        </b-carousel-slide>

        <b-carousel-slide img-src="~assets/images/nurse banner.jpg"></b-carousel-slide>
    </b-carousel>

    <section class="position-relative">
        <svg viewBox="0 0 1382 58" width="100%" height="60" preserveAspectRatio="none" style="position: absolute; top: -58px; left: 0; z-index: 1;">
            <path style="fill: #fff;" d="M1.52.62s802.13,127,1380,0v56H.51Z" />
        </svg>

        <div class="container">
            <div class="slider-feature w-100">
                <div class="row justify-content-center">
                    <div class="col-md-3 px-1">
                        <a href="https://admission.pi.in.th/admission/" class="card center border-left-0 border-right-0 border-top-0 border-bottom border-bottom shadow py-3 rounded-0 font-weight-semibold text-uppercase ls1">
                            <div class="card-body">
                                <i class="icon-line-align-center"></i>
                                ผู้สนใจเข้าศึกษา
                            </div>
                        </a>
                    </div>
                    <div class="col-md-3 px-1">
                        <a href="http://admission.pi.in.th/admission/" class="card center border-left-0 border-right-0 border-top-0 border-bottom border-bottom shadow py-3 rounded-0 font-weight-semibold text-uppercase ls1">
                            <div class="card-body">
                                <i class="icon-line-umbrella"></i>
                                นักศึกษาปัจจุบัน
                            </div>
                        </a>
                    </div>

                    <div class="col-md-3 px-1">
                        <NuxtLink :to="'/member'">
                            <div class="card center border-left-0 border-right-0 border-top-0 border-bottom border-bottom shadow py-3 rounded-0 font-weight-semibold text-uppercase ls1">
                                <div class="card-body">
                                    <i class="icon-line-mail"></i> บุคลากร
                                </div>
                            </div>
                        </NuxtLink>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section>
        <div class="container my-5 clearfix bg-color-light py-4 news">
            <div class="row clearfix justify-content-between">
                <div class="col-lg-8">
                    <div class="col-12">
                        <div class="fancy-title title-bottom-border">
                            <h3 style="
                                            display: flex;
                                            justify-content: space-between;
                                            align-items: center;
                                        ">
                                ข่าวสารจากเรา
                                <a href class="small float-right">ทั้งหมด</a>
                            </h3>
                        </div>
                    </div>
                    <div class="entry col-12">
                        <div class="grid-inner row no-gutters">
                            <div class="col-auto">
                                <div class="entry-image">
                                    <i class="fas fa-play"></i>
                                </div>
                            </div>
                            <div class="col pl-3">
                                <div class="entry-title">
                                    <h4>
                                        <a href="#">
                                            ประกาศสถาบันพระบรมราชชนก เรื่อง
                                            รายชื่อผู้มีสิทธิ์เข้ารับการประเมินความรู้ความสามารถ
                                            ทักษะ และสมรรถนะ กำหนดวัน เวลา
                                            สถานที่ในการประเมินความรู้
                                        </a>
                                    </h4>
                                </div>
                                <div class="entry-meta">
                                    <ul>
                                        <li>
                                            <i class="icon-comments-alt"></i>
                                            April 24, 2012 at 10:46 am
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="divider">
                        <i class="icon-circle"></i>
                    </div>

                    <div class="entry col-12">
                        <div class="grid-inner row no-gutters">
                            <div class="col-auto">
                                <div class="entry-image">
                                    <i class="fas fa-play"></i>
                                </div>
                            </div>
                            <div class="col pl-3">
                                <div class="entry-title">
                                    <h4>
                                        <a href="#">
                                            ประกาศสถาบันพระบรมราชชนก เรื่อง
                                            รายชื่อผู้มีสิทธิ์เข้ารับการประเมินความรู้ความสามารถ
                                            ทักษะ และสมรรถนะ กำหนดวัน เวลา
                                            สถานที่ในการประเมินความรู้
                                        </a>
                                    </h4>
                                </div>
                                <div class="entry-meta">
                                    <ul>
                                        <li>
                                            <i class="icon-comments-alt"></i>
                                            April 24, 2012 at 10:46 am
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="divider">
                        <i class="icon-circle"></i>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card cat-card rounded-0 border-0 dark">
                        <img src="~assets/images/head.png" class="card-img rounded-0" alt="..." />
                        <div class="d-flex flex-column card-img-overlay p-0">
                            <h3 class="h3 ls--1 font-weight-bold mt-2 mb-auto"></h3>
                            <div class="card-h">
                                <h5 class="h5 ls--1 font-weight-bold mb-2">ดร.ทัศนีย์ เกริกกุลธร</h5>
                                <p class="mb-0">รักษาการคณบดีคณะพยาบาลศาสตร์</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section>
        <div class="container mt-4">
            <div class="row">
                <div class="col-12">
                    <h2 class="text-capitalize text-center font-weight-semibold mb-2" style="font-size: 36px; letter-spacing: -1px;">
                        <span class="text-black gradient-underline">รอบรั้วคณะพยาบาล</span>
                    </h2>
                    <div class="grid-filter-wrap">
                        <ul class="grid-filter style-2 mx-auto mb-0" data-container="#portfolio">
                            <li class="activeFilter">
                                <a href="#" data-filter="*">ทั้งหมด</a>
                            </li>
                            <li>
                                <a href="#" data-filter=".pf-icons">งานวิจัย</a>
                            </li>
                            <li>
                                <a href="#" data-filter=".pf-illustrations">ประชุมสัมมนา</a>
                            </li>
                            <li>
                                <a href="#" data-filter=".pf-uielements">ข่าวสมัครงาน</a>
                            </li>
                            <li>
                                <a href="#" data-filter=".pf-media">ข่าวประกวดราคา</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="row mt-3">
                <div class="col-md-3">
                    <div class="posts-md">
                        <div class="entry">
                            <div class="entry-image">
                                <a href="#">
                                    <img src="http://www.pi.ac.th/timthumb.php?src=/uploads/contents/20200515150928SSyT8mh.jpg&w=650&h=510" alt="Image 3" />
                                </a>
                            </div>
                            <div class="entry-title title-sm nott">
                                <h3 class="mb-2">
                                    <a href="#">
                                        คณะพยาบาลศาสตร์ สถาบันพระบรมราชชนก ร่วมจัดทำ "ตู้ปันอิ่ม
                                        ปันใช้"
                                    </a>
                                </h3>
                            </div>
                            <div class="entry-meta">
                                <ul>
                                    <li>
                                        <a href="#">กองกลางและประชาสัมพันธ์</a>
                                    </li>
                                    <li>
                                        <i class="icon-time"></i>
                                        <a href="#">11 Mar 2021</a>
                                    </li>
                                </ul>
                            </div>
                            <div class="entry-content">
                                <p class="mb-0">
                                    ตามที่ได้มีประกาศสถาบันพระบรมราชชนก ลงวันที่ 27 พฤษภาคม พ.ศ.
                                    2563 เรื่อง
                                    รับสมัครบุคคลเพื่อเลือกสรรเป็นพนักงานราชการทั่วไป
                                    โดยจะประกาศรายชื่อผู้มีสิทธิ์เข้ารับการประเมินความรู้ความสามารถ
                                    ทักษะ และสมรรถนะ ครั้งที่ 1 ในวันที่ 22 มิถุนายน 2563 นั้น
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="posts-md">
                        <div class="entry">
                            <div class="entry-image">
                                <a href="#">
                                    <img src="http://www.pi.ac.th/timthumb.php?src=/uploads/contents/20200515150928SSyT8mh.jpg&w=650&h=510" alt="Image 3" />
                                </a>
                            </div>
                            <div class="entry-title title-sm nott">
                                <h3 class="mb-2">
                                    <a href="#">
                                        คณะพยาบาลศาสตร์ สถาบันพระบรมราชชนก ร่วมจัดทำ "ตู้ปันอิ่ม
                                        ปันใช้"
                                    </a>
                                </h3>
                            </div>
                            <div class="entry-meta">
                                <ul>
                                    <li>
                                        <a href="#">กองกลางและประชาสัมพันธ์</a>
                                    </li>
                                    <li>
                                        <i class="icon-time"></i>
                                        <a href="#">11 Mar 2021</a>
                                    </li>
                                </ul>
                            </div>
                            <div class="entry-content">
                                <p class="mb-0">
                                    ตามที่ได้มีประกาศสถาบันพระบรมราชชนก ลงวันที่ 27 พฤษภาคม พ.ศ.
                                    2563 เรื่อง
                                    รับสมัครบุคคลเพื่อเลือกสรรเป็นพนักงานราชการทั่วไป
                                    โดยจะประกาศรายชื่อผู้มีสิทธิ์เข้ารับการประเมินความรู้ความสามารถ
                                    ทักษะ และสมรรถนะ ครั้งที่ 1 ในวันที่ 22 มิถุนายน 2563 นั้น
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="posts-md">
                        <div class="entry">
                            <div class="entry-image">
                                <a href="#">
                                    <img src="http://www.pi.ac.th/timthumb.php?src=/uploads/contents/20200515150928SSyT8mh.jpg&w=650&h=510" alt="Image 3" />
                                </a>
                            </div>
                            <div class="entry-title title-sm nott">
                                <h3 class="mb-2">
                                    <a href="#">
                                        คณะพยาบาลศาสตร์ สถาบันพระบรมราชชนก ร่วมจัดทำ "ตู้ปันอิ่ม
                                        ปันใช้"
                                    </a>
                                </h3>
                            </div>
                            <div class="entry-meta">
                                <ul>
                                    <li>
                                        <a href="#">กองกลางและประชาสัมพันธ์</a>
                                    </li>
                                    <li>
                                        <i class="icon-time"></i>
                                        <a href="#">11 Mar 2021</a>
                                    </li>
                                </ul>
                            </div>
                            <div class="entry-content">
                                <p class="mb-0">
                                    ตามที่ได้มีประกาศสถาบันพระบรมราชชนก ลงวันที่ 27 พฤษภาคม พ.ศ.
                                    2563 เรื่อง
                                    รับสมัครบุคคลเพื่อเลือกสรรเป็นพนักงานราชการทั่วไป
                                    โดยจะประกาศรายชื่อผู้มีสิทธิ์เข้ารับการประเมินความรู้ความสามารถ
                                    ทักษะ และสมรรถนะ ครั้งที่ 1 ในวันที่ 22 มิถุนายน 2563 นั้น
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="posts-md">
                        <div class="entry">
                            <div class="entry-image">
                                <a href="#">
                                    <img src="http://www.pi.ac.th/timthumb.php?src=/uploads/contents/20200515150928SSyT8mh.jpg&w=650&h=510" alt="Image 3" />
                                </a>
                            </div>
                            <div class="entry-title title-sm nott">
                                <h3 class="mb-2">
                                    <a href="#">
                                        คณะพยาบาลศาสตร์ สถาบันพระบรมราชชนก ร่วมจัดทำ "ตู้ปันอิ่ม
                                        ปันใช้"
                                    </a>
                                </h3>
                            </div>
                            <div class="entry-meta">
                                <ul>
                                    <li>
                                        <a href="#">กองกลางและประชาสัมพันธ์</a>
                                    </li>
                                    <li>
                                        <i class="icon-time"></i>
                                        <a href="#">11 Mar 2021</a>
                                    </li>
                                </ul>
                            </div>
                            <div class="entry-content">
                                <p class="mb-0">
                                    ตามที่ได้มีประกาศสถาบันพระบรมราชชนก ลงวันที่ 27 พฤษภาคม พ.ศ.
                                    2563 เรื่อง
                                    รับสมัครบุคคลเพื่อเลือกสรรเป็นพนักงานราชการทั่วไป
                                    โดยจะประกาศรายชื่อผู้มีสิทธิ์เข้ารับการประเมินความรู้ความสามารถ
                                    ทักษะ และสมรรถนะ ครั้งที่ 1 ในวันที่ 22 มิถุนายน 2563 นั้น
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <div class="section p-0 dark mb-0 bg-about">
        <svg class="svg-curve" viewBox="0 0 1463 188.03" style="transform: rotate(180deg);">
            <path style="fill: #fff;" d="M-.5,288.5s297-175,792-97,599,52,671,25v143H-.5Z" transform="translate(0 -171.47)" />
        </svg>
        <div class="container">
            <div class="row justify-content-between mb-4" style="padding: 100px 0 50px;">
                <div class="col-lg-5 col-md-6 offset-lg-1 pt-3"></div>
                <div class="col-lg-5 col-md-6 mb-0 mb-md-5">
                    <p class="mb-5">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Incidunt
                        distinctio dolor nemo quasi cum. A ipsam tempora voluptatem
                        officiis! Accusantium!
                    </p>
                    <h2 class="mb-2 text-white text-center">มาเป็นส่วนหนึ่งกับครอบครัวเรา</h2>
                    <div class="d-flex">
                        <div class="row align-items-stretch m-0 w-100 clearfix">
                            <div class="col-lg-6 col-sm-6 center mt-5">
                                <i class="fas fa-user-nurse" style=" font-size: 5rem;"></i>
                                <div class="counter font-secondary">
                                    <span data-from="100" data-to="51231" data-refresh-interval="50" data-speed="2100" data-comma="true">39</span>+
                                </div>
                                <h5 class="nott ls0 mt-0">
                                    <u>นักศึกษาที่จบ</u>
                                </h5>
                            </div>
                            <div class="col-lg-6 col-sm-6 center mt-5">
                                <i class="fas fa-user-nurse" style=" font-size: 5rem; "></i>
                                <div class="counter font-secondary">
                                    <span data-from="100" data-to="2500" data-refresh-interval="50" data-speed="2200" data-comma="true">4,500</span>+
                                </div>
                                <h5 class="nott ls0 mt-0">
                                    <u>นักศึกษาปัจจุบัน</u>
                                </h5>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="clear"></div>
        <a class="py-4" target="_blank" href="https://youtu.be/Wo6c38_srB8">
            <img src="~assets/images/bn.jpg" alt class="w-100" />
        </a>
    </div>

    <div id="portfolio" class="portfolio row grid-container no-gutters">
        <div class="col-lg-4 col-sm-6 rounded img-hover-wrap" v-for="item in college" :key="item.name">
            <a target="_blank" :href="`${item.href}`">
                <div class="img-hover-card" style="perspective: 1000px; transform-style: preserve-3d; transform: rotateX(0deg) rotateY(0deg);">
                    <!-- <a href="#" data-lightbox="image"
            ><img src="~assets/images/1200_900/วพบ.นครราชสีมา.jpg" alt="Image"
            /></a>-->
                    <!-- <img
            :src="require('~/assets/images/1200_900/' + item.name + '.jpg')"
            alt=""
            srcset=""
            />-->
                    <!-- <img
            :src="`./1200_900/${item.name}.jpg`"
            alt=""
            @error="imgPlaceholder"
            />-->
                    <img :src="`${item.img}`" alt @error="imgPlaceholder" />
                    <div class="img-hover-detail">
                        <h3 class="img-hover-title">
                            <a href="#">{{ item.name }}</a>
                        </h3>
                        <div class="img-link">
                            <a href="#">
                                <i class="icon-line-arrow-right"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </a>
        </div>
    </div>
</div>
</template>

<script>
export default {
    data() {
        return {
            college: [{
                    name: "วพบ.กรุงเทพ",
                    img: "./1200_900/วพบ.กรุงเทพ.jpg",
                    href: "http://www.bcn.ac.th/",
                },
                {
                    name: "วพบ.ขอนแก่น",
                    img: "./1200_900/วพบ.ขอนแก่น.jpg",
                    href: "http://www.bcnkk.ac.th/",
                },
                {
                    name: "วพบ.จักรีรัช",
                    img: "./1200_900/วพบ.จักรีรัช.jpg",
                    href: "http://www.ckr.ac.th/",
                },
                {
                    name: "วพบ.ชลบุรี",
                    img: "./1200_900/วพบ.ชลบุรี.jpg",
                    href: "http://www.bnc.ac.th/",
                },
                {
                    name: "วพบ.ชัยนาท",
                    img: "./1200_900/วพบ.ชัยนาท.jpg",
                    href: "http://www.bcnchainat.ac.th/index.php",
                },
                {
                    name: "วพบ.เชียงใหม่",
                    img: "./1200_900/noimg.png",
                    href: "http://www.bcnc.ac.th/",
                },
                {
                    name: "วพบ.ตรัง",
                    img: "./1200_900/noimg.png",
                    href: "http://www.bcnt.ac.th/",
                },
                {
                    name: "วพบ.นครราชสีมา",
                    img: "./1200_900/วพบ.นครราชสีมา.jpg",
                    href: "http://www.knc.ac.th/",
                },
                {
                    name: "วพบ.นครลำปาง",
                    img: "./1200_900/วพบ.นครลำปาง.jpg",
                    href: "http://www.bcnlp.ac.th/main/Person.php",
                },
                {
                    name: "วพบ.นครศรีธรรมราช",
                    img: "./1200_900/noimg.png",
                    href: "http://www.bcnnakhon.ac.th/",
                },
                {
                    name: "วพบ.นนทบุรี",
                    img: "./1200_900/วพบ.นนทบุรี.jpg",
                    href: "http://www.bcnnon.ac.th/",
                },
                {
                    name: "วพบ.นพรัตน์วชิระ",
                    img: "./1200_900/วพบ.นพรัตน์วชิระ.jpg",
                    href: "http://www.bcnnv.ac.th/",
                },
                {
                    name: "วพบ.พระพุทธบาท",
                    img: "./1200_900/noimg.png",
                    href: "http://www.bcnpb.ac.th/",
                },
                {
                    name: "วพบ.พะเยา",
                    img: "./1200_900/noimg.png",
                    href: "http://www.bcnpy.ac.th/bcnpy/index.php/th/",
                },
                {
                    name: "วพบ.พุทธชินราช",
                    img: "./1200_900/วพบ.พุทธชินราช.jpg",
                    href: "http://www.bcnb.ac.th/",
                },
                {
                    name: "วพบ.แพร่",
                    img: "./1200_900/วพบ.แพร่.jpg",
                    href: "http://www.bcnph.ac.th/",
                },
                {
                    name: "วพบ.ยะลา",
                    img: "./1200_900/วพบ.ยะลา.jpg",
                    href: "http://www.bcnyala.ac.th/",
                },
                {
                    name: "วพบ.ราชบุรี",
                    img: "./1200_900/วพบ.ราชบุรี.jpg",
                    href: "http://www.bcnr.ac.th/",
                },
                {
                    name: "วพบ.สงขลา",
                    img: "./1200_900/วพบ.สงขลา.jpg",
                    href: "http://www.bcnsk.ac.th/",
                },
                {
                    name: "วพบ.สรรพสิทธิประสงค์",
                    img: "./1200_900/noimg.png",
                    href: "http://www.bcnsp.ac.th/",
                },
                {
                    name: "วพบ.สระบุรี",
                    img: "./1200_900/วพบ.สระบุรี.jpg",
                    href: "http://www.bcns.ac.th/",
                },
                {
                    name: "วพบ.สวรรค์ประชารักษ์",
                    img: "./1200_900/วพบ.สวรรค์ประชารักษ.jpg",
                    href: "http://www.bcnsprnw.ac.th/",
                },
                {
                    name: "วพบ.สุพรรณบุรี",
                    img: "./1200_900/วพบ.สุพรรณบุรี.jpg",
                    href: "http://www.snc.ac.th/",
                },
                {
                    name: "วพบ.สุราษฎร์ธานี",
                    img: "./1200_900/noimg.png",
                    href: "http://www.bcnsurat.ac.th/",
                },
                {
                    name: "วพบ.สุรินทร์",
                    img: "./1200_900/วพบ.สุรินทร์.jpg",
                    href: "http://www.bcnsurin.ac.th/",
                },
                {
                    name: "วพบ.อุดรธานี",
                    img: "./1200_900/วพบ.อุดรธานี.jpg",
                    href: "http://www.bcnu.ac.th/",
                },
                {
                    name: "วพบ.อุตรดิตถ์",
                    img: "./1200_900/noimg.png",
                    href: "http://www.unc.ac.th/",
                },
                {
                    name: "วพ.พระจอมเกล้า จังหวัด เพชรบุรี",
                    img: "./1200_900/วพ.พระจอมเกล้าเพชรบุรี.jpg",
                    href: "http://www.PCKPB.ac.th/",
                },
                {
                    name: "วพ.พระปกเกล้า จันทบุรี",
                    img: "./1200_900/วพ.พระปกเกล้า จันทบุรี.jpg",
                    href: "http://www.pnc.ac.th/",
                },
                {
                    name: "วพ.ศรีมหาสารคาม",
                    img: "./1200_900/noimg.png",
                    href: "http://www.smnc.ac.th/",
                },
            ],
        };
    },
    methods: {
        imgPlaceholder(e) {
            e.target.src = "https://via.placeholder.com/300";
        },
    },
};
</script>

<style></style>
