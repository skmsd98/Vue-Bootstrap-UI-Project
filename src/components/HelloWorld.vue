<template>
  <div>
    <b-navbar toggleable="lg" type="light" variant="light">
      <b-navbar-brand href="#">
        <img src="../assets/icon.png" id="brand-icon" />
      </b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#">Home</b-nav-item>
          <b-nav-item href="#">Shop</b-nav-item>
          <b-nav-item href="#">Blog</b-nav-item>
          <b-nav-item href="#">About</b-nav-item>
          <b-nav-item href="#">Contact</b-nav-item>
          <b-nav-item href="#">
            <b-img :src="require(`@/assets/10.png`)" fluid alt="img"></b-img>
          </b-nav-item>
          <b-nav-item href="#">
            <img src="../assets/8.png" class="nav-icons" />
          </b-nav-item>
          <b-nav-item href="#">
            <img src="../assets/9.png" class="nav-icons" />
          </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>

    <b-img :src="require(`@/assets/header.png`)" fluid alt="img"></b-img>

    <b-container fluid class="myContainers">
      <b-row>
        <b-col class="text-center categoryHeading">
          <h2>shop by</h2>
          <br />
          <h3>Category</h3>
        </b-col>
      </b-row>

      <b-row class="text-center myContainers justify-content-center">
        <b-col lg="1" md="2" sm="4" cols="6">
          <div class="categoryIcons">
            <b-img :src="require(`@/assets/3.png`)" fluid alt="img"></b-img>
            <p>Pet</p>
          </div>
        </b-col>
        <b-col lg="1" md="2" sm="4" cols="6">
          <div class="categoryIcons">
            <b-img :src="require(`@/assets/6.png`)" fluid alt="img"></b-img>
            <p>Food</p>
          </div>
        </b-col>
        <b-col lg="1" md="2" sm="4" cols="6">
          <div class="categoryIcons">
            <b-img :src="require(`@/assets/2.png`)" fluid alt="img"></b-img>
            <p>Collars</p>
          </div>
        </b-col>
        <b-col lg="1" md="2" sm="4" cols="6">
          <div class="categoryIcons">
            <b-img :src="require(`@/assets/4.png`)" fluid alt="img"></b-img>
            <p>Bowl</p>
          </div>
        </b-col>
        <b-col lg="1" md="2" sm="4" cols="6">
          <div class="categoryIcons">
            <b-img :src="require(`@/assets/5.png`)" fluid alt="img"></b-img>
            <p>Toys</p>
          </div>
        </b-col>
        <b-col lg="1" md="2" sm="4" cols="6">
          <div class="categoryIcons">
            <b-img :src="require(`@/assets/6.png`)" fluid alt="img"></b-img>
            <p>Grooming</p>
          </div>
        </b-col>
        <b-col lg="1" md="2" sm="4" cols="6">
          <div class="categoryIcons">
            <b-img :src="require(`@/assets/7.png`)" fluid alt="img"></b-img>
            <p>Bed</p>
          </div>
        </b-col>
      </b-row>

      <b-row class="text-center justify-content-center">
        <b-col lg="2">
          <div class="caretBrown">
            <i class="fas fa-caret-left caret-left-brown"></i>
            <i class="fas fa-caret-right caret-right-brown"></i>
          </div>
        </b-col>
      </b-row>
    </b-container>

    <div class="bgImage text-center">
      <b-container fluid>
        <b-row>
          <b-col class="featuredHeading">
            <h2>Most Popular</h2>
            <br />
            <h3>Featured Products</h3>
          </b-col>
        </b-row>
        <b-row class="featuredProducts justify-content-lg-center">
          <b-col lg="2" md="3" sm="4" cols="12">
            <div class="imgWhiteBackground">
              <b-img :src="require(`@/assets/12.png`)" fluid alt="img" class="featuredImg"></b-img>
            </div>
            <p>Dog Food</p>
            <b-img :src="require(`@/assets/price-tag.png`)" fluid alt="img"></b-img>
            <br />
            <p>$305</p>
          </b-col>
          <b-col lg="2" md="3" sm="4" cols="12">
            <div class="imgWhiteBackground">
              <b-img :src="require(`@/assets/13.png`)" fluid alt="img" class="featuredImg"></b-img>
            </div>
            <p>Dog Drops</p>
            <b-img :src="require(`@/assets/price-tag.png`)" fluid alt="img"></b-img>
            <br />
            <p>$305</p>
          </b-col>
          <b-col lg="2" md="3" sm="4" cols="12">
            <div class="imgWhiteBackground">
              <b-img :src="require(`@/assets/14.png`)" fluid alt="img" class="featuredImg"></b-img>
            </div>
            <p>Dog T-Shirt</p>
            <b-img :src="require(`@/assets/price-tag.png`)" fluid alt="img"></b-img>
            <br />
            <p>$305</p>
          </b-col>
          <b-col lg="2" md="3" sm="4" cols="12">
            <div class="imgWhiteBackground">
              <b-img :src="require(`@/assets/15.png`)" fluid alt="img" class="featuredImg"></b-img>
            </div>
            <p>Dog Collar</p>
            <b-img :src="require(`@/assets/price-tag.png`)" fluid alt="img"></b-img>
            <br />
            <p>$305</p>
          </b-col>
        </b-row>
        <b-row class="text-center justify-content-center">
          <b-col lg="2">
            <div class="caretWhite">
              <i class="fas fa-caret-left caret-left-white"></i>
              <i class="fas fa-caret-right caret-right-white"></i>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>

    <div class="section-4 text-center">
      <b-container fluid>
        <b-row>
          <b-col lg="8" md="6" sm="12" cols="12">
            <b-img :src="require(`@/assets/16.png`)" fluid alt="img" class="sec-4-largeImage-1"></b-img>
          </b-col>
          <b-col lg="4" md="6" sm="12" cols="12">
            <b-img :src="require(`@/assets/17.png`)" fluid alt="img" class="sec-4-largeImage-2"></b-img>
          </b-col>
        </b-row>
        <b-row class="justify-content-center">
          <b-col lg="3" md="6" sm="12" cols="12">
            <div class="dogsRounded">
              <div class="dogBackground">
                <h4>Personalize Collar</h4>
              <b-img :src="require(`@/assets/dog3.png`)" fluid></b-img>
              <div class="circleBorder"></div>
            </div>
            </div>
          </b-col>
          <b-col lg="2"></b-col>
          <b-col lg="3" md="6" sm="12" cols="12">
            <div class="dogsRounded">
              <div class="dogBackground">
              <h4>Personalize Bed</h4>
              <b-img :src="require(`@/assets/dog4.png`)" fluid></b-img>
              <div class="circleBorder"></div>
            </div>
            </div>
          </b-col>
        </b-row>
      </b-container>

      <div class="section-5 text-center">
        <b-container fluid>
          <div class="sponsoredProducts">
            <b-row>
              <b-col class="categoryHeading brandsLoved">
                <h2>Brands</h2>
                <br />
                <h3>You Love</h3>
              </b-col>
            </b-row>
            <b-row class="justify-content-center" align-v="center">
              <b-col lg="2" md="6" sm="6" cols="12" >
                <div>
                  <b-img :src="require(`@/assets/18.png`)" fluid alt="img" class="sponsored"></b-img>
                </div>
              </b-col>
              <b-col lg="2" md="6" sm="6" cols="12">
                <div>
                  <b-img :src="require(`@/assets/19.png`)" fluid alt="img" class="sponsored"></b-img>
                </div>
              </b-col>
              <b-col lg="2" md="6" sm="6" cols="12">
                <div>
                  <b-img :src="require(`@/assets/20.png`)" fluid alt="img" class="sponsored"></b-img>
                </div>
              </b-col>
              <b-col lg="2" md="6" sm="6" cols="12">
                <div>
                  <b-img :src="require(`@/assets/21.png`)" fluid alt="img" class="sponsored"></b-img>
                </div>
              </b-col>
              <b-col lg="2" md="6" sm="6" cols="12">
                <div>
                  <b-img :src="require(`@/assets/22.png`)" fluid alt="img" class="sponsored"></b-img>
                </div>
              </b-col>
              <b-col lg="2" md="6" sm="6" cols="12">
                <div>
                  <b-img :src="require(`@/assets/23.png`)" fluid alt="img" class="sponsored"></b-img>
                </div>
              </b-col>
              <b-col lg="2" md="6" sm="6" cols="12">
                <div>
                  <b-img :src="require(`@/assets/24.png`)" fluid alt="img" class="sponsored"></b-img>
                </div>
              </b-col>
              <b-col lg="2" md="6" sm="6" cols="12">
                <div>
                  <b-img :src="require(`@/assets/25.png`)" fluid alt="img" class="sponsored"></b-img>
                </div>
              </b-col>
              <b-col lg="2" md="6" sm="6" cols="12">
                <div>
                  <b-img :src="require(`@/assets/26.png`)" fluid alt="img" class="sponsored"></b-img>
                </div>
              </b-col>
              <b-col lg="2" md="6" sm="6" cols="12">
                <div>
                  <b-img :src="require(`@/assets/27.png`)" fluid alt="img" class="sponsored"></b-img>
                </div>
              </b-col>
            </b-row>
          </div>
        </b-container>
      </div>
    </div>

    <div class="section-6 text-center">
      <b-container fluid>
        <b-row>
          <b-col class="categoryHeading">
            <h2>latest News</h2>
            <br />
            <h3>From Our Blogs</h3>
          </b-col>
        </b-row>
          <b-row class="justify-content-center dogCares" >
            <b-col lg="4" md="4" sm="6" xs="6">
              <b-img :src="require(`@/assets/image1.jpg`)" fluid alt="img"></b-img>
              <h5>Train Your Dogs</h5>
              <p>Is your dog easily distracted? Does he spend your entire week lunging at ...</p>
              <a href="#"><h6>Full Article ></h6></a>
            </b-col>
            <b-col lg="4" md="4" sm="6" xs="6">
              <b-img :src="require(`@/assets/image2.jpg`)" fluid alt="img"></b-img>
              <h5>Care Of Your Dogs</h5>
              <p>Is your dog easily distracted? Does he spend your entire week lunging at ...</p>
              <a href="#"><h6>Full Article ></h6></a>
            </b-col>
            <b-col lg="4" md="4" sm="6" xs="6">
              <b-img :src="require(`@/assets/image3.jpg`)" fluid alt="img"></b-img>
              <h5>Electric Fence for Dogs</h5>
              <p>Is your dog easily distracted? Does he spend your entire week lunging at ...</p>
              <a href="#"><h6>Full Article ></h6></a>
            </b-col>
          </b-row>
          <b-row class="justify-content-center">
            <b-col>
              <i class="fas fa-circle"></i>
              <i class="far fa-circle"></i>
              <i class="far fa-circle"></i>
              <i class="far fa-circle"></i>
              <i class="far fa-circle"></i>
              <i class="far fa-circle"></i>
              <i class="far fa-circle"></i>
            </b-col>
          </b-row>
          <b-row class="justify-content-center">
            <b-col lg="3" md="4" sm="6" xs="12">
              <div class="servicesWrapper">
                <b-img :src="require(`@/assets/28.png`)" fluid alt="img"></b-img>
                <h4>Free Shipping</h4>
                <p>Free shipping on all orders</p>
              </div>
            </b-col>
            <b-col lg="3" md="4" sm="6" xs="12">
              <div class="servicesWrapper">
                <b-img :src="require(`@/assets/29.png`)" fluid alt="img"></b-img>
                <h4>Online Support</h4>
                <p>Online support 24 hours a day</p>
              </div>
            </b-col>
            <b-col lg="3" md="4" sm="6" xs="12">
              <div class="servicesWrapper">
                <b-img :src="require(`@/assets/30.png`)" fluid alt="img"></b-img>
                <h4>Easy Return</h4>
                <p>Back guarentee under 5 days</p>
              </div>
            </b-col>
          </b-row>
      </b-container>
    </div>

    <div class="section-7">
      <b-container fluid>
        <b-row class="justify-content-center">
          <b-col lg="3" md="4" sm="6" xs="12">
            <div class="linksWrapper">
              <b-img :src="require(`@/assets/icon.png`)" fluid alt="img"></b-img>
              <p>Bowwow.com is India's first and largest online pet store catering from 2002 to dogs ,cats ,birds, fishes and all your small companions.</p>
              <p>Get weekly dose of exciting news &amp; products</p>
              <b-form-input placeholder="Enter your Email Address"></b-form-input>
            </div>
          </b-col>
          <b-col lg="2" md="4" sm="6" xs="12">
            <div class="linksWrapper">
              <a href="#">
                <h5>Legal</h5>
              </a>
              <a href="#">
                <p>Privacy Policy</p>
              </a>
              <a href="#">
                <p>Terms &amp; Conditions</p>
              </a>
              <a href="#">
                <p>Refund &amp; Cancellation</p>
              </a>
            </div>
          </b-col>
          <b-col lg="2" md="4" sm="6" xs="12">
            <div class="linksWrapper">
              <a href="#">
                <h5>Useful Links</h5>
              </a>
              <a href="#">
                <p>Home</p>
              </a>
              <a href="#">
                <p>Shop</p>
              </a>
              <a href="#">
                <p>Blog</p>
              </a>
              <a href="#">
                <p>About</p>
              </a>
            </div>
          </b-col>
          <b-col lg="3" md="4" sm="6" xs="12">
            <div class="linksWrapper">
              <a href="#">
                <h5>Contact</h5>
              </a>
                <p>Lorem ipsum dolor sit amet, co adipisi elit, sed eiusmod tempor incididunt ut labore et dolore</p>
                <p>+91-1234567890</p>
              <a href="mailto: #">
                <p>info@bowwow.com</p>
              </a>
            </div>
          </b-col>
        </b-row>
        <b-row class="text-center justify-content-center copyRight">
          <b-col>
            <p>&copy; 2019 BowWow. All Rights Reserved</p>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>

