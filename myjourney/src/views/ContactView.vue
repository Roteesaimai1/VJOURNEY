<template>
  <div>
    <!-- Title Text -->
    <div class="text-5xl font-extrabold">
      <span class="brightness-125 antialiased animate-pulse pl-5 xl:pl-24 bg-clip-text text-transparent bg-gradient-to-r from-pink-500 to-violet-500 ">
        CONTACT US 
      </span>
      
        <p class="text-base pl-6 xl:pl-24 items-center ">ติดต่อบริการ</p>
        <div class="text-center text-black rounded-lg m-5 xl:m-24 font-medium bg-fuchsia-200 h-96 shadow-lg shadow-pink-500/40  ">
          
          <div class="text-3xl text-red-50  bg-gradient-to-r from-pink-500 to-violet-400">ติดต่อจองทัวร์</div>
          <div class="text-base m-2 ">
            <p class="text-pink-500">ชื่อจริง</p>
            <input type="text" placeholder="FirstName" class="w-3/4 rounded-md border-2 border-red-300 hover:border-red-500">
          </div>
          <div class="text-base m-2">
            <p class="text-pink-500">นามสกุล</p>
            <input type="text" placeholder="LastName" class="w-3/4 rounded-md border-2 border-red-300 hover:border-red-500">
          </div>
          <div class="text-base m-2">
            <p class="text-pink-500">Email</p>
            <input type="email" placeholder="Email" class="w-3/4 rounded-md border-2 border-red-300 hover:border-red-500">
          </div>
          <div class="text-base m-2">
            <p class="text-pink-500">จำนวนคนที่จอง</p>
            <input type="number" placeholder="" class="w-3/4 rounded-md border-2 border-red-300 hover:border-red-500">
          </div>
          <div class="text-base m-5">
            <button @click="sendform()" class="text-pink-50 bg-gradient-to-r from-pink-500 to-red-400 rounded-xl w-20 h-8 shadow-lg  shadow-red-500/40 hover:bg-gradient-to-t hover:from-red-500 hover:to-pink-400">จอง</button>
          </div>
        </div>
        </div>
    
    
  </div>
</template>
<script>
export default{
  data() {
    return{

    }
  },
  methods:{
    sendform() {
      alert('ขออภัย ตอนนี้มีผู้ใช้บริการยาวถึงปีใหม่ ขอบคุณค่ะ')
    }  
  }
}
</script>

<style scoped>

</style>
