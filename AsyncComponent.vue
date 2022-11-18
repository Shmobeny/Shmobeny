<script setup>
  import { ref } from 'vue';

  const smile = ref('^_^');
</script>

<template>
  <div class="async-complete"> {{ smile }} </div>
</template>

<style>
  .async-complete {
    position: absolute;
    top: 0%;
    left: 0%;
    padding: 20px;
    color: black;
    background-color: green;
    border-radius: 50%;
  }
</style>