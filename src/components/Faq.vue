<template>
  <div id="faq">
      <!-- <div class="tengah"> -->
      <div class="footer">
          <div class="tengah">
              <p><a href="" class="tbl-grey">FAQ</a> </p>
              <h2>Frequently Asked Question</h2>
          </div>

          <div class="footer-section">
                <div v-for="answerSaya in answer" v-bind:key="answerSaya.id" class="artikel-1">
                  <!-- <div class="card"> -->
                    <article> 
                                <div v-for="answerDes in answer" v-bind:key="answerDes" > 
                                    <h3>{{ answerDes.deskripsi}}</h3> 
                                </div>
                                <div v-for="answerJwb in answer" v-bind:key="answerJwb" > 
                                    <p>{{ answerJwb.jawaban}}</p> 
                                </div>
                    </article>
                 <!-- </div> -->
                </div>
            </div>  

    <div class="footer-section">
                  <div v-for="answerSaya in answer" v-bind:key="answerSaya.id" class="artikel-1">
                  <!-- <div class="card"> -->
                    <article> 
                                <div v-for="answerDes in answer" v-bind:key="answerDes" > 
                                    <h3>{{ answerDes.deskripsi2}}</h3> 
                                </div>
                                <div v-for="answerJwb in answer" v-bind:key="answerJwb" > 
                                    <p>{{ answerJwb.jawaban2}}</p> 
                                </div>
                    </article>
            <!-- </div> -->
        </div>
    </div>  

    <div class="footer-section">
                  <div v-for="answerSaya in answer" v-bind:key="answerSaya.id" class="artikel-1">
                  <!-- <div class="card"> -->
                    <article> 
                                <div v-for="answerDes in answer" v-bind:key="answerDes" > 
                                    <h3>{{ answerDes.deskripsi3}}</h3> 
                                </div>
                                <div v-for="answerJwb in answer" v-bind:key="answerJwb" > 
                                    <p>{{ answerJwb.jawaban3}}
                                      <ul>
                                      <li>Bandung: Jl Cisitu Indah VI no. 6, Kelurahan Dago, Kecamatan Coblong</li>
                                      <li>Tasikmalaya: Kampus STT Cipasung, Jl Raya Cisinga KM1, Cilampunghilir, Kecamatan Padakembang.</li>
                                      </ul>
                                    </p>    
                                </div>
                    </article>
            <!-- </div> -->
        </div>
    </div>  

    <div class="footer-section">
                  <div v-for="answerSaya in answer" v-bind:key="answerSaya.id" class="artikel-1">
                  <!-- <div class="card"> -->
                    <article> 
                                <div v-for="answerDes in answer" v-bind:key="answerDes" > 
                                    <h3>{{ answerDes.deskripsi4}}</h3> 
                                </div>
                                <!-- <div v-for="answerJwb in answer" v-bind:key="answerJwb" >  -->
                                  <p class="mb-0">
                                     <ol style='list-style: number; margin-left: 1rem'>
                                      <li>Volunteer: Peran kamu adalah pionir pengembang website-website rumah ibadah dalam satu malam!</li>
                                      <li>Santri Belajar: Kamu santri, kamu belajar sekaligus membuatkan website rumah ibadah dalam satu malam!</li>
                                      <li>Project Owner: Kamu memiliki informasi rumah ibadah, pesantren atau panti asuhan yang akan dibuatkan websitenya.</li>
                                      <li>Donatur: Masyarakat umum yang ingin berkontribusi memberikan sedikit sumbangsih dalam bentuk apapun untuk event Lailatul Coding</li>
                                  </ol></p>
                    </article>
            <!-- </div> -->
        </div>
    </div> 

    <div class="footer-section">
                  <div v-for="answerSaya in answer" v-bind:key="answerSaya.id" class="artikel-1">
                  <!-- <div class="card"> -->
                    <article> 
                                <div v-for="answerDes in answer" v-bind:key="answerDes" > 
                                    <h3>{{ answerDes.deskripsi5}}</h3> 
                                </div>
                                <div v-for="answerJwb in answer" v-bind:key="answerJwb" > 
                                    <p>{{ answerJwb.jawaban5}}</p> 
                                </div>
                    </article>
            <!-- </div> -->
        </div>
    </div>  

    <div class="footer-section">
                  <div v-for="answerSaya in answer" v-bind:key="answerSaya.id" class="artikel-1">
                  <!-- <div class="card"> -->
                    <article> 
                                <div v-for="answerDes in answer" v-bind:key="answerDes" > 
                                    <h3>{{ answerDes.deskripsi6}}</h3> 
                                </div>
                                <div v-for="answerJwb in answer" v-bind:key="answerJwb" > 
                                    <p>{{ answerJwb.jawaban6}}</p> 
                                </div>
                    </article>
            <!-- </div> -->
        </div>
    </div>  


  </div>