<script>
export default {};
</script>



<style scoped>
@import url("https://fonts.googleapis.com/css?family=Josefin+Sans&display=swap");

#brand-icon {
  width: 75px;
  height: 50px;
  margin-left: 90px;
}
.nav-icons {
  height: 20px;
  width: 20px;
}
.navbar-light .navbar-nav .nav-link {
  color: #664321;
  font-family: "Josefin Sans", sans-serif;
}
a.nav-link {
  font-family: "Josefin Sans", sans-serif;
  margin-right: 15px;
}
.bg-light {
    background-color: #EFF0F4 !important;
}
.navbar {
  padding: 0rem 1rem;
  padding-bottom: 10px;
}
.navbar-collapse {
  padding-right: 90px;
}

@import url("https://fonts.googleapis.com/css?family=Pacifico&display=swap");
@import url("https://fonts.googleapis.com/css?family=Fredoka+One&display=swap");

.categoryHeading {
  color: #000000;
  font-weight: bold;
}
.categoryHeading h2 {
  font-size: 1.5em;
  font-family: "Pacifico", cursive;
}

.categoryHeading h3 {
  margin-top: -20px;
  font-size: 2em;
  font-family: "Fredoka One", cursive;
}

.myContainers {
  padding-top: 30px;
}

.categoryIcons {
  padding-top: 25px;
  border: 2px solid #fafafa;
  border-radius: 10px;
  box-shadow: 3px 3px 10px #d3d3d3;
  color: #664321;
  font-family: "Josefin Sans", sans-serif;
}

