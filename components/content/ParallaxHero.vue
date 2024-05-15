<template>
  <div class="bg-fixed bg-center h-96" style="background-image: url('https://images.unsplash.com/photo-1465848059293-208e11dfea17?q=80&w=1932&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D')">
    <slot name="navbar" />
    <div class="h-full place-content-center">
      <div class="h-fit place-content-center bg-sky-800/50 py-16 ring-offset-1 ring-offset-white ring-8 ring-slate-800/25">
        <h1 class="text-center text-white text-5xl font-extralight">Church Minor</h1>
        <hr class="mx-4 sm:mx-16 my-4" />
        <p class="text-center text-white text-xl font-light">Liturgical music resources for small parishes.</p>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>

</script>

<style lang="scss">

</style>