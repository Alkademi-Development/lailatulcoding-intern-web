<template>
    

         <!-- <div class="partner-list"> 
            <div class="kartu-partner">
                <div v-for="partnerSaya in answer" v-bind:key="partnerSaya.id" class="artikel-1"> -->
                  <!-- <div class="card"> -->
                    <!-- <div v-for="wisataImage in wisata" v-bind:key="wisataImage" > 
               </div> 
                <g-image src="../gambar/5.jpg" alt="gambar 5" class="card__img" width="500"/> -->
            <!-- </div> -->
            <!-- </div>
        </div>
   </div> -->
   


   <div id="partners">
        <div class="tengah">
            <div class="partner-list">
                <div class="kartu-partner">
                    <div v-for="partnerImage in wisata" v-bind:key="partnerImage" > </div> 
                        <img src="../gambar/Alkademi.png"/>
                        <!-- <p>{{ wisataImage.img}}</p>  -->
                </div>
                <div class="kartu-partner">
                    <img src="../gambar/idcloudhost.png"/>
                </div>
                <div class="kartu-partner">
                    <img src="https://lailatulcoding.com/assets/template/images/brand-radya.svg"/>
                </div>
                <div class="kartu-partner">
                    <img src="../gambar/rumahamalsalman.png"/>"
                </div>
                <div class="kartu-partner">
                    <img src="../gambar/sttcipasung.png"/>
                </div>
                <div class="kartu-partner">
                    <img src="../gambar/startupbandung.png"/>
                </div>
                <div class="kartu-partner">
                    <img src="../gambar/geekhunterlogo.png"/>
                </div>
                <div class="kartu-partner">
                    <img src="../gambar/tiarbah.png"/>
                </div>
                <div class="kartu-partner">
                    <img src="../gambar/feedlooplogo.png"/>
                </div>
                <div class="kartu-partner">
                    <img src="https://lailatulcoding.com/assets/template/images/logo-qw-light.webp"/>
                </div>
                <div class="kartu-partner">
                    <img src="../gambar/qiwii.png"/>
                </div>
                <div class="kartu-partner">
                    <img src="../gambar/nuo-jateng.png"/>
                </div>
                <div class="kartu-partner">
                    <img src="../gambar/indocisc.png"/>
                </div>
                <div class="kartu-partner">
                    <img src="../gambar/block-71.png"/>
                </div>
                <div class="kartu-partner">
                    <img src="../gambar/1000-startup.png"/>
                </div>
                <div class="kartu-partner">
                    <img src="../gambar/potensee.png"/>
                </div>
            <!-- </div> -->
        </div>
    </div>
    </div>
</template>

<script>
export default {
    metaInfo: {
    title: 'Partners',
},
data: function(){
    return {
      partner: [
          {
          img: '../gambar/feedlooplogo.png',
          img2: '../gambar/idcloudhost.png',
          img3: '../gambar/3.jpg',
          img4: '../gambar/4.jpg',
          img5: '../gambar/5.jpg',
          img6: '../gambar/6.jpg',
          }
        ]
        }
    }
}
    


</script>

<style>

.partner-list {
    display: flex;
    flex-wrap : wrap;
    gap : 10px;
    margin-left: 105px;
    margin-right:105px;

}

.partner-list img {
    width: 350px;
    height : 180px;
    object-fit : contain;
}



</style>