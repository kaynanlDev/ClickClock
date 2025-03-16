<script setup>
import HeaderData from './components/HeaderData.vue';
import MainData from './components/MainData.vue';
</script>

<template>
  <div class="container">
    <HeaderData />
    <MainData />
  </div>
</template>

<style lang="scss">

 *{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
 }
 body{

  max-width: 1220px;
  width: 100%;
  height: 100vh;
  padding: 0 24px;
  background-color: hsl(0, 0%, 94%);
  display: flex;
  align-items: center;
  justify-content: center;
 }

 .container{
        width: 800px;
        height: 400px;
        padding: 24px;
        background-color: hsl(0, 0%, 100%);
        margin: 0 auto;
        border-radius: 16px;
        box-shadow: 5px 6px 20px rgba(0, 0, 0, 0.082);
 }
 
</style>
