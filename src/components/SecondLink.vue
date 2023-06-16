<template>
<div class="container">
<div class="card-container">
<div class="q-pa-md row items-start q-gutter-md" style="height: 180px;">
  <q-card flat class="card">
    <q-card-section>
      <div class="text-h4">Unlock Your Potential with Our <br>
        Online Learning Platform</div>
        <div class="text-h5">Explore a World of Knowledge and Advance Your<br>
        Career from Anywhere, Anytime</div>
    </q-card-section>
  </q-card>

  
  <q-card class="box" style="background: radial-gradient(circle, #35a2ff 0%, #014a88 100%)">
    <q-card-section>
      <div class="text-h3">100+</div>
      <div class="text-h5">COURSES</div>
    </q-card-section>
  </q-card>

  <q-card class="box" style="background: radial-gradient(circle, #35a2ff 0%, #014a88 100%)">
    <q-card-section>
      <div class="text-h3">1000+</div>
      <div class="text-h5">MEMBERS</div>
    </q-card-section>
  </q-card>

  <q-card class="box" style="background: radial-gradient(circle, #35a2ff 0%, #014a88 100%)">
    <q-card-section>
      <div class="text-h3">50+</div>
      <div class="text-h5">INSTRUCTORS</div>
    </q-card-section>
  </q-card>

</div>
</div>

<div class="card2-container">
<div class="q-pa-md">
  <q-card class="card2">
    <q-video src="https://www.youtube.com/embed/k3_tw44QsZQ?rel=0" />

    <q-card-section>
      <div class="text-h6">Our Changing Planet</div>
      <div class="text-subtitle2">by John Doe</div>
    </q-card-section>

    <q-card-section class="q-pt-none">  
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    </q-card-section>
  </q-card>
</div>
</div>
</div>
</template>

<style>
body{
    background-color: #b3d9ff;
}
.container {
  display: flex;
}

.card-container {
  flex: 1;
  margin-top: 18px;
  margin-left: 20px;
}

.card2-container {
  flex: 1;
  margin-top: 18px;
  margin-left: 20px;
}

.card {
  font-family: 'Times New Roman', Times, serif;
  background-color: rgb(192, 238, 238);
  margin-left: 40px;
  margin-top: 40px;
  text-align: center;
}

.card2 {
  max-width: 400px;
  max-height: fit-content;
  margin-top: 40px;
  border-radius: 8px;
  margin-bottom: 160px;
}

.box {
  max-width: 300px;
  border-radius: 20px;
  margin-left: 20px;
  margin-top: 50px;
}

.page-container {
    height: 100vh;
    overflow-y: auto;
}

.button-text {
  margin-left: 50px;
  text-align: center;
}
</style>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'SecondLink'

})
</script>