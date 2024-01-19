<template>
  <div id="quote-box">
    <div id="quote">
      "A arte é capaz de expressar e tornar visível a necessidade do homem de ir além do que se vê, manifesta a sede e a
      busca pelo infinito. Na verdade, é como uma porta aberta para o infinito, para uma beleza e uma verdade que vão para
      além do cotidiano. E uma obra de arte pode abrir os olhos da mente e do coração, direcionando-os para o alto."
    </div>
    <div id="author">
      - São João Paulo II
    </div>
  </div>
</template>

<script>
export default {
  name: 'StartQuote'
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Galada&display=swap');

#quote-box {
  color: white;
  background-color: black;
  padding: 1vh 4vw;

  font-family: 'Galada';
  font-size: 0.8rem;
}
</style>