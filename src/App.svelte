<script>
  import Navbar from "./lib/navbar.svelte"
  import logo2 from "./assets/peenuxlogo.svg"
  import bg from "./assets/backgroundimage.svg"
  import plus from "./assets/icon.svg"
  import sarı from "./assets/sar.svg"
  import mavi from "./assets/mavi.svg"
  import server from "./assets/servers.svg"
  import rank from "./assets/rankcard.svg"
  import slash from "./assets/slashcommands.svg"
  import leader from "./assets/leaderboards.svg"

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
        <h1 class=" text-center  text-white/70 mt-3 text-font  sm:w-[40rem] text-md break-words ">Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita officia ab quae provident natus! Illum, quia! Debitis, atque incidunt accusantium, quo dicta maiores voluptatibus magni repudiandae illo nobis omnis. Voluptatem?</h1>
              <div class="relative w-[5rem] sm:w-[10rem] lg:w-[40rem]">
                <img  src={sarı} class=" absolute right-[11rem] sm:right-[23rem] md:right-[24rem] lg:right-[38rem] top-5 h-5" alt="">
              </div>
              <div class="flex sm:flex-row mt-4 flex-col items-center gap-4">
                <a target="_blank" href="https://discord.gg/7GvdW2V7" class="mr-1 w-72 b-4 h-10  sm:px-3 py-2  text-font justify-center   outline-none focus:outline-none  ease-linear transition-all duration-150 hover:bg-[#3845cf] text-white bg-[#404eed] items-center flex space-x-3 font-bold rounded-[6.5px] text-lg sm:text-xl"><img src={plus} class="w-5 h-5" alt=""> <h1>Add To Discord</h1></a>
                <a target="_blank" href="https://discord.gg/7GvdW2V7" class="w-72 bg-white mb-4 h-10  sm:px-3 py-1.5 justify-center text-font mt-[1rem] outline-none focus:outline-none  ease-linear transition-all duration-150  text-black  items-center flex space-x-3 font-bold rounded-[6.5px] text-lg sm:text-xl"><i class="fa-brands text-black fa-discord text-2xl "></i> <h1>Join Server</h1></a>
             
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

<div class="min-h-screen  space-y-20 flex flex-col items-center justify-center px-5 py-10 xl:px-10 2xl:px-64 bg-[#202225]">
  <div  class="lg:bg-gradient-to-r bg-gradient-to-b py-3 flex lg:flex-row flex-col items-center lg:justify-end justify-center px-3 mt-5 lg:h-96 rounded-[6.5px] w-full from-[#18191c] to-[#202225]">
    <img data-aos="fade-up" src={server} class="lg:absolute pointer-events-none md:h-72 lg:h-96 h-72 lg:left-0 xl:left-0 2xl:left-40 " alt="">
    <div data-aos="fade-up" class="flex lg:text-end text-center items-center lg:items-end flex-col">
      <h2 class="text-font text-end mr-4 text-[#afafaf]">Features</h2>
      <h1 class="text-font text-white font-extrabold text-4xl mr-4">Server</h1>
      <p class="text-font text-white text-lg mr-1 w-auto mt-3 md:w-[20rem] lg:w-[20rem] xl:w-[30rem] 2xl:w-[48rem]">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quam, maxime eum. Sequi, distinctio laudantium voluptatem fuga unde excepturi magnam reiciendis, quisquam, repudiandae similique impedit mollitia beatae odio. Ab, assumenda error.</p>
      <a href="login" class="px-3 items-center text-center mt-5 w-64 rounded-[6.5px] text-black bg-white py-2">
        <span class="text-black text-font font-bold text-lg">More İnfo</span>
      </a>
    </div>
       
  </div>
    <div class="h-0.5 w-[10rem] sm:w-[40rem] mt-5 bg-[#444649]"></div>
  <div  class="lg:bg-gradient-to-l bg-gradient-to-b py-3 flex lg:flex-row flex-col items-center lg:justify-start justify-center px-3 mt-5 lg:h-96 rounded-[6.5px] w-full from-[#18191c] to-[#202225]">
    <img data-aos="fade-up" src={rank} class="lg:absolute pointer-events-none lg:h-64 xl:h-72 h-40 lg:right-0 xl:right-0 2xl:right-40 " alt="">
    <div data-aos="fade-up" class="flex mt-4 lg:text-start text-center items-center lg:items-start flex-col">
      <h2 class="text-font text-end mr-4 text-[#afafaf]">Features</h2>
      <h1 class="text-font text-white font-extrabold text-4xl mr-4">Ranking</h1>
      <p class="text-font text-white text-lg mr-1 w-auto mt-3 md:w-[20rem] lg:w-[20rem] xl:w-[30rem] 2xl:w-[40rem]">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quam, maxime eum. Sequi, distinctio laudantium voluptatem fuga unde excepturi magnam reiciendis, quisquam, repudiandae similique impedit mollitia beatae odio. Ab, assumenda error.</p>
      <a href="login" class="px-3 items-center text-center mt-5 w-64 rounded-[6.5px] text-black bg-white py-2">
        <span class="text-black text-font font-bold text-lg">More İnfo</span>
      </a>
    </div>
       
  </div>
    <div class="h-0.5 w-[10rem] sm:w-[40rem] mt-5  bg-[#444649]"></div>
  <div  class="lg:bg-gradient-to-r bg-gradient-to-b py-3 flex lg:flex-row flex-col items-center lg:justify-end justify-center px-3 mt-5 lg:h-96 rounded-[6.5px] w-full from-[#18191c] to-[#202225]">
    <img data-aos="fade-up" src={slash} class="lg:absolute pointer-events-none mt-3 lg:h-72 h-52 lg:left-0 xl:left-0 2xl:left-20 mr-5" alt="">
    <div data-aos="fade-up" class="flex lg:text-end text-center items-center lg:items-end flex-col">
      <h2 class="text-font text-end mr-4 mt-10 text-[#afafaf]">Features</h2>
      <h1 class="text-font text-white font-extrabold text-4xl mr-4">And More, More</h1>
      <p class="text-font text-white text-lg mr-1 w-auto mt-3 md:w-[20rem] lg:w-[20rem] xl:w-[30rem] 2xl:w-[40rem]">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quam, maxime eum. Sequi, distinctio laudantium voluptatem fuga unde excepturi magnam reiciendis, quisquam, repudiandae similique impedit mollitia beatae odio. Ab, assumenda error.</p>
      <a href="login" class="px-3 items-center text-center mt-5 w-64 rounded-[6.5px] text-black bg-white py-2">
        <span class="text-black text-font font-bold text-lg">More İnfo</span>
      </a>
    </div>
       
  </div>
  <div class="h-0.5 w-[10rem] sm:w-[40rem]  bg-[#444649]"></div>
