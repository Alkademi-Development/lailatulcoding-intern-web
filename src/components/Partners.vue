<template>
    <div id="partners">
           <div class="partner-list">
               <div class="kartu-partner">
                   <div v-for="partnerImage in wisata" v-bind:key="partnerImage" > </div> 
                       <img src="../gambar/Alkademi.png"/>
                       <!-- <img wisataImage.img> -->
               </div>
               <div class="kartu-partner">
                   <img src="../gambar/idcloudhost.png"/>
               </div>
               <div class="kartu-partner">
                   <img src="https://lailatulcoding.com/assets/template/images/brand-radya.svg"/>
               </div>
               <div class="kartu-partner">
                   <img src="../gambar/rumahamalsalman.png"/>
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
         img: '../gambar/Alkademi.png',
         img2: '../gambar/idcloudhost.png',
         img3: "https://lailatulcoding.com/assets/template/images/brand-radya.svg",
         img :"../gambar/rumahamalsalman.png",
         img :"../gambar/sttcipasung.png",
         img : "../gambar/startupbandung.png",
         img : "../gambar/geekhunterlogo.png",
         img : "../gambar/tiarbah.png",
         img : "../gambar/feedlooplogo.png",
         img : "https://lailatulcoding.com/assets/template/images/logo-qw-light.webp",
         img : "../gambar/qiwii.png",
         img : "../gambar/nuo-jateng.png",
         img : "../gambar/indocisc.png",
         img : "../gambar/block-71.png",
         img : "../gambar/1000-startup.png",
         img : "../gambar/potensee.png",
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