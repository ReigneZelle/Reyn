<template>
    <div class="container">
    <div class="q-pa-md row items-start q-gutter-md" style="height: 180px;">
      <div class="q-pa-md q-gutter-sm"> 
        <h2 class="button-text"> Discover Motivating Online Courses</h2>
    <q-btn outline rounded color="primary" label="featured" />
    <q-btn outline rounded color="primary" label="category" />
    <q-btn outline rounded color="primary" label="category" />
    <q-btn outline rounded color="primary" label="category" />
    <q-btn outline rounded color="primary" label="category" /> 
    <q-btn outline rounded color="primary" label="category" /> <br>
    <q-btn outline rounded color="primary" label="category" />
    <q-btn outline rounded color="primary" label="category" />
    <q-btn outline rounded color="primary" label="category" />
    <q-btn outline rounded color="primary" label="category" />
  </div>
  </div>
  </div>

  <div class="q-pa-md col items-start q-gutter-md">
    <q-card class="my-card">
      <img src="https://cdn.quasar.dev/img/mountains.jpg">

      <q-card-section>
        <div class="text-h6">Our Changing Planet</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>
    </q-card>
    </div>


</template>

<style>
    .container {
    height: 100vh;
    overflow-y: auto;
}

.button-text {
  margin-left: 50px;
  text-align: center;
}

.my-card {
    max-width: 100px;
    max-height: 100px;
}

</style>