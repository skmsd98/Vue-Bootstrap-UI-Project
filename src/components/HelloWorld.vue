<template>
  <div>
    <b-navbar toggleable="lg" type="light" variant="light">
      <b-navbar-brand href="#">
        <img src="../assets/icon.png" id="brand-icon" />
      </b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#">Home</b-nav-item>
          <b-nav-item href="#">Shop</b-nav-item>
          <b-nav-item href="#">Blog</b-nav-item>
          <b-nav-item href="#">About</b-nav-item>
          <b-nav-item href="#">Contact</b-nav-item>
          <b-nav-item href="#">
            <img src="../assets/10.png" class="nav-icons" />
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

      <b-row class="text-center myContainers" align-h="around">
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

      <b-row class="text-center" align-h="around">
        <b-col lg="2">
          <div class="caretIcons">
            <i class="fas fa-caret-left"></i>
            <i class="fas fa-caret-right"></i>
          </div>
        </b-col>
      </b-row>
    </b-container>

    <div class="bgImage text-center">
      <b-container>
        <b-row>
          <b-col class="featuredHeading">
            <h2>Most Popular</h2>
            <br />
            <h3>Featured Products</h3>
          </b-col>
        </b-row>
        <b-row class="featuredProducts justify-content-lg-center">
          <b-col lg="2" md="3" sm="4" cols="6">
              <div class="imgWhiteBackground">
                <b-img :src="require(`@/assets/12.png`)" fluid alt="img" class="featuredImg"></b-img>
              </div>
              <p>Dog Food</p>
              <b-img :src="require(`@/assets/price-tag.png`)" fluid alt="img"></b-img>
              <br />
              <p>$305</p>
          </b-col>
          <b-col lg="2" md="3" sm="4" cols="6">
              <div class="imgWhiteBackground">
                <b-img :src="require(`@/assets/13.png`)" fluid alt="img" class="featuredImg"></b-img>
              </div>
              <p>Dog Breath Drops</p>
              <b-img :src="require(`@/assets/price-tag.png`)" fluid alt="img"></b-img>
              <br />
              <p>$305</p>
          </b-col>
          <b-col lg="2" md="3" sm="4" cols="6">
              <div class="imgWhiteBackground">
                <b-img :src="require(`@/assets/14.png`)" fluid alt="img" class="featuredImg"></b-img>
              </div>
              <p>Dog T-Shirt</p>
              <b-img :src="require(`@/assets/price-tag.png`)" fluid alt="img"></b-img>
              <br />
              <p>$305</p>
          </b-col>
          <b-col lg="2" md="3" sm="4" cols="6">
              <div class="imgWhiteBackground">
                <b-img :src="require(`@/assets/15.png`)" fluid alt="img" class="featuredImg"></b-img>
              </div>
              <p>Dog Collar</p>
              <b-img :src="require(`@/assets/price-tag.png`)" fluid alt="img"></b-img>
              <br />
              <p>$305</p>
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
.navbar {
  padding: 0rem 1rem;
  padding-bottom: 10px;
}
.navbar-collapse {
  padding-right: 90px;
  margin-top: -10px;
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
  height: 125px;
  width: 125px;
}

.categoryIcons img {
  height: 50px;
}

.fa-caret-left,
.fa-caret-right {
  font-size: 4em;
  color: #664321;
  margin-top: 50px;
}

.fa-caret-left {
  color: #b3a190;
  border-right: 3px solid #664321;
  padding-right: 15px;
  margin-right: 17px;
}

.bgImage {
  margin-top: 50px;
  background-image: url("../assets/bg-img.jpg");
  background-color: #cccccc; /* Used if the image is unavailable */
  height: 50%; /* You must set a specified height */
  width: 100%;
  background-position: center; /* Center the image */
  background-repeat: no-repeat; /* Do not repeat the image */
  background-size: cover; /* Resize the background image to cover the entire container */
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
  width: 110%;
  border-radius: 20px;
}

.featuredProducts {
  margin-top: 30px;
}

.featuredProducts p {  
  margin-top: 20px;
}


</style>
