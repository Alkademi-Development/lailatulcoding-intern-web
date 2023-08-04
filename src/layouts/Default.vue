<template>
  <div class="layout-lc">
    <header class="header-lc">
      <strong>
        <a href="#beranda"><img src="../gambar/logo.png" style="height: 32px; width: 183px;" /></a>
      </strong>
      <nav id="nav">
        
        <a class="nav__link" href="#" >Beranda</a>
        <a class="nav__link" href="#lailatulcoding">Lailatul Coding</a>
        <!-- <g-link class="nav__link" to="/faq/">Faq</g-link> -->
        <a class="nav__link" href="#faq">Faq</a>
        <!-- <g-link class="nav__link" to="/berita/">Berita</g-link>
        <g-link class="nav__link" to="/berita2/">Berita2</g-link>
        <g-link class="nav__link" to="/berita3/">Berita3</g-link>
        <g-link class="nav__link" to="/halaman/">Halaman</g-link>
        <g-link class="nav__link" to="/navbar/">Navbar</g-link> -->

      </nav>
      
    </header>
    <slot/>
  </div>
</template>
<script>

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
}


.header-lc {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 22px 0;
  /* background: yellow; */
  position : sticky;
  top: 0;
  margin-left: 105px;
  margin-right:105px;
}

.nav__link {
  padding:25px 8px;
  margin:0px 10px;
  font-size:600 15px / 26px "Nunito Sans", sans-serif;
  color:#767dac;
  border:0px solid #e2e8f0;
}
</style>
