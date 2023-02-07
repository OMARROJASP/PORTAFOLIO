<script setup>

</script>

<template>
      <nav class="py-10 px-10 flex flex-col text-center">
        <div class="sm:flex sm:justify-between ">
          <div>
          <RouterLink  class=" text-purple-500 font-semibold text-2xl" to="/">MAXIMO OMAR</RouterLink>
        </div>
        <div class="flex pt-10"> 
          <RouterLink class="mx-5" to="/">Quien soy</RouterLink>
          <RouterLink class="mx-5" to="/">Proyectos</RouterLink>
          <RouterLink class="mx-5" to="/">acerca de mi</RouterLink>
        </div>
        </div>
        
      </nav>


  <RouterView />
</template>


