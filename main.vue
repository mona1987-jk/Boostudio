<template>
  <div>
    <section class="position-relative" id="section1">
      <h1>boostudio</h1>
      <img src="../assets/img/teamwork-makes-the-dream-work4.jpg" alt="">
    </section>
    <section id="section2">
      <div class="title-section2">WELCOME TO BOOSTUDIO!</div>
      <div class="title-section2"><span>YOUR BRAND ACTIVATION PARTNER</span></div>
      <div class="para-section2">Helping you deliver unique, impactful brand experiences in retail, design, events, &
        technology.
      </div>
    </section>

    <!-- Section 3 -->
    <div id="section3">
      <b-row>
        <b-col class="design-box-section3" lg="6">
          <div class="h2">Design</div>
          <div class="p"> Our team will help you discover your ‘Brand Attraction' through creative design.</div>
          <button class="btn1-section3">Find out more</button>
        </b-col>
        <hr>
        <b-col lg="6" class="installation-box-section3">
          <div class="h2">Installation</div>
          <div class="p"> Expert break-fix, installation, and retail solutions to ensure your displays, storefronts and
            products are ready to meet your customers.
          </div>
          <button class="btn2-section3">Find out more</button>
        </b-col>
      </b-row>
    </div>
    <!--END OF SECTION-->
    <!-- section with images and images on background -->
    <div id="section-image1">
      <b-row>
        <b-col class="left-box" lg="4" sm="12">
          <h1><span style="color: #4885ed">G</span><span style="color: #f4c20d">o</span><span style="color: #db3236">o</span><span style="color: #4885ed">g</span><span style="color:#3cba54">l</span><span style="color: #db3236">e</span></h1><br>
          <h2>  Connected Home Tables - Nationwide Rollout</h2><br>
          <a href="" ><u>VIEW OUR PROJECTS</u></a>
        </b-col>
        <b-col class="section3-image" lg="8" sm="12">

        </b-col>
      </b-row>
    </div>
    <!-- second image background -->
    <div class="hero-bkg-animated">
      <h1>GOOGLE</h1>
      <h1>  Connected Home Tables - Nationwide Rollout</h1>
      <a href="" ><u>VIEW OUR PROJECTS</u></a>
    </div>
    <!-- Orange background -->
    <div id="section-orange-bg">
      <b-row>
        <b-col class="left-orange-box" lg="6">
          <div class="orange-bg-h2">Design</div>
          <div class="orange-bg-p"> Our team will help you discover your ‘Brand Attraction' through creative design.</div>
          <button class="btn1-section-orange-bg">Find out more</button>
        </b-col>
        <hr>
        <b-col lg="6" class="left-orange-box">
          <div class="orange-bg-h2">Installation</div>
          <div class="orange-bg-p"> Expert break-fix, installation, and retail solutions to ensure your displays, storefronts and
            products are ready to meet your customers.
          </div>
          <button class="btn2-section-orange-bg">Find out more</button>
        </b-col>
      </b-row>
    </div>

    <!-- END OF THIS SECTION -->
    <!-- SECTION 4 Carousel images with hover -->
    <div id="section4">
      <div class="h3 text-center mb-4">FOLLOW OUR SOCIAL POSTS</div>
      <hr id="hr2">
      <carousel :loop="true" class="mt-5" :autoplay="true" :per-page="4" style="height: 450px">
        <slide>
          <div class="imagelist" >


            <a href="">
              <img src="../assets/img/letsgetcooking.png" class="follow-us-image" style="width:100%;height:100%">


              <p class="imgtext">
                <span>
                    <span>
                   This certainly is not the prettiest side of what we do as a business, but it’s certainly one of the most important parts;
                    ✔️ Warehousing
                    ✔️ Logistics
                    ✔️ Pick and Pack
                    ✔️ Order fulfilment

                    The future of how we do this is super exciting:
                    We’re on the cusp of automating everything excluding the labour of packing and preparing, meaning orders are dispatched quicker and we can give you a better overview of what part of the process your order is at, including delivery statuses right up to when it’s delivered.

                    #boostudio #parcel #logistics #warehousing #pickandpack #orderfufillment #fufillment #sydney #australia
                    </span></span>
              </p>
            </a>
          </div>

        </slide>
        <slide>

          <div class="imagelist" >
            <a href="">
              <img src="../assets/img/followus3.png" class="follow-us-image" width="100%" height="100%">
              <p class="imgtext">
                <span>
                    <span>
                   This certainly is not the prettiest side of what we do as a business, but it’s certainly one of the most important parts;
                    ✔️ Warehousing
                    ✔️ Logistics
                    ✔️ Pick and Pack
                    ✔️ Order fulfilment

                    The future of how we do this is super exciting:
                    We’re on the cusp of automating everything excluding the labour of packing and preparing, meaning orders are dispatched quicker and we can give you a better overview of what part of the process your order is at, including delivery statuses right up to when it’s delivered.

                    #boostudio #parcel #logistics #warehousing #pickandpack #orderfufillment #fufillment #sydney #australia
                    </span></span>
              </p>
            </a>
          </div>
        </slide>
        <slide>


          <div class="imagelist" >
            <a href="">
              <img src="../assets/img/followus6.png" class="follow-us-image" width="100%" height="100%">
              <p class="imgtext">
                <span>
                    <span>
                   This certainly is not the prettiest side of what we do as a business, but it’s certainly one of the most important parts;
                    ✔️ Warehousing
                    ✔️ Logistics
                    ✔️ Pick and Pack
                    ✔️ Order fulfilment

                    The future of how we do this is super exciting:
                    We’re on the cusp of automating everything excluding the labour of packing and preparing, meaning orders are dispatched quicker and we can give you a better overview of what part of the process your order is at, including delivery statuses right up to when it’s delivered.

                    #boostudio #parcel #logistics #warehousing #pickandpack #orderfufillment #fufillment #sydney #australia
                    </span></span>
              </p>
            </a>
          </div>
        </slide>
        <slide>

          <div class="imagelist" >
            <a href="">
              <img src="../assets/img/letsgetcooking.png" class="follow-us-image" width="100%" height="100%">
              <p class="imgtext">
                <span>
                    <span>
                   This certainly is not the prettiest side of what we do as a business, but it’s certainly one of the most important parts;
                    ✔️ Warehousing
                    ✔️ Logistics
                    ✔️ Pick and Pack
                    ✔️ Order fulfilment

                    The future of how we do this is super exciting:
                    We’re on the cusp of automating everything excluding the labour of packing and preparing, meaning orders are dispatched quicker and we can give you a better overview of what part of the process your order is at, including delivery statuses right up to when it’s delivered.

                    #boostudio #parcel #logistics #warehousing #pickandpack #orderfufillment #fufillment #sydney #australia
                    </span></span>
              </p>
            </a>
          </div>
        </slide>
        <slide>
          <div class="imagelist" >
            <a href="">
              <img src="../assets/img/followus6.png" class="follow-us-image" width="100%" height="100%">
              <p class="imgtext">
                <span>
                    <span>
                   This certainly is not the prettiest side of what we do as a business, but it’s certainly one of the most important parts;
                    ✔️ Warehousing
                    ✔️ Logistics
                    ✔️ Pick and Pack
                    ✔️ Order fulfilment

                    The future of how we do this is super exciting:
                    We’re on the cusp of automating everything excluding the labour of packing and preparing, meaning orders are dispatched quicker and we can give you a better overview of what part of the process your order is at, including delivery statuses right up to when it’s delivered.

                    #boostudio #parcel #logistics #warehousing #pickandpack #orderfufillment #fufillment #sydney #australia
                    </span></span>
              </p>
            </a>
          </div>
        </slide>
        <slide>
          <div class="imagelist" >
            <a href="">
              <img src="../assets/img/followus3.png" class="follow-us-image" width="100%" height="100%">
              <p class="imgtext">
                <span>
                    <span>
                   This certainly is not the prettiest side of what we do as a business, but it’s certainly one of the most important parts;
                    ✔️ Warehousing
                    ✔️ Logistics
                    ✔️ Pick and Pack
                    ✔️ Order fulfilment

                    The future of how we do this is super exciting:
                    We’re on the cusp of automating everything excluding the labour of packing and preparing, meaning orders are dispatched quicker and we can give you a better overview of what part of the process your order is at, including delivery statuses right up to when it’s delivered.

                    #boostudio #parcel #logistics #warehousing #pickandpack #orderfufillment #fufillment #sydney #australia
                    </span></span>
              </p>
            </a>
          </div>
        </slide>
      </carousel>
    </div>
