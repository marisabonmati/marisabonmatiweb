<template>
    <img
      class="marisa-img"
      src="../static/marisa.jpeg"
      alt="Foto Marisa Bonmatí"
    />
</template>

<style>
.marisa-img {
  animation: 1s appear;
  display: block;
  margin: 0 auto;
  width: 30em;
  padding: 2rem;
  box-shadow: 0 0 15px #ddd;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>
