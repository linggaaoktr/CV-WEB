<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>
<!-- <template>
 <div class="latar">
  <div class="greetings">
    <h1 class="black">{{ msg }}</h1>
    
    <h4>
    Tentang Saya
    </h4>
    
    <p>
      Saya Lingga Oktarina, siswi SMK Taruna Bhakti Depok, jurusan RPL . Memiliki kemampuan dalam mengoperasikan HTML, CSS, Bootstrap, Figma dan Wordpress. Serta sedikit memahami tentang Javascript, MySql, dan Laravel.</p> 
    
      <p>
      Role   = Front End<br>
      Alamat = Gg. Mandor rt 006 rw 01 Sukatani, Tapos, Depok<br>
      Email  = linggaoktarina2976@gmail.com<br>
      No. Hp = 0895367934076
      </p>
      
      
      </div>
  </div>
</template> -->

<template>
<div class="card-footer text-muted">
       <footer>Sosial Media</footer><br>
       <a href=""><i class="sosmed fa-brands fa-instagram"></i>@iamlinggaa</a><br>
       <a href=""><i class="sosmed fa-brands fa-github"></i>linggaaoktr</a><br>
       <a href=""><i class="sosmed fa-solid fa-envelope"></i>linggaoktarina2976@gmail.com</a><br>
       <a href=""><i class="sosmed fa-brands fa-whatsapp"></i>0895367934076</a><br>
       </div>
</template>


<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }

.sosmed{
    margin-left: 0.5px;
    margin-right: 0.5px;
    padding-bottom: 15px;
  }
  .sosmed i{
    margin-left: 20px;
  }

}
</style>
