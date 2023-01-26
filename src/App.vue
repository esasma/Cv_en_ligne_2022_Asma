<template>
  <header>
    <div class="mt-10">
      <router-link to="/"
        class=" ml-80 m-10 uppercase bg-transparent hover:bg-black text-black font-semibold hover:text-white py-2 px-4 border-2 border-black hover:border-transparent rounded">
        Français
      </router-link>


      <router-link to="/ResumeView"
        class="m-10 uppercase bg-transparent hover:bg-black text-black font-semibold hover:text-white py-2 px-4 border-2 border-black hover:border-transparent rounded ">
        Englsih
      </router-link>
    </div>
  </header>


  <!-- Affiche les pages -->
  <Suspense>
    <router-view class="" />
  </Suspense>
</template>

<script setup lang="ts">

</script>
