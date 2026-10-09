<script setup>
import { ref } from 'vue'
import heroImg from '../assets/hero.png'
import viteLogo from '../assets/vite.svg'
import vueLogo from '../assets/vue.svg'
import trainavif from '../assets/train.avif'
const count = ref(0)
</script>

<template>
  <section id="center">
    <div class="hero">
      
      <img :src="trainavif" class="train" alt="Train logo" />
    </div>
    <div>
      <h1>Welcome to the best counter over</h1>

    </div>
    <button type="button" class="counter" @click="count+=1000">
      speed of train is {{ count }} miles per second
    </button>
  </section>

  <div class="ticks"></div>

  <section id="next-steps">
    <div id="docs">
      
      
      
      <h2>Connect with ME isai macias </h2>
      <p>This application is built with Vite and Vue. On second thought dont contact me</p>
      
    </div>
  </section>

  <div class="ticks"></div>
  <section id="spacer"></section>
</template>
