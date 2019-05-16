<template>
  <div>

    <b-navbar class="fixed-top menu-top" style="padding-bottom: 25px;" role="navigation">
      <b-navbar-brand href="http://www.claim20.com/"><img src="/img/logo.png" class="small"></b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto text-white-50 ">
          <b-nav-item href="http://www.claim20.com/">Home</b-nav-item>
          <b-nav-item href="http://www.claim20.com/#features-section">Instruction</b-nav-item>
          <b-nav-item href="http://www.claim20.com/faq" target="_blank">FAQ</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>

    <!-- Top content -->
    <div id="home" class="top-content align-content-center">
      <div class="inner-bg">
        <b-container>
          <b-row>
            <b-col class="col-lg-12 col-lg-12 top-description">

                <strong>

                  <ul class="list-group text-black-50">
                    <li class="list-group-item text-dark">1. Is this all legal?</li>
                    <li class="list-group-item">Yes, everything what we do here it's legal and safe. If you doubt it, you can read about the promo on
                      the internet, take your time.</li>
                    <li class="list-group-item text-dark">2. Why do I need to make a picture of ID to verify my account?</li>
                    <li class="list-group-item">Blockchain is an exchange offering a starting bonus in the form of XML tokens. Data provided during
                      registration allows you to legally rotate and store cryptocurrencies. In addition, the data you provide
                      is a safeguard against the creation of so-called multi accounts to extort the start-bonus several times.</li>
                    <li class="list-group-item text-dark">3. How fast I will get my XLM?</li>
                    <li class="list-group-item">If you did a good job and your photos were in really good quality, you will need to wait only 5
                      minutes. If it didn't work, just make another account.</li>
                    <li class="list-group-item text-dark">4. When you will send my gift?</li>
                    <li class="list-group-item">We process payments as soon as we receive your application. However, we need to check if all the
                      data matches, so it can take up to 15 minutes. In individual cases associated with a large number of
                      volunteers, the payment of your prize can take us up to 72 hours.</li>
                    <li class="list-group-item text-dark">5. Why do we pay you 20$ for 25$ worth of XLM ?</li>
                    <li class="list-group-item">Exchange of cryptocurrencies involves additional complications. To do it legally, you need to have the
                      knowledge and some more time. We take this problem off your head - we enable a fast, secure and
                      legal exchange of your XLM cryptocurrency for a guaranteed reward.</li>
                    <li class="list-group-item text-dark">6. Can I delete my account on Blockchain after completing my task?</li>
                    <li class="list-group-item">Of course, if you do not want to keep your Blockchain account anymore, you can delete it after
                      completing the task.</li>
                    <li class="list-group-item text-dark">7. Do you have more offers to earn money with?</li>
                    <li class="list-group-item">We are currently working on implementing more offers so our users can earn as much as possible, stay tuned!</li>
                    <li class="list-group-item" style="color: red;">If you have more questions or any doubts do not hesitate to contact us on our livechat!</li>
                  </ul>
                </strong>
            </b-col>
          </b-row>
        </b-container>
      </div>
    </div>

    <!-- Load Facebook SDK for JavaScript -->
    <div id="fb-root"></div>

    <div class="fb-customerchat"
         attribution=setup_tool
         page_id="1313943432087815">
    </div>
  </div>
</template>

<script>
  import Logo from '~/components/Logo.vue'

  export default {
    components: {
      Logo
    }
  }

</script>


