<template>
  <layout>
    <div class="wrapper">
    <div>
      <Beranda />
      <Lailatulcoding />
      <Faq />
      <!-- <Partner /> -->
    </div>
  </div>
  </layout>
</template>

<script>
import Beranda from '../components/Beranda.vue'
import Lailatulcoding from '../components/Lailatulcoding.vue'
import Faq from '../components/Faq.vue'
// import Partner from '../components/Partner.vue'


export default {
  components : {
    Beranda,
    Lailatulcoding, 
    Faq,
    // Partner
  } 
  
}
</script>

<style>

* {
  text-decoration: none;
  margin: 0px;
  padding: 0px;
}

body {
  margin: 0px;
  padding: 0px;
  font-family: "Open Sans", sans serif;
}

.wrapper {
  width: 1500px;
  margin: auto;
  position: relative;
  background: #ffffff;
  z-index: 100000;
}

.menu {
  float: right;
}

p {
  margin: 10px 0px 10px 0px;
  padding: 10px 0px 10px 0px;
  color: #767dac;
}

.tengah {
  text-align: center;
  width: 100%;
}



</style>