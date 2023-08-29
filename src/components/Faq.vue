<template>
  <div id="faq">
      <div class="judul">
      <div class="footer">
          <div class="tengah">
              <p><a href="" class="tbl-grey">FAQ</a> </p>
              <h1>Frequently Asked Question</h1>
          </div>
     

          <div class="footer-section">
            <article>
            <div v-for="edge in $static.allFaq.edges" :key="edge.id" class="article">
                  <div class="question">{{ edge.node.question }}</div>
                  <div class="answer">{{ edge.node.answer }}</div>
            </div>
          </article>
        </div>
    </div>             
  </div>
  </div>
</template>

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
          jawaban6 : "Donasi dapat disalurkan melalui transfer ke BNI 7770817151 A.n Yayasan Alkademi Karya Bangsa"
        },
      ]
    }
  }
}



      

      
  

</script>
<static-query>
  query {
  allFaq {
    edges {
      node {
        id
        question
        answer
      }
    }
  }
}
</static-query>
<style>

#faq {
    /* Gaya untuk kontainer utama FAQ */
    width: 80%;
    margin: 0 auto;
    padding: 20px;
    background-color: #f5f5f5;
    border: 1px solid #ccc;
    }

    .judul {
        /* Gaya untuk judul FAQ */
        text-align: center;
        margin-bottom: 20px;
    }

    .footer {
        /* Gaya untuk bagian footer FAQ */
        text-align: center;
        margin-top: 20px;
    }

    .tengah {
        /* Gaya untuk mengatur posisi elemen-elemen di tengah */
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .tbl-grey {
        /* Gaya untuk tautan dengan latar belakang abu-abu */
        background-color: #ccc;
        padding: 5px 10px;
        text-decoration: none;
        color: #fff;
    }

    h1 {
        /* Gaya untuk judul pertanyaan yang sering diajukan */
        font-size: 24px;
        margin-bottom: 20px;
    }

    .footer-section article{
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .article{
      padding: 20px;
      background-color: #fff;
      border: 1px solid #ccc;
      width: calc(50% - 50px);
    }

    .article-grid {
        display: grid;
        grid-template-columns: 1fr;
        gap: 20px;
    }

    /* Gaya untuk pertanyaan dalam artikel */
    .question {
        font-weight: bold;
        font-size: 18px;
        margin-bottom: 10px;
    }

    /* Gaya untuk jawaban dalam artikel */
    .answer {
        font-size: 16px;
        margin-top: 10px; /* Menambah ruang di atas jawaban */
        color: #767dac;
        text-align: justify;
    }

 
 @media (max-width: 768px) {
.article{
      width: 100%;
    }
  }
</style>