<script>
  import Navbar from "./lib/navbar.svelte"
  import logo2 from "./assets/peenuxlogo.svg"
  import bg from "./assets/backgroundimage.svg"
  import plus from "./assets/icon.svg"
  import sarı from "./assets/sar.svg"
  import mavi from "./assets/mavi.svg"
  import server from "./assets/servers.svg"
</script>
<style>
  .text-font {
    font-family: 'Inter', sans-serif;
  }

</style>
<Navbar />
<div class="bg-cover bg-center min-h-screen" style="background-image: url({bg})"></div>
 <div class="absolute inset-0">
  <div class="min-h-screen flex justify-center items-center px-3 bg-gradient-to-t from-[#202225]  boyut ">
      <div class="items-center mt-16 sm:mb-32 flex flex-col  ">
        <img class=" h-32 sm:mt-0 mb-5 mt-10 sm:h-40 xl:mt-32 2xl:h-52 " src={logo2} alt="">
        <h1 class=" text-center  text-white/70 mt-3 text-font  sm:w-[40rem]  text-lg break-words ">Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita officia ab quae provident natus! Illum, quia! Debitis, atque incidunt accusantium, quo dicta maiores voluptatibus magni repudiandae illo nobis omnis. Voluptatem?</h1>
              <div class="relative w-[5rem] sm:w-[10rem] lg:w-[40rem]">
                <img  src={sarı} class=" absolute right-[11rem] sm:right-[23rem] md:right-[24rem] lg:right-[38rem] top-3 h-5" alt="">
              </div>
              <div class="flex sm:flex-row flex-col items-center gap-4">
                <a target="_blank" href="https://discord.gg/7GvdW2V7" class="mr-1 pointer-events-none w-72  mb-4 px-5 sm:px-3 py-2  text-font justify-center mt-5  outline-none focus:outline-none  ease-linear transition-all duration-150 hover:bg-[#3845cf] text-white bg-[#404eed] items-center flex space-x-3 font-bold rounded-[6.5px] text-lg sm:text-xl"><img src={plus} class="w-5 h-5" alt=""> <h1>Add To Discord</h1></a>
                <a target="_blank" href="https://discord.gg/7GvdW2V7" class="w-72 pointer-events-none   bg-white mb-4 px-5 sm:px-3 py-1.5 justify-center text-font mt-5  outline-none focus:outline-none  ease-linear transition-all duration-150  text-black  items-center flex space-x-3 font-bold rounded-[6.5px] text-lg sm:text-xl"><i class="fa-brands text-black fa-discord text-2xl "></i> <h1>Join Server</h1></a>
             
              </div>
              <div class="relative w-[5rem] sm:w-[10rem] lg:w-[40rem] ">
                <img  src={mavi} class="absolute bottom-3 left-[11rem] md:bottom-2 sm:left-[24rem] md:left-[24rem] lg:left-[39rem]   h-4" alt="">
              </div>
      </div>   
   </div>
   <a href="https://submission.bromb.co/peenux" class="fixed bottom-0 z-40 right-0  text-white outline-none focus:outline-none text-font px-3 py-2 mb-5 mr-5 ease-linear transition-all duration-150 items-center bg-[#3845cf] rounded-full cursor-pointer backdrop-blur-xl shadow-xl ">
    <i class="fa-solid fa-circle-question text-2xl"></i>
   </a>
 </div>  

<div class="min-h-screen px-5 py-10 2xl:px-20 bg-[#202225]">
  <div class="md:bg-gradient-to-l bg-gradient-to-t relative py-3 flex md:flex-row flex-col items-center md:justify-end px-3 mt-5 h-96 rounded-[6.5px] w-full from-[#18191c] to-[#202225]">
    <img src={server} class="absolute pointer-events-none h-96 md:inset-x-4 right-0" alt="">
    <h1>dasds</h1>
  </div>


</div>



