<template>
  <div class="layout-lc">
    <header class="header-lc">
      <strong>
        <a href="#beranda"><img src="../gambar/logo.png" style="height: 32px; width: 183px;" /></a>
      </strong>

      <div class="menu-toggle" @click="toggleMenu">
        <i class="fa fa-bars"></i>
      </div>

      <nav id="nav" :class="{ 'nav-responsive': menuOpen }">
        <a class="nav__link" href="#">Beranda</a>
        <a class="nav__link" href="#lailatulcoding">Lailatul Coding</a>
        <a class="nav__link" href="#faq">Faq</a>
      </nav>
    </header>

    <button class="nav-button" @click="toggleMenu">Menu</button>
    
    <nav class="navbar" v-if="menuOpen">
      <a class="navbar__link" href="#">Beranda</a>
      <a class="navbar__link" href="#lailatulcoding">Lailatul Coding</a>
      <a class="navbar__link" href="#faq">Faq</a>
    </nav>

    <slot/>
  </div>
</template>

<script>
export default {
  data() {
    return {
      menuOpen: false,
    };
  },
  methods: {
    toggleMenu() {
      this.menuOpen = !this.menuOpen;
    },
  },
};
</script>

<style scoped>
/* Your existing styles here */

body {
  font-family: 'Nunito Sans', sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.5;
}

.header-lc {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 22px 0;
  background: white;
  position: sticky;
  top: 0;
  margin-left: 20px;
  margin-right: 20px;
}

.menu-toggle {
  color: rgb(94, 94, 94);
  font-size: 24px;
  cursor: pointer;
  display: none;
}

.nav__link {
  list-style-type: none;
  font-size: 15px;
  margin: 0;
  padding: 0;
  color: #767dac;
  font-weight: bold;
  text-align: center;
  padding: 10px 16px;
  text-decoration: none;
}

.nav-responsive {
  position: absolute;
  width: 100%;
  background: #333;
  top: 70px;
  left: -100%;
  transition: 0.5s all;
  display: block;
  z-index: 1000;
}

.navbar {
  background: #333;
  padding: 10px 20px;
  display: flex;
  justify-content: flex-start;
  align-items: center;
}

.navbar__link {
  color: #fff;
  font-weight: bold;
  text-decoration: none;
  margin-right: 20px;
}

.nav-button {
  display: none;
  font-size: 16px;
  background: #333;
  color: #fff;
  border: none;
  cursor: pointer;
  padding: 10px 20px;
  border-radius: 5px;
}

@media (max-width: 768px) {
  /* Existing styles for mobile view */

  .menu-toggle {
    display: block;
    margin-right: 20px;
  }

  .nav-button {
    display: block;
    margin: 10px auto;
  }

  .navbar {
    display: flex;
    flex-direction: column;
    background: #333;
    position: absolute;
    width: 100%;
    top: 70px;
    left: -100%;
    transition: 0.5s all;
    z-index: 1000;
  }

  .navbar__link {
    color: #fff;
    font-weight: bold;
    text-decoration: none;
    margin-right: 0;
    margin-bottom: 10px;
    padding: 10px 16px;
    text-align: center;
  }

  .nav-responsive {
    top: 50px;
  }
}
</style>
