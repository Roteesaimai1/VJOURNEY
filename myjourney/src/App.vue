<template>
  <div class="main">
    <div class="head text-white text-center"> <navbar/> </div>
    <div class="content text-white mt-20">
      <router-view></router-view>
    </div>
    <div class="footer text-white pl-6 fixed bottom-0 text-zinc-500">
      <p>Made With ❤️<span><button class="text-rose-600" @click="contactus()"> จองด่วน ของเต็ม</button></span></p> 
      
    </div>
  </div>
  
</template>

<script>
import navbar from './components/navbar.vue';

export default {
  components: { navbar },
  name: "App",
  data(){
    return{

    }
  },
  methods:{
    contactus() {
      alert('เสียใจด้วย บริการของเราเต็มแล้ว กรุณาลองใหม่อีกครั้ง')
    }
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Mitr:wght@300&display=swap');
.main {
  display: grid;
  /* grid-template-rows: 4fr 30fr; */
}
body {
  background-color: #09090b;
  box-sizing: border-box;
  min-height: 100vh;
  font-family: 'Mitr', sans-serif;
}
</style>