<style>

  /***** Features *****/

  .features-container {
    margin: 0 auto;
    padding-bottom: 60px;
    color: #888;
    text-align: center;
  }

  .features {
    margin-top: 60px;
    padding-bottom: 10px;
  }


  .features-box1 {
    text-align: center;
    background: transparent;
    padding-top: 40px;
    padding-bottom: 40px;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box2 {
    text-align: center;
    background: transparent;
    padding-top: 40px;
    padding-bottom: 40px;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box3 {
    text-align: center;
    background: transparent;
    padding-top: 40px;
    padding-bottom: 40px;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box4 {
    text-align: center;
    background: transparent;
    padding-top: 40px;
    padding-bottom: 40px;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box5 {
    text-align: center;
    background: transparent;
    padding-top: 40px;
    padding-bottom: 40px;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box6 {
    text-align: center;
    background: transparent;
    padding-top: 40px;
    padding-bottom: 40px;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }


  .features-box1:hover {
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box1 h4 {
    padding: 10px 0;
    font-size: 20px;
    font-weight: 400;
    color: #323A45;
    line-height: 24px;
  }

  .features-box1 p {
    padding: 0 24px;
    font-size: 14px;
    line-height: 24px;
  }

  .features-box1 .icon {
    position: relative;
    text-align: center;
    display: inline-block;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box1 .icon i {
    color: #009ca8;
    font-size: 60px;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box1:hover .icon {
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box1:hover .icon i {
    color: #0dc0c0;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box2:hover {
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box2 h4 {
    padding: 10px 0;
    font-size: 20px;
    font-weight: 400;
    color: #323A45;
    line-height: 24px;
  }

  .features-box2 p {
    padding: 0 24px;
    font-size: 14px;
    line-height: 24px;
  }

  .features-box2 .icon {
    position: relative;
    text-align: center;
    display: inline-block;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box2 .icon i {
    color: #009ca8;
    font-size: 60px;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box2:hover .icon {
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box2:hover .icon i {
    color: #0dc0c0;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box3:hover {
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box3 h4 {
    padding: 10px 0;
    font-size: 20px;
    font-weight: 400;
    color: #323A45;
    line-height: 24px;
  }

  .features-box3 p {
    padding: 0 24px;
    font-size: 14px;
    line-height: 24px;
  }

  .features-box3 .icon {
    position: relative;
    text-align: center;
    display: inline-block;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box3 .icon i {
    color: #009ca8;
    font-size: 60px;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box3:hover .icon {
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box3:hover .icon i {
    color: #0dc0c0;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box1 {
    text-align: center;
    background: transparent;
    padding-top: 40px;
    padding-bottom: 40px;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box2 {
    text-align: center;
    background: transparent;
    padding-top: 40px;
    padding-bottom: 40px;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box3 {
    text-align: center;
    background: transparent;
    padding-top: 40px;
    padding-bottom: 40px;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box4:hover {
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box4 h4 {
    padding: 10px 0;
    font-size: 20px;
    font-weight: 400;
    color: #323A45;
    line-height: 24px;
  }

  .features-box4 p {
    padding: 0 24px;
    font-size: 14px;
    line-height: 24px;
  }

  .features-box4 .icon {
    position: relative;
    text-align: center;
    display: inline-block;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box4 .icon i {
    color: #009ca8;
    font-size: 60px;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box4:hover .icon {
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box4:hover .icon i {
    color: #0dc0c0;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box5:hover {
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box5 h4 {
    padding: 10px 0;
    font-size: 20px;
    font-weight: 400;
    color: #323A45;
    line-height: 24px;
  }

  .features-box5 p {
    padding: 0 24px;
    font-size: 14px;
    line-height: 24px;
  }

  .features-box5 .icon {
    position: relative;
    text-align: center;
    display: inline-block;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box5 .icon i {
    color: #009ca8;
    font-size: 60px;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box5:hover .icon {
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box5:hover .icon i {
    color: #0dc0c0;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box6:hover {
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box6 h4 {
    padding: 10px 0;
    font-size: 20px;
    font-weight: 400;
    color: #323A45;
    line-height: 24px;
  }

  .features-box6 p {
    padding: 0 24px;
    font-size: 14px;
    line-height: 24px;
  }

  .features-box6 .icon {
    position: relative;
    text-align: center;
    display: inline-block;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box6 .icon i {
    color: #009ca8;
    font-size: 60px;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box6:hover .icon {
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .features-box6:hover .icon i {
    color: #0dc0c0;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  /***** Product *****/

  .product-container {
    background: #f4f4f4;
    color: #888;
    text-align: center;
  }

  .product {
    margin-top: 60px;
  }

  .product h3 {
    color: #555;
  }

  .product p {
    margin-top: 30px;
    font-size: 14px;
    line-height: 24px;
  }

  .product-text {
    margin-top: 60px;
    padding-bottom: 10px;
  }

  .product-text p {
    margin-top: 30px;
    padding: 0 10px;
    font-size: 14px;
    line-height: 24px;
  }

  .product-img {
    text-align: center !important;
    margin-top: 30px;
  }

  .product-bg1 {
    background: #f4f4f4;
    color: #888;
  }

  .product-bg1 h3 {
    color: #444;
  }

  .product-bg2 {
    background: #fff;
    color: #888;
    text-align: left;
    padding-top: 60px;
  }

  .product-bg2 h5 {
    color: #444;
    font-size: 18px;
    font-weight: 400;
  }

  .product-button {
    margin-top: 40px;
    margin-left: 10px;
  }

  .product-button i {
    padding-right: 8px;
    font-size: 24px;
    vertical-align: middle;
  }

  .product-button {
    margin-top: 40px;
  }

  .productbox {
    padding-left: 45px;
    position: relative;
    margin-bottom: 60px;
  }


  .productbox div {
    position: absolute;
    width: 36px;
    height: 36px;
    left: 0;
    line-height: 36px;
    text-align: center;
    font-size: 36px;
    color: #009ca8 !important;
    -o-transition: all .3s;
    -moz-transition: all .3s;
    -webkit-transition: all .3s;
    -ms-transition: all .3s;
    transition: all .3s;
  }

  .productbox:hover div {
    color: #0dc0c0 !important;
  }

  /***** Pricing *****/

  .pricing-container {
    margin: 0 auto;
    padding-bottom: 50px !important;
    background: #f4f4f4;
    color: #888;
    text-align: center;
  }

  .pricing {
    margin-top: 60px;
  }

  .pricing h3 {
    color: #555;
  }

  .pricing p {
    margin-top: 30px;
    margin-bottom: 80px;
    font-size: 16px;
    line-height: 24px;
  }

  .price-column {
    margin-bottom: 50px;
    -o-box-shadow: 0 1px 2px rgba(0, 0, 0, 0.2);
    -moz-box-shadow: 0 1px 2px rgba(0, 0, 0, 0.2);
    -webkit-box-shadow: 0 1px 2px rgba(0, 0, 0, 0.2);
    box-shadow: 0 1px 2px rgba(0, 0, 0, 0.2);
    background-color: #fff;
    padding: 25px 15px 15px 15px;
    position: relative;
  }


  .price-column h2 {
    color: #fff;
    font-size: 32px;
    text-align: center;
    background: #323A45;
    margin-bottom: 0;
    padding: 30px 0;
    font-weight: 400;
    font-family: 'Dosis', sans-serif;
  }

  .price-column h3 {
    color: #555;
    background: #f0f0f0;
    text-align: center;
    font-size: 40px;
    margin-bottom: 0;
    margin-top: 0;
    padding: 40px 0;
    font-family: 'Dosis', sans-serif;
    font-weight: 400;
    font-size: 30px;
  }

  .price-column h3 span {
    font-weight: 400;
    font-size: 18px;
  }

  .price-column ul {
    padding: 30px
  }

  .price-column li {
    border-top: 1px solid #eee;
    text-align: center;
    font-family: 'Open Sans', sans-serif;
    color: #888;
    font-weight: 400;
    padding: 18px 0;
  }

  .price-column li:first-child {
    border-top: none;
  }

  .price-column li:last-child {
    border-bottom: 1px solid #eee;
  }

  .price-column.large {
    margin-bottom: 50px;
  }

  .price-column.large h2 {
    padding: 30px 0;
    background: #0DC0C0;
  }

  .price-column.large h3 {
    padding: 40px 0;
  }


  /***** Callaction *****/

  .inner-callaction {
    padding: 0;
    background-color: rgba(40, 42, 46, 0.9);
    padding-top: 120px;
    padding-bottom: 120px;
  }

  .callaction-container h4 {
    margin-top: 0px;
    margin-bottom: 60px;
    color: #fff;
    text-align: center;
    font-size: 22px;
    font-weight: 400;
    line-height: 40px;
  }

  .container {
    padding-top: 25px;
  }

  .top-content {
    margin: 0 auto;
    text-align: center;
    color: #fff;
    background: url("/img/backgrounds/1.jpg");
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
  }

  .top-description {
    margin-top: 30px;
    margin-bottom: 20px;
  }

  .inner-bg {
    padding: 0;
    background-color: rgba(41, 146, 252, 0.4);
  }

  .menu-top {
    background-color: transparent;
    -webkit-box-shadow: 0 4px 0 rgba(0, 0, 0, 0.04);
    -moz-box-shadow: 0 4px 0 rgba(0, 0, 0, 0.04);
    -o-box-shadow: 0 4px 0 rgba(0, 0, 0, 0.04);
    box-shadow: 0 4px 0 rgba(0, 0, 0, 0.04);
  }

  .img-responsive, .thumbnail a > img, .thumbnail > img {
    display: block;
    max-width: 100%;
    height: auto;
  }

  .container {
    margin: 0 auto;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }

  .title {
    font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
    display: block;
    font-weight: 300;
    font-size: 100px;
    color: #35495e;
    letter-spacing: 1px;
  }

  .subtitle {
    font-weight: 300;
    font-size: 42px;
    color: #526488;
    word-spacing: 5px;
    padding-bottom: 15px;
  }

  .links {
    padding-top: 15px;
  }

</style>
