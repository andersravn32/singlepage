<script setup>
import bg from "../assets/img/topo.svg";
</script>

<template>
  <section id="hero" :style="{ 'background-image': `url(${bg})` }">
    <div class="flex flex-col text-center max-w-xl">
      <h1 class="font-bold text-4xl">En <span class="text-violet-600">hjemmeside</span> er ikke længere blot en hjemmeside.</h1>
      <p>Hos Singlepage Development udvikler vi speciallavede webløsninger til små og mellemstore virksomheder i Danmark</p>
    </div>
  </section>
</template>

<style>
#hero {
  @apply min-h-screen w-full bg-contain bg-repeat flex items-center justify-center;
  animation: 60s linear infinite bg;
}

@keyframes bg{
    0%{
        background-position: 0% 0%;
    }

    100%{
        background-position: 100% 100%;
    }
}
</style>
