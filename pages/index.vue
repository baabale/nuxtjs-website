<script setup lang="ts">
</script>

<template>
  <div class="container">
    <div class="info">
      <img
        class="avatar"
        src="https://baabale.com/wp-content/uploads/2021/11/New-Project.png"
      />
      <h1>Abdirahman Baabale</h1>
      <p>Get ready, something cool is coming!</p>
    </div>
  </div>
</template>

<style>
* {
  margin: 0 !important;
}

/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
  .avatar {
    width: 50%;
  }
}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
  .avatar {
    width: 50%;
  }
}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
  .avatar {
    width: 50%;
  }
}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
  .avatar {
    width: 70%;
  }
}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
  .avatar {
    width: 70%;
  }
}

.container {
  height: 100vh;
  width: 100vw;
  background: rgba(30, 136, 229, 0.15);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.info {
  text-align: center;
  font-family: "Helvetica Neue", Arial, sans-serif;
}
.container .info h1 {
  font-size: 2.5rem;
}
</style>

