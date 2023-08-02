<template>
    <nav>
        <div class="wrapper">
          <div class="logo">
            <img src="../gambar/logo.png" alt style="height: 50px" />
          </div>

          <div class="menu">
            <ul>
              <li><a href="#beranda">Beranda</a></li>
              <li><a href="#lailatulcoding">Lailatulcoding</a></li>
              <li><a href="#faq">FAQ</a></li>
            </ul>
          </div>
        </div>
      </nav>
</template>

<script>
export default {
    nama : 'Navbar'
}
</script>
    
<style>

nav {
  width: 100%;
  margin: auto;
  display: flex;
  line-height: 80px;
  position: sticky;
  position: -webkit-sticky;
  top: 0;
  background-color: white;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  position: sticky;
}

nav ul li {
  float: left;
  position: sticky;
}

nav ul li a {
  color: #767dac;
  font-weight: bold;
  text-align: center;
  padding: 0px 16px 0px 16px;
  text-decoration: none;
  position: sticky;
}

nav ul li a:hover {
  text-decoration: underline;
}


</style>