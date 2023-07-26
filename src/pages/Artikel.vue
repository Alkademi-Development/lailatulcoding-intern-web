<template>
  <Layout>
    <link rel="stylesheet" href="style.css">
    
      <header>
        <h1>Tujuan Wisata Indonesia yang Populer di Mata Dunia</h1>
      </header>
    
    <div class=" container"> 
      <div v-for="wisataSaya in wisata" v-bind:key="wisataSaya.id" class="artikel-1">
          <div class="card">
            <article> 
              <div  class="wisata"> 
                <a href="/berita"> <h1>{{wisataSaya.nama}}</h1> </a>

              <div v-for="wisataImage in wisata" v-bind:key="wisataImage" > 
               </div> 
                <g-image src="../gambar/1.jpg" alt="gambar 5" class="card__img" width="500"/>
                  <div class="card__details">

              <div v-for="wisataDes in wisata" v-bind:key="wisataDes" > 
                  <p>{{ wisataDes.deskripsi}}</p> 

               <div v-for="wisataAdm in wisata" v-bind:key="wisataAdm" > 
               <span>{{ wisataAdm.adm}}</span> </div>
              </div>
                  </div>
                </div>
              </article>
          </div> 
              </div>
        
  <div class=" container2"> 
      <div v-for="wisataSaya in wisata" v-bind:key="wisataSaya.id" class="artikel-1">
          <div class="card">
            <article> 
              <div  class="wisata"> 
                <a href="/berita2"> <h1>{{wisataSaya.nama2}}</h1> </a>

                <div v-for="wisataImage in wisata" v-bind:key="wisataImage" > 
               </div> 
                <g-image src="../gambar/2.jpg" alt="gambar 2" class="card__img" width="500"/>
                  <div class="card__details">

              <div v-for="wisataDes in wisata" v-bind:key="wisataDes" > 
                  <p>{{ wisataDes.deskripsi}}</p> 

               <div v-for="wisataAdm in wisata" v-bind:key="wisataAdm" > 
               <span>{{ wisataAdm.adm}}</span> </div>
              </div>
                  </div>
                </div>
              </article>
          </div> 
        </div>
    </div>
        
  <div class=" container3"> 
      <div v-for="wisataSaya in wisata" v-bind:key="wisataSaya.id" class="artikel-3">
          <div class="card">
            <article> 
              <div  class="wisata"> 
                <a href="/berita3"> <h1>{{wisataSaya.nama3}}</h1> </a>

                <div v-for="wisataImage in wisata" v-bind:key="wisataImage" > 
                <g-image src="../gambar/3.jpg" alt="gambar 3" class="card__img" width="500"/>
                  <div class="card__details">

                <div v-for="wisataDes3 in wisata" v-bind:key="wisataDes3" > 
                  <p>{{ wisataDes3.deskripsi3}}</p> 

                <div v-for="wisataAdm3 in wisata" v-bind:key="wisataAdm3" > 
               <span>{{ wisataAdm3.adm3}}</span> </div>
                </div>
                </div>
                </div> 
              </div>
            </article>
          </div> 
      </div>
  </div>      

   <div class=" container4"> 
      <div v-for="wisataSaya in wisata" v-bind:key="wisataSaya.id" class="artikel-4">
          <div class="card">
            <article> 
              <div  class="wisata"> 
                <a href="/berita4"> <h1>{{wisataSaya.nama4}}</h1> </a>

                <div v-for="wisataImage in wisata" v-bind:key="wisataImage" > 
               </div> 
                <g-image src="../gambar/4.jpg" alt="gambar 4" class="card__img" width="500"/>
                  <div class="card__details">

              <div v-for="wisataDes4 in wisata" v-bind:key="wisataDes4" > 
                  <p>{{ wisataDes4.deskripsi4}}</p> 

               <div v-for="wisataAdm4 in wisata" v-bind:key="wisataAdm4" > 
               <span>{{ wisataAdm4.adm4}}</span> </div>
              </div>
                  </div>
                </div>
              </article>
          </div> 
        </div>
    </div>
            

    <div class=" container5"> 
      <div v-for="wisataSaya in wisata" v-bind:key="wisataSaya.id" class="artikel-5">
          <div class="card">
            <article> 
              <div  class="wisata"> 
                <a href="/berita5"> <h1>{{wisataSaya.nama5}}</h1> </a>

                <div v-for="wisataImage in wisata" v-bind:key="wisataImage" > 
               </div> 
                <g-image src="../gambar/5.jpg" alt="gambar 5" class="card__img" width="500"/>
                  <div class="card__details">

              <div v-for="wisataDes5 in wisata" v-bind:key="wisataDes5" > 
                  <p>{{ wisataDes5.deskripsi5}}</p> 

               <div v-for="wisataAdm5 in wisata" v-bind:key="wisataAdm5" > 
               <span>{{ wisataAdm5.adm5}}</span> </div>
              </div>
                  </div>
                </div>
              </article>
          </div> 
        </div>
    </div>        
            


    <div class=" container6"> 
      <div v-for="wisataSaya in wisata" v-bind:key="wisataSaya.id" class="artikel-6">
          <div class="card">
            <article> 
              <div  class="wisata"> 
                <a href="/berita6"> <h1>{{wisataSaya.nama6}}</h1> </a>

                <div v-for="wisataImage in wisata" v-bind:key="wisataImage" > 
               </div> 
                <g-image src="../gambar/6.jpg" alt="gambar 6" class="card__img" width="500"/>
                  <div class="card__details">

              <div v-for="wisataDes6 in wisata" v-bind:key="wisataDes6" > 
                  <p>{{ wisataDes6.deskripsi6}}</p> 

               <div v-for="wisataAdm6 in wisata" v-bind:key="wisataAdm6" > 
               <span>{{ wisataAdm6.adm6}}</span> </div>
              </div>
                  </div>
                </div>
              </article>
          </div> 
        </div>
    </div>       


