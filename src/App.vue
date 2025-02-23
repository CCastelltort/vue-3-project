<template>
  <h1>{{ message }}</h1>
  <img src="/public/img/banner_1.jpg" alt="" />
  <br />

  <button>Change image</button>

</template>

<script setup>
import { ref } from 'vue'

let message = 'Hello, v-bind!'



</script>

<style scoped>
img {
  max-width: 300px;
}

.active {
  color: green;
}

.inactive {
  color: red;
  text-decoration: line-through;
}

.center {
  text-align: center;
}
</style>