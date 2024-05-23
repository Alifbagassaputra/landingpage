<template>
<div id="carouselExampleIndicators" class="carousel slide">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://images.samsung.com/is/image/samsung/assets/id/galaxy-ai/web-galaxy-ai-1440-640.jpg?imwidth=2560" class="d-block w-100">
    </div>
    <div class="carousel-item">
      <img src="https://images.samsung.com/is/image/samsung/assets/id/homepage/main-homepage/2024/web-trade-in-tv-2024.jpg?imwidth=1366" class="d-block w-100" >
    </div>
    <div class="carousel-item">
      <img src="https://images.samsung.com/is/image/samsung/assets/id/homepage/main-homepage/2024/2024-bespoke-ai-n01-kv-pc02.jpg?imwidth=1366" class="d-block w-100">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
  </template>
  
  <script>
  export default {
    name: 'Carousel'
  }
  </script>
  