</div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'About us',
  },
  data: function(){
    return {
      wisata: [
        { 
          nama: "1.Pura Besakih",
          nama2: "2.Kepualauan Derawan",
          nama3: "3.Taman Nasional Way Kambas",
          nama4: "4.Pantai Parai Tenggiri (Bangka Belitung)",
          nama5: "5.Nusa Dua (Bali)",
          nama6: "6.Gunung Rinjani (Lombok NTB)",
          img: '../gambar/1.jpg',
          img2: '../gambar/2.jpg',
          img3: '../gambar/3.jpg',
          img4: '../gambar/4.jpg',
          img5: '../gambar/5.jpg',
          img6: '../gambar/6.jpg',
          deskripsi :  "Banyak daerah di Indonesia yang sangat terkenal sebagai destinasi wisata internasional. Berikut 20 daerah di Indonesia yang terkenal hingga ke mancanegara. ",
          deskripsi2 :  "Banyak daerah di Indonesia yang sangat terkenal sebagai destinasi wisata internasional. Berikut 20 daerah di Indonesia yang terkenal hingga ke mancanegara. ",
          deskripsi3 : "Bandung menjadi salah satu tujuan wisata favorit bagi banyak orang. Suasananya yang sejuk dan asri, membuat Bandung sering dijadikan sebagai tempat tujuan untuk berjalan-jalan dan menenangkan pikiran.",
          deskripsi4 :  "Pasti diantara kamu sudah pernah menyaksikan film populer Laskar Pelangi yang berlatar di Pulang Belitung, bukan? Selain alur ceritanya yang menarik, lokasi film ini juga banyak menyita perhatian penonton.",
          deskripsi5 :  "pulau Seribu Dewa satu ini memang tidak perlu diragukan lagi terkait keindahan dan pesonanya dalam memikat para wisatawan dalam negeri maupun mancanegara. Di Bali, ada satu tempat wisata yang begitu cantik, yakni Nusa Dua.",
          deskripsi6 : "Selain Gili Trawangan, di Nusa Tenggara Barat juga terdapat wisata yang tak kalah populer dan cocok bagi kamu yang suka mendaki, yakni Gunung Rinjani. Gunung ini adalah gunung berapi tertinggi kedua yang ada di Indonesia. ",
          adm : "admin",
          adm2 : "admin",
          adm3 : "admin",
          adm4 : "admin",
          adm5 : "admin",
          adm6 : "admin",

          
        },
      ]
    }
  }
}
</script>
