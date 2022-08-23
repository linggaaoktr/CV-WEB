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



}
</style>
