<template>
    <div>
    <!-- Title Text -->
    <div class="text-5xl font-extrabold">
      <span class="brightness-125 antialiased animate-pulse pl-5 bg-clip-text text-transparent bg-gradient-to-r from-pink-500 to-violet-500">
        V TRIP
      </span>
      <p class="text-base pl-6  items-center">รายการความสนุกของเรามีดังนี้</p>
      <div class="m-5 max-w-xl grid grid-cols-1 gap-2 h-96 text-center font-medium sm:max-w-5xl lg:max-w-7xl xl:max-w-full xl:grid-cols-2">
        <div class="col-start-1  bg-fuchsia-200   rounded-bl-2xl rounded-tr-2xl text-pink-500 shadow-lg shadow-pink-500/50 text-3xl"><div class="rounded-tr-2xl bg-gradient-to-r from-pink-500 to-violet-400 text-white">SQUID@JOMTIEN BEACH</div>  <hr><span class="text-base pl-2">จุดลับๆสำหรับตกหมึกสดๆยามค่ำคืน บรรยากาศส่วนตัวริมหาดจอมเทียน บางทริปก็กินหมึกเล็ก บางทริปก็หมึกใหญ่ บางทริปก็กินน้ำฝน</span> 
        <p class="text-xs animate-ping text-red-500 m-2"><router-link to="/contact">ทัวร์เลย</router-link></p></div>
        <div class="col-start-1 xl:col-start-2 bg-fuchsia-200   rounded-bl-2xl rounded-tr-2xl text-pink-500 shadow-lg shadow-pink-500/50 text-3xl"><div class="rounded-tr-2xl bg-gradient-to-r from-pink-500  to-violet-400 text-white">FISHING SUNLIGHT</div>  <hr><span class="text-base pl-2">ตกปลาเก๋าล่าวัตถุดิบยามเย็น วิวสวยเห็นพระอาทิตย์ตก ถ้าได้ปลาก็กินอาหารสด ไม่ได้ก็อาหารกระป๋อง</span> 
        <p class="text-xs animate-ping text-red-500 m-2"><router-link to="/contact">ทัวร์เลย</router-link></p></div>
        <div class="col-start-1  bg-fuchsia-200  rounded-bl-2xl rounded-tr-2xl text-pink-500 shadow-lg shadow-pink-500/50 text-3xl"><div class="rounded-tr-2xl bg-gradient-to-r from-pink-500  to-violet-400 text-white">NIGHT PARTY</div>  <hr><span class="text-base pl-2">ผับเด็ดๆดังๆ ในพัทยาฉบับเข้าทางออก ออกทางเข้า ถ้าภาษาดี มีกินฟรีตลอดงาน</span> 
        <p class="text-xs animate-ping text-red-500 m-2"><router-link to="/contact">ทัวร์เลย</router-link></p></div>
        <div class="col-start-1 xl:col-start-2 bg-fuchsia-200  rounded-bl-2xl rounded-tr-2xl text-pink-500 shadow-lg shadow-pink-500/50 text-3xl"><div class="rounded-tr-2xl bg-gradient-to-r from-pink-500  to-violet-400 text-white">NIGHT MARKET</div>  <hr><span class="text-base pl-2">ยกขโยงกันมาทั้งพัทยา ร้านเด็ดร้านดัง เหล้า ยา ปลาปิ้ง ครบจบในตลาดเดียว</span> 
        <p class="text-xs animate-ping text-red-500 m-2"><router-link to="/contact">ทัวร์เลย</router-link></p></div>
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
    
  }
}
</script>

<style scoped>

</style>