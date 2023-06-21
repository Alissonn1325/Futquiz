<script setup>
import { ref } from 'vue'
</script>

<template>
 <div class="barra">
    <h1>Futquiz</h1>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@300&display=swap');

.barra {
  text-align: center;
  font-size: 50px;
  border-style:groove;
  border-width: 10px;
  background-color: rgba(3,164,255,255);
  border-color: rgba(232,66,252,255);
}

.tema {
  background-color: rgb(0, 0, 0);
  padding: 20px 30px;
  color: rgb(183, 210, 219);
  border-radius: 10px;
  text-align: center;
  display: flex;
  flex-direction: column;
  width: 26%;
  margin: 0 auto;
  margin-top: 8%;
  margin-bottom: 20px;
  border-style:groove;
  box-shadow: 8px 8px 8px black;
}

h1{
  color: white;
  font-weight: bold;
  font-size: 1.5em;
  font-family: 'Roboto Condensed', sans-serif;
}
</style>
