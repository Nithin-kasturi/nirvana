<template>
  <div class="flex bg-black h-screen w-screen">
    <div class="flex flex-col gap-4 md:flex-row">
    <div class="z-30 box h-full w-full md:my-7 md:w-1/2 lg:my-9 lg:w-[80%] my-5">
      <div class="relative z-50 m-4">
        <img class="w-full rounded-3xl md:h-[400px] lg:h-[200px]" src="../assets/images.jpg"/>
        <div class="-mt-8 relative z-50 pl-6 rounded-xl md:-mt-20 lg:-mt-24 md:pl-20 lg:pl-30">
          <img class="rounded-xl md:rounded-3xl border-gray-500 border-[2px] md:border-[10px] h-[80px] w-[80px] md:h-[150px] md:w-[150px] lg:h-[200px] lg:w-[200px]" src="../assets/profilePic.jpg"/>
        </div>
        <div class="mt-1 pl-4 flex gap-2 items-center">
          <h1 class="text-sm font-mono text-white md:text-3xl lg:text-4xl">0xFSgdA</h1>
          <img src="../assets/verified.jpg" class="md:h-11 md:w-11 lg:h-14 lg:w-14 h-7 w-7">
        </div>
        <div class="w-full bg-gray-600 h-[1px] mt-2">
      </div>
      <div class="md:px-3 md:py-4 flex flex-col md:gap-6 lg:px-4 lg:py-5">
        <div class="h-screen md:h-full">
          <p class="text-gray-400 text-sm md:font-bold md:text-xl">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi mollitia repellat officiis enim distinctio nam pariatur dicta asperiores rem. Aliquam, nostrum obcaecati! Ratione molestiae, facere aperiam eum maxime beatae! Officia.</p>
        </div>
        <div class="">
          <i class="pi pi-linkedin text-white mr-6 md:text-2xl text-sm"></i>
          <i class="pi pi-twitter text-white mr-6 md:text-2xl text-sm" ></i>
          <i class="pi pi-instagram text-white mr-6 md:text-2xl text-sm"></i>
        </div>
        
      </div>
      </div>
    </div>
    <div class="box h-1/2 w-full md:w-1/2 lg:my-9 md:my-7 z-30">
      <div class="h-[50px] w-[150px] lg:h-[75px] lg:w-[200px] lg: relative z-50 m-2 md:m-6 bg-zinc-800 rounded-full flex items-center justify-center">
        <h1 class="text-white text-sm md:text-lg lg:xl">Resume</h1>
      </div>
      <div class="text-white relative z-50 h-4 md:h-10 w-4 md:w-10 rounded-full bg-zinc-700 flex items-center justify-center -mt-5 ml-36 md:-mt-11 md:ml-72 lg:ml-48">
        <p class="md:font-bold text-sm md:text-2xl">+</p>
      </div>
      <div class="relative z-50 p-1 md:p-10 flex justify-evenly mt-5">
          <i class="pi pi-linkedin text-white md:text-4xl lg:text-5xl text-sm" ></i>
          <i class="pi pi-twitter text-white md:text-4xl  lg:text-5xl text-sm"></i>
          <i class="pi pi-instagram text-white md:text-4xl lg:text-5xl text-sm" ></i>
        </div>

     </div>
    </div>
    
  </div>
  <div class="w-screen h-[50px] md:h-[100px] bg-black flex my-2 md:my-6 lg:mt-12">
    <div class="rounded-full border-zinc-500 border-2 h-full w-full flex justify-between">
      <div>
        <i class="pi pi-cog text-white md:text-7xl text-3xl p-2" ></i>
      </div>
      <div class="w-full">
        <input type="text" placeholder="Have something in mind?" class="hover:border-2 rounded flex w-full h-full items-center justify-center bg-black text-white text-sm font-bold md:text-2xl"/> 
      </div>
      <div>
        <i class="pi pi-sign-out text-white md:text-7xl text-3xl p-2" ></i>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'HelloWorld',
}
</script>