<!--END OF THIS SECTION -->
    <!-- section 5 -->
    <div id="section5">
      <b-row>
        <b-col lg="8" sm="12" class="my-auto">
          <div class="h2" style="line-height: 57px;font-weight: 600;color: #666666">
            We are all about building
            Strong <span class="font-weight-bold" style="color: #cf551c">&</span> Growing Partnerships
          </div>
          <button class="btn-section5">Contact Us</button>
        </b-col>
        <b-col lg="4" sm="12" class="section5-right" style="width: 100%;height: auto">
          <img width="100%" height="100%" src="../assets/img/cartoonimg.png" class="section5-right-image" alt="">
        </b-col>
      </b-row>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Main"
  }
</script>

<style scoped>
  #section1 {
    margin-top: 70px;
  }

  #section1 img {
    width: 100%;
    object-fit: cover;
    z-index: -1;
    height: 500px;
    transform: scale(1.4);
    animation: scaleImage 3s ease-out forwards;
  }

  #section1 h1 {
    display: flex;
    position: absolute;
    justify-content: center;
    align-items: center;
    font-family: 'Roboto', Arial, sans-serif;
    font-size: calc(10px + 8vw);
    font-weight: 700;
    line-height: 1.2;
    letter-spacing: 0.05em;
    white-space: nowrap;
    color: #cf551c;
    background-color: #0d0d0d;
    mix-blend-mode: multiply;
    opacity: 0;
    top: 0;
    animation: fadeInText 3s 2s ease-out forwards;
    width: 100%;
    z-index: 9;
  }

  @keyframes scaleImage {
    100% {
      transform: scale(1);
    }
  }

  @keyframes fadeInText {
    100% {
      opacity: 1;
    }
  }

  #section2, #section4 {
    margin-top: 80px;
  }

  .title-section2 {
    color: #8c8c8c;
    font-size: 2.5rem;
    font-weight: 600;
    text-align: center;
  }

  .title-section2 span {
    border-bottom: 8px solid #cf551c;
    padding-bottom: 10px;
  }
  @media only screen and (max-width: 800px) {
    .title-section2 {
      font-size: 1.5rem;
      font-weight: 400;

    }
  }


  .para-section2 {
    color: #8c8c8c;
    font-weight: 500;
    font-size: 1.75rem;
    text-align: center;
    margin: 50px 0 80px;
  }

  .design-box-section3 {
    background-color: #e6e6e6;
    padding: 100px 120px 60px 200px;
    border-right: 2px solid #cf551c;}

  .h2{color:#cf551c;}

  .installation-box-section3 {
    background-color: #e6e6e6;
    padding: 100px 120px 60px 200px;

  }

  .btn1-section3 {
    padding: 7px 20px;
    background-color: transparent;
    border: 1px solid #cf551c;
    color: #cf551c;
    position: relative;
    top: 40px;
    transition: background-color 500ms;
    border-radius: 5px;
  }

  .btn1-section3:hover {
    background-color: #cf551c;
    color: #ffffff;
  }

  .btn2-section3 {
    padding: 7px 20px;
    background-color: transparent;
    border: 1px solid #cf551c;
    color: #cf551c;
    position: relative;
    top: 20px;
    transition: background-color 500ms;
    border-radius: 5px;
  }

  .btn2-section3:hover {
    background-color: #cf551c;
    color: #ffffff;
  }
  /* section 3 with images background */
  .left-box {background-image: url("../assets/img/gray-bg.png");
    background-attachment: fixed;
    background-repeat: no-repeat;
    width:100%;
    height: auto;
    background-size: cover;
  padding-top:150px;
  padding-bottom: 150px;}
  .left-box h1{text-align: center;
  margin-top:1cm;
    margin-left: auto;
    margin-right: auto;}
  .left-box h2{text-align: center;
  padding-top:20px;}
  .left-box a{text-align: center;
    display: block;
   margin-left: auto;
    margin-right: auto;
    transform: translate(0, -50%);
    color:#cf551c;
    font-size: 25px;
    font-weight: bold;}
.section3-image{background-image: url("../assets/img/computer-store.png");
  background-attachment: fixed;
  background-repeat: no-repeat;
  width:100%;
  height:auto;
  background-size: cover;}
/* second image background */
  .hero-bkg-animated {
    background-image:url("../assets/img/cafe2.png");
    filter: brightness(80%);
    width: 100%;
    height: 600px;
    margin: 0;
    text-align: center;
    padding-top: 120px;
    box-sizing: border-box;
    -webkit-animation: slide 20s linear infinite;
    color: #ffffff;
  }
  .hero-bkg-animated a{color: #ffffff;
  }

  .hero-bkg-animated-text {
    font-family: sans-serif;
    font-weight: bold;
    margin-bottom: 20px;
    color:#ffffff;}
  @-webkit-keyframes slide {
    from { background-position: 0 0; }
    to { background-position: -400px 0; }
  }

  /* END OF SECTION */
  /* orange background section-orange-bg */
  #section-orange-bg{background-color: #cf551c;
    padding: 100px 120px 60px 200px;
    border-right: 2px solid #ffffff;}
  .orange-bg-h2{color:#ffffff;
  font-size:30px;
  font-weight: bold;}
  .orange-bg-p{color: #f2f2f2;
  padding-top:20px;
  font-size:20px;}

  .btn1-section-orange-bg {
    padding: 7px 20px;
    background-color: transparent;
    border: 1px solid #f2f2f2;
    color: #f2f2f2;
    transition: background-color 500ms;
    border-radius: 5px;
    margin-top:50px;
  }

  .btn1-section-orange-bg:hover {
    background-color: #f2f2f2;
    color: #cf551c;
  }

  .btn2-section-orange-bg {
    padding: 7px 20px;
    background-color: transparent;
    border: 1px solid #f2f2f2;
    color: #f2f2f2;
    position: relative;
    margin-top: 20px;
    transition: background-color 500ms;
    border-radius: 5px;
  }

  .btn2-section-orange-bg:hover {
    background-color: #f2f2f2;
    color: #cf551c;
  }

  /* END OF THIS */
  #hr2 {
    border-top: 8px solid #cf551c;
    width: 20%;
    margin-left: auto;
    margin-right: auto;
  }
  /* Section 4 and carousel images */

  .imagelist a {position: relative;display: inline-block;}
  .imagelist a p{display: none;}
  .imagelist a:hover p{position: absolute;width: 100%;height: 100%;background: #000;opacity: 0.8;top: 0;left: 0;margin: 0;display: block;}
  .imagelist a p span{display: inline-table;width: 100%;height: 100%;text-align: center;color:#fff;}
  .imagelist a p span span{display: table-cell;vertical-align: middle;}
/*END OF THIS SECTION */
  #section5 {
    margin-top: 100px;
    background-color: #e6e6e6;
    padding: 70px 150px;
    font-weight: 600;
  }

  .section5-right{background-image: url("../assets/img/images1.png");
  background-repeat: no-repeat;
  width:100%;
  height: 100%;
  background-size: cover;}
  .btn-section5 {
    padding: 8px 0;
    width: 200px;
    background-color: #cf551c;
    border: 2px solid black;
    color: black;
    font-size: 18px;
    margin-top: 12px;
    transition: background-color 500ms;
    border-radius: 5px;
  }
  .btn-section5:hover {
    background-color: #f2f2f2;
    color: #cf551c;
  }
  @media only screen and (max-width: 900px) {
    .section5-right{

      top: 1cm;
    }
  }


</style>
