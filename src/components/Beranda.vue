<template>
  <div id="beranda">
        <div class="hero">
          <div>
            <h2>Saatnya Developer Beramal!</h2>
            <p>Jika kamu developer dan menguasai wordpress, ayo bergabung di Lailatul Coding 2023! Tahun ini kita akan terjun langsung
                ngementorin santri agar mereka bisa membuat website untuk masjid di daerah asalnya.</p>
            <p><strong>LailatulCoding 2023 akan dilaksanakan pada tanggal 13-14 April 2023</strong></p>
            <p><strong>Pendaftaran dimulai dari 24 Maret - 12 April dan dibuka untuk Developer, Santri & Project Owner</strong></p>
            <p> 
            <a href="https://bit.ly/devlc2023" class="tbl-pink">Daftar Volunteer →<i class="mdi-arrow-right"></i> </a>
            <a href="https://bit.ly/santrilc2023" class="tbl-blue">Daftar Santri →</a></p>
            <p><a href="https://bit.ly/polc2023" class="tbl-blue">Daftar Projek Owner →</a></p>
          </div>
          <div>
            <img src="https://lailatulcoding.com/_nuxt/img/caa8ff3.svg" style="padding-top: 78px;" />
          </div>
        </div>
        
</div>
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
#beranda:target {
  padding-top: 100px; /* Atur nilai sesuai jarak yang diinginkan */
}
#beranda .hero {
  display: flex; 
  margin-top: 54px; 
  margin-bottom: 70px;
  /* background: red; */
  margin-left: 105px;
  margin-right:105px;
}
#beranda .kolom-lc {
  margin-left: 10px;
  margin-right: 10px;
  float: left;
  display: flex;
}

.kolom .deskripsi {
  font-size: 20px;
  font-weight: bold;
  font-family: "Nunito Sans,sans-serif";
  color: #767dac;
}

#beranda .kolom-lc .h2 {
  font-family: "Nunito Sans,sans-serif";
  font-weight: 800;
  font-size: 45px;
  margin-bottom: 20px;
  color: #33324e;
  width: 100%;
  line-height: 50px;
}


a.tbl-pink {
        background: #4353ff;
        border-radius: 5px;
        margin-top: 20px;
        padding: 15px 20px 15px 20px;
        color: #FFFFFF;
        cursor: pointer;
        font-weight: bold;
        text-align: center;
        margin-right: 10px;
    }

a.tbl-pink:hover {
        background: #00b58c;
        text-decoration: none;
    }

a.tbl-blue {
        background: #00b58c;
        border-radius: 5px;
        margin-top: 20px;
        padding: 15px 20px 15px 20px;
        color: #FFFFFF;
        cursor: pointer;
        font-weight: bold;
    }

    a.tbl-blue:hover{
        background: #00b58c;
        text-decoration: none;
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