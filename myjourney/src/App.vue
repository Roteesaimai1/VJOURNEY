<template>
  <div class="main">
    <div class="head text-white text-center"> <navbar/> </div>
    <div class="content text-white">
      <router-view></router-view>
    </div>
    <div class="footer text-white">
      <p >footer</p>
    </div>
  </div>
  
</template>

<script>
import navbar from './components/navbar.vue';

export default {
  components: { navbar },
  name: "App"
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Mitr:wght@300&display=swap');
.main {
  display: grid;
  grid-template-rows: 4fr 30fr 1fr;
}
body {
  background-color: #09090b;
  box-sizing: border-box;
  min-height: 100vh;
  font-family: 'Mitr', sans-serif;
}
</style>