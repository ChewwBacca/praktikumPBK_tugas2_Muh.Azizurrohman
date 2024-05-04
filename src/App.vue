<template>
  <div class="container">
    <div class="konten">
      <h1 >MUH. AZIZURROHMAN</h1>
  
     <input type="text" placeholder="masukan inputan" v-model="input" >
      <p :class='judul' >{{ input }}</p>

    </div>
  </div>

  
  </template>
  
  <script setup>
  import { ref } from 'vue';
  
  const judul = ref('title')
  const input = ref("")
  </script>
  
  <style scoped>
  .title{
    color: white;
    text-transform: uppercase;
  }
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.vue:hover {
    filter: drop-shadow(0 0 2em #42b883aa);
  }
  h1 {
    color: white;
  }
  input {
    border-radius: 10px;
    width: 200px;
    height: 30px;
  }
  </style>
  