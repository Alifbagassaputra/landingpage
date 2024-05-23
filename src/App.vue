<template>
  <div id="app">
    <Navbar />
    <Carousel />
    <div class="container mt-5">
      <div class="row">
        <Card
          title="Galaxy S24"
          description="The latest Galaxy S24 with powerful features and sleek design."
          imgUrl="https://images.samsung.com/is/image/samsung/p6pim/id/2401/gallery/id-galaxy-s24-sm-s921bzyqxid-thumb-539294568?$180_180_PNG$"
        />
        <Card
          title="Galaxy S24 Ultra"
          description="Experience the best with Galaxy S24 Ultra's cutting-edge technology."
          imgUrl="https://images.samsung.com/is/image/samsung/p6pim/id/2401/gallery/id-galaxy-s24-s928-sm-s928bztqxid-thumb-539319761?$180_180_PNG$"
        />
        <Card
          title="Galaxy Watch 4"
          description="Stay connected and track your health with Galaxy Watch 4."
          imgUrl="https://images.samsung.com/is/image/samsung/p6pim/id/2108/gallery/id-galaxy-watch4-sm-r860nzdaxse-thumb-481093234?$180_180_PNG$"
        />
      </div>
      <h2 class="text-center my-4">Additional Information</h2>
      <div class="row">
        <InfoCard
          title="Smartwatch"
          description="Smartwatch baru. Datanya sama."
          imgUrl="https://images.samsung.com/id/galaxy-watch5-pro/feature/galaxy-watch5-pro-battery-display.png" 
        />
        <InfoCard
          title="Galaxy Buds"
          description="Hear sound as it was intended, wirelessly."
          imgUrl="https://images.samsung.com/is/image/samsung/assets/id/galaxy-buds2-pro/feature/galaxy-buds2-pro-color-view-purple.jpg" 
        />
        <InfoCard
          title="Galaxy Tab"
          description="Desain terpadu. Keindahan ada pada detailnya"
          imgUrl="https://images.samsung.com/id/galaxy-tab-s9/feature/galaxy-tab-s9-visual-pc.jpg" 
        />
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Carousel from './components/Carousel.vue';
import Card from './components/Card.vue';
import InfoCard from './components/InfoCard.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Carousel,
    Card,
    InfoCard,
    Footer
  }
}
</script>

<style>
body {
  font-family: 'Arial', sans-serif;
  background-color: #f8f9fa;
  color: #333;
}

h2 {
  color: #007bff;
}

.container {
  padding: 0 15px;
}

.text-center {
  text-align: center;
}

.mb-4 {
  margin-bottom: 1.5rem;
}

.mt-5 {
  margin-top: 3rem;
}

.mt-4 {
  margin-top: 1.5rem;
}

.my-4 {
  margin-top: 1.5rem;
  margin-bottom: 1.5rem;
}

.row {
  display: flex;
  flex-wrap: wrap;
}

.card,
.info-card {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover,
.info-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

hr {
  border: none;
  border-top: 2px solid #ddd;
}
</style>
