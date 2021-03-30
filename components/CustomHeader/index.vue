<template>
  <div class="w-full h-screen flex bg-gray-200">
    <Navbar class="fixed bg-gray-400 top-0 mt-10" />
    <div
    class="w-full h-screen flex flex-col justify-center items-center"
    style="width: 50%;">
      <div class="w-24 ml-25">
      </div>
          <h1
          class="max-w-xl font-regular m-2 font-bold text-2xl text-blue-800">
          Otimize seu tempo encontrando a melhor transportadora para sua carga agora.
          </h1>
          <span
          class="max-w-xl mt-6 font-regular text-md text-blue-800">
            Mantenha o foco no seu negócio e nós encontraremos a melhor opção de transportadora para a sua carga.
          </span>
    </div>
    <div
    class="w-full h-screen flex flex-col justify-center items-center"
    style="width: 50%;">
    <h2 class="text-center text-blue-8--"> calc quasar here </h2>
    </div>
  </div>
</template>

<script>
import Navbar from '../Navbar'

export default {
  components: {
    Navbar
  }
}
</script>
