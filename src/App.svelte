<script>
  import Navbar from "./lib/navbar.svelte"
  import logo2 from "./assets/peenuxlogo.svg"
  import bg from "./assets/backgroundimage.svg"
</script>
<style>
  .text-font {
    font-family: 'Inter', sans-serif;
  }
</style>
<Navbar />
<div class="bg-cover bg-center min-h-screen" style="background-image: url({bg})"></div>
 <div class="absolute inset-0">
  <div  data-aos="zoom-in" class="min-h-screen px-3 sm:px-52 items-center justify-center flex flex-col space-y-8  bg-gradient-to-t from-[black]  boyut mb-5 ">
    <img class="h-32 sm:mt-0 mt-10 sm:h-40 xl:mt-32 2xl:h-52" src={logo2} alt="">
    <h1 class=" text-center  text-white/70 mt-5 text-font text-lg break-words sm:text-xl">Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita officia ab quae provident natus! Illum, quia! Debitis, atque incidunt accusantium, quo dicta maiores voluptatibus magni repudiandae illo nobis omnis. Voluptatem?</h1>
    <div class="flex sm:flex-row flex-col items-center gap-4">
      <a target="_blank" href="https://discord.gg/7GvdW2V7" class="mr-1 mb-4 px-5 sm:px-5 py-2 sm:py-3  text-font  outline-none focus:outline-none  ease-linear transition-all duration-150 hover:bg-[#3845cf] text-white bg-[#404eed] items-center flex space-x-5 font-bold rounded-lg text-lg sm:text-xl"><i class="fa-brands fa-discord text-2xl "></i> <h1>Add To Discord</h1></a>
    </div>
   </div>
 </div>  

<div class="min-h-screen bg-black"></div>



