<script>
  import Navbar from "./lib/navbar.svelte"
  import logo2 from "./assets/peenuxlogo.svg"
  import bg from "./assets/backgroundimage.svg"
  import plus from "./assets/icon.svg"
  import sarı from "./assets/sar.svg"
  import mavi from "./assets/mavi.svg"
</script>
<style>
  .text-font {
    font-family: 'Inter', sans-serif;
  }
</style>
<Navbar />
<div class="bg-cover bg-center min-h-screen" style="background-image: url({bg})"></div>
 <div class="absolute inset-0">
  <div  data-aos="zoom-in" class="min-h-screen flex items-center  px-3 sm:px-10 md:px-20 lg:px-32 xl:px-52 2xl:px-96 bg-gradient-to-t from-[black]  boyut ">
      <div class="items-center mt-16 sm:mb-32 flex flex-col space-y-5 ">
        <img class="h-32 sm:mt-0 mt-10 sm:h-40 xl:mt-32 2xl:h-52" src={logo2} alt="">
        <h1 class=" text-center  text-white/70 mt-5 text-font text-lg break-words sm:text-xl">Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita officia ab quae provident natus! Illum, quia! Debitis, atque incidunt accusantium, quo dicta maiores voluptatibus magni repudiandae illo nobis omnis. Voluptatem?</h1>
              <div class="relative w-[5rem] sm:w-[10rem] lg:w-[40rem]">
                <img  src={sarı} class=" absolute right-[11rem] sm:right-[23rem] md:right-[24rem] lg:right-[38rem] top-1.5 h-6" alt="">
              </div>
              <div class="flex sm:flex-row flex-col items-center gap-4">
                <a target="_blank" href="https://discord.gg/7GvdW2V7" class="mr-1 w-72  mb-4 px-5 sm:px-3 py-2 sm:py-3  text-font justify-center  outline-none focus:outline-none  ease-linear transition-all duration-150 hover:bg-[#3845cf] text-white bg-[#404eed] items-center flex space-x-3 font-bold rounded-[6.5px] text-lg sm:text-xl"><img src={plus} class="w-5 h-5" alt=""> <h1>Add To Discord</h1></a>
                <a target="_blank" href="https://discord.gg/7GvdW2V7" class="mr-1 backdrop-blur-md bg-white mb-4 w-72 px-5 sm:px-3 py-2 sm:py-3 justify-center text-font  outline-none focus:outline-none  ease-linear transition-all duration-150  text-black  items-center flex space-x-3 font-bold rounded-[6.5px] text-lg sm:text-xl"><i class="fa-brands text-black fa-discord text-2xl "></i> <h1>Join Server</h1></a>
             
              </div>
              <div class="relative w-[5rem] sm:w-[10rem] lg:w-[40rem] ">
                <img  src={mavi} class="absolute bottom-3 left-[11rem] md:bottom-2 sm:left-[24rem] md:left-[24rem] lg:left-[39rem]   h-5" alt="">
              </div>
      </div>   
   </div>
   <a href="https://submission.bromb.co/peenux" class="fixed bottom-0 right-0  text-white outline-none focus:outline-none text-font px-4 py-3 mb-5 mr-5 ease-linear transition-all duration-150 items-center bg-[#3845cf] rounded-full cursor-pointer backdrop-blur-xl shadow-xl ">
    <i class="fa-solid fa-circle-question text-2xl"></i>
   </a>
 </div>  

<div class="min-h-screen bg-black"></div>