.categoryIcons p {
  margin-top: 20px;
}

.categoryIcons img {
  height: 50px;
}

.fa-caret-left,
.fa-caret-right {
  font-size: 4em;
}

.caretBrown {
  margin-top: 50px;
}

.caret-left-brown {
  color: #b3a190;
  border-right: 3px solid #664321;
}

.caret-right-brown {
  color: #664321;
}

.caret-left-white {
  color: #b3a190;
  border-right: 3px solid #ffffff;
}

.caret-right-white {
  color: #ffffff;
}

.fa-caret-left {
  padding-right: 15px;
  margin-right: 17px;
}

.bgImage {
  margin-top: 50px;
  background-image: url("../assets/bg-img.jpg");
  background-color: #cccccc;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.featuredHeading {
  color: #ffffff;
  font-weight: bold;
  margin-top: 30px;
}
.featuredHeading h2 {
  font-size: 1.5em;
  font-family: "Pacifico", cursive;
}

.featuredHeading h3 {
  margin-top: -20px;
  font-size: 2em;
  font-family: "Fredoka One", cursive;
}

.bgImage p {
  font-family: "Josefin Sans", sans-serif;
  color: #ffffff;
}

.featuredImg {
  height: 140px;
  width: 100px;
  margin-top: 30px;
}

