<template>
  <div id="gallery" class="carousel slide" data-bs-ride="carousel">

    <div class="carousel-inner">
      <div class="carousel-item active" data-bs-interval="1000">
        <img src="../../assets/carousel/img1.jpg" class="d-block w-100" alt="...">
        <a href="https://unsplash.com/pt-br/fotografias/interior-da-igreja-GxbFfu6yRN0" target="_blank">
          Brandon Morgan, 2016
        </a>
      </div>

      <div class="carousel-item" data-bs-interval="1000">
        <img src="../../assets/carousel/img2.jpg" class="d-block w-100" alt="...">
        <a href="https://unsplash.com/pt-br/fotografias/bancos-da-igreja-de-madeira-na-igreja-go_b8XV21f0"
          target="_blank">
          Matheus Campos Felipe, 2019
        </a>
      </div>

      <div class="carousel-item" data-bs-interval="1000">
        <img src="../../assets/carousel/img3.jpg" class="d-block w-100" alt="...">
        <a href="https://unsplash.com/pt-br/fotografias/foto-em-tons-de-cinza-da-mulher-com-flor-em-sua-estatua-da-cabeca-yy6fGEvnoMo"
          target="_blank">
          Marites Allen, 2020
        </a>
      </div>

      <div class="carousel-item" data-bs-interval="1000">
        <img src="../../assets/carousel/img4.jpg" class="d-block w-100" alt="...">
        <a href="https://unsplash.com/pt-br/fotografias/decoracao-de-parede-de-jesus-cristo-vAkaLvqVFmc"
          target="_blank">
          Josh Applegate, 2020
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'GalleryPhotos'
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Galada&display=swap');

.carousel-item {
  display: flex;
  position: relative;
  height: 90%;
}

.carousel-item img {
  display: inline-block;
  margin: 0;
  max-height: 2500px;
}

.carousel-item a {
  position: absolute;
  bottom: 0px;
  right: 0;

  color: white;
  text-decoration: none;
  font-family: 'Galada';

  padding: 3vmin;
  border: 40px;
  background-color: rgba(0, 0, 0, 0.35);
  box-shadow: 0 0 40px rgba(0, 0, 0, 0.2);

  font-size: large;

  margin: 0 !important;
}
</style>