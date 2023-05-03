<template>
<div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://gadgetstolive.com/wp-content/uploads/2019/09/shopping.jpeg" class="d-block w-100 h-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.pinimg.com/originals/9a/71/6f/9a716f90fc2e24079b8960168d5ea089.jpg" class="d-block w-100 h-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://th.bing.com/th/id/R.f37a30068590013910688c3489ca38da?rik=%2biCSX4SawMQiYg&pid=ImgRaw&r=0" class="d-block w-100 h-100" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Trước</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Sau</span>
  </button>
</div>
</template>
<style scoped>
    .carousel-item{
        height: 600px;
    }
</style>