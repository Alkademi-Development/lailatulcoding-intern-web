<template>
  <container>
    <div id="beranda">
        <div class="container">
          <div class="deskripsi-3">
              <h1>Saatnya Developer Beramal!</h1>
              <p>Jika kamu developer dan menguasai wordpress, ayo bergabung di Lailatul Coding 2023! Tahun ini kita akan terjun langsung
                  ngementorin santri agar mereka bisa membuat website untuk masjid di daerah asalnya.</p>
              <!-- <p><strong>Lailatul Coding 2023 akan dilaksanakan pada tanggal 13-14 April 2023</strong></p>
              <p><strong>Pendaftaran dimulai dari 24 Maret - 12 April dan dibuka untuk Developer, Santri & Project Owner</strong></p>
              
              <p> <i class="tbl-pink"></i> 
              <a href="https://bit.ly/devlc2023" class="tbl-pink" target="_blank>"> Daftar Volunteer → </a> 
              <a href="https://bit.ly/santrilc2023" class="tbl-blue" target="_blank"> Daftar Santri →</a></p>
              <p><a href="https://bit.ly/polc2023" class="tbl-blue" target="_blank"> Daftar Projek Owner →</a></p> -->
            </div>
              <img src="https://lailatulcoding.com/_nuxt/img/caa8ff3.svg" style="padding-top: 78px; width: 500px; height: auto;" />
          </div>
   </div>
  </container>
  
</template>

<script>
export default {

}
</script>

<style>
 img {
  float: right;
  width: 540px;
  height: 415px;
}

#beranda .container {
  display: flex; 
  margin-top: 54px; 
  margin-bottom: 70px;
  /* background: red; */
  margin-left: 105px;
  margin-right:105px;
}

.container .deskripsi-3 {
  font-size: 20px;
  /* font-weight: bold; */
  font-family: "Nunito Sans,sans-serif";
  color: #33324e;
  margin : 0px 0px 8px;
}

#beranda .hero .deskripsi-3 .p {
  font-family: "Nunito Sans,sans-serif";
  font-weight: 800;
  font-size: 45px;
  margin-bottom: 20px;
  color: #00c99c;
  width: 100%;
  line-height: 50px;
}


a.tbl-pink {
    background: #3f72af;
    border-radius: 5px;
    margin-top: 20px;
    /* padding: 15px 20px 15px 20px; */
    padding : 11.2px 22.4px;
    color: #FFFFFF;
    cursor: pointer;
    font-weight: bold;
    /* text-align: center; */
    text-decoration: none;
    margin-right: 5px;
}

a.tbl-pink:hover {
    border : 3px solid #00c99c;
    
}
  
a.tbl-blue {
    background: #00c99c;
    border-radius: 5px;
    margin-top: 20px;
    /* padding: 15px 20px 15px 20px; */
    padding : 11.2px 22.4px;
    color: #FFFFFF;
    cursor: pointer;
    font-weight: bold;
    text-align: center;
    text-decoration: none;
    margin-right: 5px;
}

a.tbl-blue:hover {
    border : 3px solid #00c99c;
    
}

/* KODE CSS YANG DIBERIKAN RESPONSIVE DESIGN */
@media (max-width: 768px) {
  #beranda .container {
    flex-direction: column;
    align-items: center;
    margin-left: 20px;
    margin-right: 20px;
  }

  img {
    width: 200%;
    height: auto;
    padding-top: 20px;
  }
}

</style>