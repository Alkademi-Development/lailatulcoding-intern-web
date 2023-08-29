<template>
    <div id="partners">
           <div class="partner-list">
               <div class="kartu-partner">
                <article>
                <div v-for="edge in $static.allImage.edges" :key="edge.id" class="article">
                      <div class="image">{{ edge.node.image }}</div>
                </div>
              </article>
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
    <!-- <static-query>
        query {
        allImage {
          edges {
            node {
              id
              image
            }
          }
        }
      }
    </static-query> -->
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