</div>
</template>

        

        




                    
                    <!-- <h3>Q: Dimana program ini akan berlangsung?</h3>
                    <p>
                      Lailatul Coding 2023 akan diadakan secara Hybrid; Online
                      dan Offline. Jadi kamu bisa mengikuti acara ini secara
                      Online dari tempat masing-masing. Asal jangan ketiduran
                      saja yaa
                    </p> -->
              

                  <!-- <div class="footer-section">
                      <h3>Q: Apa teknologi yang akan dipakai untuk pengembangan
                        website?</h3>
                      <p>
                        Untuk pengembangan website Rumah Ibadah di Lailatul
                        Coding ini, kita menggunakan Wordpress. Silahkan
                        dipersiapkan atau diingat-ingat lagi sebelum hari-H ya
                      </p>
                    </div> -->
                    <!-- <div class="footer-section">
                      <h3>Q:Dimana lokasi pelaksanaan jika offline</h3>
                      <p>Untuk penyelenggaraan Offline, kita mengadakan di dua tempat yakni 
                      Bandung dan Tasikmalaya. Untuk masing-masing lokasi, silahkan dicatat:</p>
                      <p><ul>
                           <li>Bandung: Jl Cisitu Indah VI no. 6, Kelurahan Dago, Kecamatan Coblong</li>
                            <li>Tasikmalaya: Kampus STT Cipasung, Jl Raya Cisinga KM1, Cilampunghilir, Kecamatan Padakembang.</li>
                             </ul></p>
                    </div> -->

                    <!-- <div class="footer-section">
                      <h3>Q: Bagaimana kita dapat berpartisipasi?</h3>
                      <p class="mb-0">
                        <ol style='list-style: number; margin-left: 1rem'>
                            <li>Volunteer: Peran kamu adalah pionir pengembang website-website rumah ibadah dalam satu malam!</li>
                            <li>Santri Belajar: Kamu santri, kamu belajar sekaligus membuatkan website rumah ibadah dalam satu malam!</li>
                            <li>Project Owner: Kamu memiliki informasi rumah ibadah, pesantren atau panti asuhan yang akan dibuatkan websitenya.</li>
                            <li>Donatur: Masyarakat umum yang ingin berkontribusi memberikan sedikit sumbangsih dalam bentuk apapun untuk event Lailatul Coding</li>
                        </ol></p>
                    </div> -->

                    <!-- <div class="footer-section">
                      <h3>Q: Tempat apa saja yang bisa dibuakan websitenya? </h3>
                      <p class="mb-0">Tahun ini, Lailatul Coding membuka kesempatan untuk Pesantren, Panti Asuhan, serta yang 
                        tergolong kepada rumah ibadah seperti: Masjid, Gereja, Klenteng, Pura, dan Wihara.</p>
                    </div> -->

                    <!-- <div class="footer-section">
                      <h3>Q: Bagaimana Jika Ingin Berdonasi? </h3>
                      <p class="mb-0">Donasi dapat disalurkan melalui transfer ke <br>
                            BNI 7770817151 <br>A.n Yayasan Alkademi Karya Bangsa</p>
                    </div> -->
                 
              <!-- </div> -->


<script>
export default {
  metaInfo: {
    title: 'Faq',
  },
  data: function(){
    return {
      answer: [
        { 
          deskripsi :  "Q: Dimana program ini akan berlangsung?",
          deskripsi2 : "Q: Apa teknologi yang akan dipakai untuk pengembangan website?",
          deskripsi3 : "Q:Dimana lokasi pelaksanaan jika offline",
          deskripsi4 : "Q: Bagaimana kita dapat berpartisipasi?",
          deskripsi5 : "Q: Tempat apa saja yang bisa dibuakan websitenya? ",
          deskripsi6 : "Q: Bagaimana Jika Ingin Berdonasi?",
          jawaban : " Lailatul Coding 2023 akan diadakan secara Hybrid; Online dan Offline. Jadi kamu bisa mengikuti acara ini secara Online dari tempat masing-masing. Asal jangan ketiduran saja yaa",
          jawaban2 : "Untuk pengembangan website Rumah Ibadah di Lailatul Coding ini, kita menggunakan Wordpress. Silahkan dipersiapkan atau diingat-ingat lagi sebelum hari-H ya",
          jawaban3 : "Untuk penyelenggaraan Offline, kita mengadakan di dua tempat yakni Bandung dan Tasikmalaya. Untuk masing-masing lokasi, silahkan dicatat:",
          jawaban5 : "Tahun ini, Lailatul Coding membuka kesempatan untuk Pesantren, Panti Asuhan, serta yang tergolong kepada rumah ibadah seperti: Masjid, Gereja, Klenteng, Pura, dan Wihara.",
          jawaban6 : "Donasi dapat disalurkan melalui transfer ke <br> BNI 7770817151 <br>A.n Yayasan Alkademi Karya Bangsa"
        },
      ]
    }
  }
}



      

      
  

</script>

<style>

.faq {
  background: #dedede;
  padding: 50px 0px 50px 0px;
}

a.tbl-grey {
  background: #767dac;
  border-radius: 20px;
  margin-top: 20px;
  padding: 15px 20px 15px 20px;
  color: #FFFFFF;
  cursor: pointer;
  font-weight: bold;
  text-align: center;
  margin-right: 10px;
    }

.footer {
  display: flex;
  flex-wrap: wrap;
  background: #d8d9e9;
  padding-left: 105px;
  padding-right:105px;

}

.footer-section {
  width: 452px;
  padding: 16px;
  margin-left: 55px;
  color: #767dac;
}

.footer-section h3 {
  margin : 8px 0px;
  font-size :700 20px / 28px;
}

.footer-section p {
  padding : 16px;
  font-size : 16px / 24px;
}

</style>