<template>
  <layout>
  <!-- <div class="wrapper">
    <div> -->
      <div id="beranda"><Beranda /></div>
      <div id="lailatulcoding"><Lailatulcoding /></div>
      <div id="faq"><Faq /></div>
      <div id="partners"><Partners /></div>
      <div id="footer">
        <div class="copyright" style="background: yellow; margin-top: 100px;">
          <h6>2023 © BilkisNisa.</h6>
        </div>
      </div>
    <!-- </div>

    
  </div> -->
  </layout>
</template>

<script>
import Beranda from '../components/Beranda.vue'
import Lailatulcoding from '../components/Lailatulcoding.vue'
import Faq from '../components/Faq.vue'
import Partners from '../components/Partners.vue'


export default {
  components : {
    Beranda,
    Lailatulcoding, 
    Faq,
    Partners
  } 
  
}
</script>

<style>

/* body {
  margin: 0px;
  padding: 0px;
  font-family: "Open Sans", sans serif;
} */

.wrapper {
  width: 100%;
  margin: auto;
  position: relative;
  background: #ffffff;
}
.copyright {
    text-align: center;
    width: 100%;
    padding-top: 100px;
    margin-bottom: 50px;
    position: middle;
    color: #767dac;
}

</style>