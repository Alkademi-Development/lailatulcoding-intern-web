<template>
  
  <div class="layout-lc">
    <header class="header-lc">
      <img src="../gambar/logo.png" style="height: 32px; width: 183px;" />

      <nav id="nav">
        <!-- <input type="checkbox" id="check">
        <label for="check">
          <i class="fas fa-bars" id="btn"></i>
          <i class="fas fa-times" id="cancel"></i>
        </label> -->

        <label for="check">
          <i class="fas fa-bars" id="btn"></i>
          <i class="fas fa-times" id="cancel"></i>
        </label>

        <nav>
          <ul>
          <li> <a class="nav__link" href="#" >Beranda</a> </li>
          <li> <a class="nav__link" href="#lailatulcoding">Lailatul Coding</a> </li>
          <li> <a class="nav__link" href="#faq">Faq</a> </li>
        </ul>
        </nav>
       

        <!-- <g-link class="nav__link" to="/faq/">Faq</g-link> -->
        <!-- <g-link class="nav__link" to="/berita/">Berita</g-link>
        <g-link class="nav__link" to="/berita2/">Berita2</g-link>
        <g-link class="nav__link" to="/berita3/">Berita3</g-link>
        <g-link class="nav__link" to="/halaman/">Halaman</g-link>
        <g-link class="nav__link" to="/navbar/">Navbar</g-link> -->

      </nav>
      
      <div class="menu-toggle">
            <i class="fa fa-bars"></i>
      </div>

    </header>
    <slot/>
  </div>
</template>
<script >

// import Navbar from '../components/Navbar.vue';
export default {
  components : {
  
  }
}
</script>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style>

body {
  font-family: 'Nunito Sans', sans-serif;
  margin:0;
  padding:0;
  line-height: 1.5;
  text-decoration: none;
}


.header-lc {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 22px 0;
  background: white;
  position : sticky;
  top: 0;
  margin-left: 105px;
  margin-right:105px;
}

.nav__link {
  list-style-type: none;
  font-size:600 15px / 26px "Nunito Sans", sans-serif;
  margin: 0;
  padding: 0;
  overflow: hidden;
  float: left;
  color: #767dac;
  font-weight: bold;
  text-align: center;
  padding: 0px 16px 0px 16px;
  text-decoration: none;
}

.nav_link a:hover,
.nav_link a.active {
    text-decoration: underline;
    background-color: #aaaaaa;
}


nav{
  height: 80px;
  background: #ffff;
}

nav img{
  width: 150px;
  position : absolute;
  top: 17px;
  left: 12%;
}

nav ul{
  float: right;
  margin-right: 25px;
}

nav ul li{
  display: inline-block;
  line-height: 80px;
  margin: 0 15px;
}

nav ul li a{
  position: relative;
  color: white;
  padding: 5px 0;
  font-size: 18px;
  text-transform: uppercase;
}

nav ul li a:before{
  position: absolute;
  content: '';
  left: 0;
  bottom: 0;
  height: 100%;
  background: white;
  transform: scale(0);
  transform-origin: right;
  transition: transform .4s linear;
}

nav ul li a:hover :before{
  transform: scaleX(1);
  transform-origin: left;
}

.menu-toggle {
    color: rgb(94, 94, 94);
    float: right;
    line-height: 50px;
    font-size: 24px;
    cursor: pointer;
    display: none;
}

@media (max-width: 650px) {
  .header-lc {
        padding: 0 20px;
    }

  .menu-toggle {
      display: block;
  }

  .nav_link {
    position: absolute;
    width: 100%;
    height: calc(100vh - 50px);
    background: #333;
    top: 50px;
    left: -100%;
    transition: 0.5s all;
}
}

label #btn,
label #cancel{
  color : white;
  font-size: 30px;
  float: right;
  line-height: 80px;
  margin-right: 40px;
  cursor: pointer;
}

</style>