.imgWhiteBackground {
  border: 1px solid white;
  background-color: #ffffff;
  height: 12em;
  border-radius: 20px;
}

.featuredProducts {
  margin-top: 30px;
}

.featuredProducts p {
  margin-top: 20px;
}

@media (max-width: 767px) {
  .imgWhiteBackground {
    width: 70%;
    margin: auto;
    margin-top: 25px;
  }

  .categoryIcons {
    margin-top: 20px;
  }

  .sec-4-largeImage-2 {
    margin-top: -60px;
  }

  .brandsLoved {
    margin-bottom: 50px;
  }

  .servicesWrapper {
    margin: auto
  }
}

@media (max-width: 990px) {
  .brandsLoved {
    margin-bottom: 50px;
  }
  .servicesWrapper {
    margin: auto;
  }
}

@media (min-width: 992px) {
  .dogCares {
    width: 90%;
  margin: auto;
  }
  .servicesWrapper {
    margin: auto
  }
}

.caretWhite {
  margin-top: 10px;
  margin-bottom: 20px;
}

.section-4 {
  padding-top: 50px;
}

.sec-4-largeImage-1,
.sec-4-largeImage-2 {
  height: 70%;
}

.dogBackground {
  background-image: url("../assets/bg-image.jpg");
  background-color: #cccccc;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  border-radius: 50%;
  height: 300px;
  box-shadow: 1px 2px 1px 2px #d3d3d3;
  margin-bottom: 20px;
}