</div>
<div class="flex items-center text-start bg-[#202225] flex-col h-96">
  <span class="text-font text-[#afafaf] text-xl">Features</span>
  <h1 class="text-white text-font font-extrabold text-5xl">Leaderboards</h1>
    <img data-aos="fade-up" src={leader} class="absolute object-cover w-auto h-[40rem] mb-5" alt="">
   <p class="text-font absolute mt-[45rem] text-xl text-white 2xl:w-[80rem] px-2 break-words text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic architecto unde placeat sint laudantium veniam quas, enim sit veritatis ullam harum ducimus asperiores delectus alias optio? Temporibus corporis odio fugiat! Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sint voluptatibus delectus, tempore excepturi maiores enim quisquam fugit ab temporibus aspernatur magnam cum eius quo nesciunt iure ea facere deserunt voluptate.</p>   
   <div class="h-0.5 w-[10rem] sm:w-[40rem] sm:mt-[30rem] mt-[50rem] flex justify-center items-center bg-[#444649]"></div>

  </div>

<h1 class="text-white text-center sm:mt-[30rem] mt-[20rem]  text-font font-extrabold text-5xl">Statistics</h1>
<div class="bg-[#18191c] justify-center items-center  mt-5 flex flex-wrap gap-20 w-full sm:py-0 py-5 h-auto sm:h-52 sm:mt-5">
  <div class="flex items space-y-2 items-center flex-col">
    <span class="text-font font-extrabold text-xl text-[#afafaf]">Total</span>
    <h1 class="text-font text-5xl text-white font-extrabold">500+</h1>
    <span class="text-font font-extrabold text-xl text-[#afafaf]">Server</span>
  </div>
  <div class="flex items space-y-2 items-center flex-col">
    <span class="text-font font-extrabold text-xl text-[#afafaf]">Total</span>
    <h1 class="text-font text-5xl text-white font-extrabold">500+</h1>
    <span class="text-font font-extrabold text-xl text-[#afafaf]">Server</span>
  </div>
  <div class="flex items space-y-2 items-center flex-col">
    <span class="text-font font-extrabold text-xl text-[#afafaf]">Total</span>
    <h1 class="text-font text-5xl text-white font-extrabold">500+</h1>
    <span class="text-font font-extrabold text-xl text-[#afafaf]">Server</span>
  </div>
</div>
<div class="min-h-screen bg-[#202225]">

</div>


