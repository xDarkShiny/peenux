<script>
  import logo from "../assets/onlylogo.svg"
</script>

<style>
  .text-font {
    font-family: 'Inter', sans-serif;
  }
</style>

<div class="w-full flex py-4 px-3 z-40 fixed  inset-x-0 top-0 items-center justify-center h-auto">
  <div class="w-auto outline-none focus:outline-none mr-1 mb-1 ease-linear transition-all duration-150 h-20 flex px-8 items-center bg-black justify-between space-x-32 rounded-full cursor-pointer backdrop-blur-xl shadow-xl bg-opacity-50">
      <img src={logo} class="h-10" alt="">
        <div class="md:block hidden">
          <div class="flex space-x-5 lg:space-x-7">
            <a class="text-font text-white font-bold underline underline-offset-4 text-xl" href="commands">Commands</a>
            <a class="text-font text-white font-bold underline underline-offset-4 text-xl" href="commands">Store</a>
            <a class="text-font text-white font-bold underline underline-offset-4 text-xl" href="commands">About</a>
            <a class="text-font text-white font-bold underline underline-offset-4 text-xl" href="commands">FAQ</a>
          </div>
        </div>
      <div class="md:block hidden">
        <a href="login" class="bg-[#404eed] text-style hover:ring-4 text-white font-bold text-xl px-10 py-3 rounded-full shadow hover:shadow-lg outline-none focus:outline-none mr-1 mb-1 ease-linear transition-all duration-150">
          <span class="text-white text-font font-bold ">Login</span>
        </a>
      </div>
      <div class="block md:hidden">
        <div class="bg-[#404eed] ml-5 text-style text-white font-bold text-xl px-5 py-2 rounded-full shadow hover:shadow-lg outline-none focus:outline-none mr-1 mb-1 ease-linear transition-all duration-150">
          <i class="fa-duotone text-2xl fa-bars"></i>
        </div>
      </div>
  </div>
</div> 