.dogBackground img {
  height: 120px;
  margin-top: 20px;
}

.dogBackground h4 {
  font-family: "Fredoka One", cursive;
  padding-top: 60px;
  color: #664321;
  font-weight: bold;
}

.sponsored {
  /* width: 80%;
  height: 70%; */
  margin-bottom: 40px;
}

.section-5 {
  background-color: #f3f3f5;
  margin-top: 50px;
}

.brandsLoved {
  margin-top: 30px;
}

.dogCares {
  font-family: "Josefin Sans", sans-serif;
  text-align: left;
}

.dogCares h5 {
  font-weight: bold;
}

.dogCares h6 {
  color: #664321;
}

.dogCares img {
  margin-top: 40px;
  margin-bottom: 30px;
}

.section-6 {
  margin-top: 30px;
}

.section-6 i {
  color: #664321;
  font-size: 12px;
  margin: 35px 5px 0 5px;
}

.servicesWrapper {
  font-family: "Fredoka One", cursive;
  color: #664321;
  border: 3px solid #664321;
  border-radius: 20px;
  padding-top: 20px;
  margin-top: 50px;
  width: 90%;
}

.servicesWrapper h4 {
  margin-top: 10px;
}

.servicesWrapper p {
  color: #000000;
  font-family: "Josefin Sans", sans-serif;
}

.section-7 {
  border-top: 1px solid #664321;
  padding-top: 50px;
  margin-top: 60px;
  font-family:  sans-serif;
}

.section-7 h5 {
  color: #664321;
  font-weight: bold;
  margin-bottom: 20px;
  text-decoration: underline;
}

.section-7 p {
  color: #000000;
  margin-top: -10px;
}

.section-7 img {
  margin-bottom: 20px;
}

.copyRight p {
  margin-top: 25px;
}

.section-7 input {
  border-radius: 20px;
  background-color: #664321;
  padding: 20px;
  font-size: 0.9em;
  color: lightgray;
}

.linksWrapper {
  font-size: 0.9em;
}

/* .dogsRounded {
  height: 300px;
} */

.circleBorder {
  height: 300px;
  width: 300px;
  border: 3px solid #664321;
  border-radius: 50%;
  position: absolute;
  margin: -210px -20px;
  z-index: -1;
}

</style>
