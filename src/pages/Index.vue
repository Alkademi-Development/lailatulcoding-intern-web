<template>
  <Layout>
    <nav>
      <div class="wrapper">
        <div class="logo">
          <img src="../gambar/logo.png" alt style="height: 32px" />
        </div>

        <div class="menu">
          <ul>
            <li><a href="#beranda">Beranda</a></li>
            <li><a href="#lailatulcoding">Lailatulcoding</a></li>
            <li><a href="#faq">FAQ</a></li>
          </ul>
        </div>
      </div>
    </nav>
    <div class="wrapper">
      <!-- untuk beanda -->
      <section id="beranda">
        <div class="kolom">
          <p class="deskripsi"></p>
              <h2>Saatnya Developer Beramal!</h2>
              <p>
                Jika kamu developer dan menguasai wordpress, ayo bergabung di
                Lailatul Coding 2023! Tahun ini kita akan terjun langsung
                ngementorin santri agar mereka bisa membuat website untuk masjid
                di daerah asalnya.
              </p>
              <p>
                <strong
                  >LailatulCoding 2023 akan dilaksanakan pada tanggal 13-14
                  April2023</strong
                >
              </p>
              <p>
                <strong
                  >Pendaftaran dimulai dari 24 Maret - 12 April dan dibuka
                  untukDeveloper, Santri & Project Owner</strong
                >
              </p>
              <div class="btn">
                <p>
                  <a href="https://bit.ly/devlc2023" class="tbl-pink"
                    >Daftar Volunteer</a
                  >
                  <a href="https://bit.ly/santrilc2023" class="tbl-green"
                    >Daftar Santri</a
                  >
                </p>
                <p>
                  <a href="https://bit.ly/polc2023" class="tbl-blue"
                    >Daftar Projek Owner</a
                  >
                </p>
              </div>
          
          

          <!-- untuk lailatulcoding -->
          <section id="lailatulcoding">
            <div class="kolom">
              <p class="deskripsi"></p>
              <h2>Saatnya Developer Beramal!</h2>
              <p>
                Jika kamu developer dan menguasai wordpress, ayo bergabung di
                Lailatul Coding 2023! Tahun ini kita akan terjun langsung
                ngementorin santri agar mereka bisa membuat website untuk masjid
                di daerah asalnya.
              </p>
              <p>
                <strong
                  >LailatulCoding 2023 akan dilaksanakan pada tanggal 13-14
                  April2023</strong
                >
              </p>
              <p>
                <strong
                  >Pendaftaran dimulai dari 24 Maret - 12 April dan dibuka
                  untukDeveloper, Santri & Project Owner</strong
                >
              </p>

              <div class="btn">
                <p>
                  <a href="https://bit.ly/devlc2023" class="tbl-pink"
                    >Daftar Volunteer</a
                  >
                  <a href="https://bit.ly/santrilc2023" class="tbl-green"
                    >Daftar Santri</a
                  >
                </p>
                <p>
                  <a href="https://bit.ly/polc2023" class="tbl-blue"
                    >Daftar Projek Owner</a
                  >
                </p>
              </div>
            </div>
            <img src="https://lailatulcoding.com/_nuxt/img/caa8ff3.svg" />
          </section>

          <section id="faq">
            <div class="kolom">
              <p class="deskripsi"></p>
              <h2>Saatnya Developer Beramal!</h2>
              <p>
                Jika kamu developer dan menguasai wordpress, ayo bergabung di
                Lailatul Coding 2023! Tahun ini kita akan terjun langsung
                ngementorin santri agar mereka bisa membuat website untuk masjid
                di daerah asalnya.
              </p>
              <p>
                <strong
                  >LailatulCoding 2023 akan dilaksanakan pada tanggal 13-14
                  April2023</strong
                >
              </p>
              <p>
                <strong
                  >Pendaftaran dimulai dari 24 Maret - 12 April dan dibuka
                  untukDeveloper, Santri & Project Owner</strong
                >
              </p>

              <div class="btn">
                <p>
                  <a href="https://bit.ly/devlc2023" class="tbl-pink"
                    >Daftar Volunteer</a
                  >
                  <a href="https://bit.ly/santrilc2023" class="tbl-green"
                    >Daftar Santri</a
                  >
                </p>
                <p>
                  <a href="https://bit.ly/polc2023" class="tbl-blue"
                    >Daftar Projek Owner</a
                  >
                </p>
              </div>
            </div>
            <img src="https://lailatulcoding.com/_nuxt/img/caa8ff3.svg" />
          </section>

        </div>
      </section>
    </div>
  </Layout>
</template>



<script>
export default {
  metaInfo: {
    title: "Lailatulcoding",
  },
};
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
  widht: 1100px;
  margin: auto;
  position: relative;
  background: #ffffff;
}

.logo a {
  float: left;
  font-size: 50px;
  font-weight: 800;
  font-family: courier;
  color: #364f6b;
}

.menu {
  float: right;
}

nav {
  width: 100%;
  margin: auto;
  display: flex;
  line-height: 80px;
  position: sticky;
  position: -webkit-sticky;
  top: 0;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
}

nav ul li {
  float: left;
}

nav ul li a {
  color: #767dac;
  font-weight: bold;
  text-align: center;
  padding: 0px 16px 0px 16px;
  text-decoration: none;
}

nav ul li a:hover {
  text-decoration: underline;
}

section img {
  float: right;
  width: 40%;
}

section {
  margin: auto;
  display: flex;
  margin-bottom: 50px;
  float: left;
}

.kolom {
  margin-top: 50px;
  margin-bottom: 50px;
  float: left;
}

.kolom .deskripsi {
  font-size: 20px;
  font-weight: bold;
  font-family: "Nunito Sans,sans-serif";
  color: #767dac;
}

h2 {
  font-family: "Nunito Sans,sans-serif";
  font-weight: 800;
  font-size: 45px;
  margin-bottom: 20px;
  color: #33324e;
  width: 100%;
  line-height: 50px;
}

.btn {
  font-size: 15px;
  padding: 0.7rem 1.4rem;
  transition: all 0.4s;
  font-weight: 600;
  margin: auto;
}

a.tbl-pink {
  background: #4353ff;
  border-color: #4353ff;
  border-radius: 20px;
  margin-top: 50px;
  padding: 15px 20px 15px 20px;
  color: #ffffff;
  cursor: pointer;
  font-weight: bold;
}

a.tbl-pink:hover {
  background: #00c99c;
  text-decoration: none;
}

a.tbl-green {
  background: #00c99c !important;
  border-color: #00c99c !important;
  border-radius: 20px;
  margin-top: 20px;
  padding: 15px 20px 15px 20px;
  color: #ffffff;
  cursor: pointer;
  font-weight: bold;
}
a.tbl-blue {
  background: #00c99c !important;
  border-color: #00c99c !important;
  border-radius: 20px;
  margin-top: 20px;
  padding: 15px 20px 15px 20px;
  color: #ffffff;
  cursor: pointer;
  font-weight: bold;
}

p {
  margin: 10px 0px 10px 0px;
  padding: 10px 0px 10px 0px;
  color: #767dac;
}
</style>


