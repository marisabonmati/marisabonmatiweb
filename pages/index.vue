<template>
  <div class="container">
    <Navhome />
    <div class="d-flex align-items-center justify-content-center">
      <div>
        <button
          type="button"
          class="btn w-100 links mb-5"
        >
          <font-awesome-icon class="icon-fontawesome fa-5x" icon="video" />
        </button>
        <button
          type="button"
          class="btn w-100 links my-5"
        >
          <font-awesome-icon class="icon-fontawesome fa-5x" icon="heart" />
        </button>
        <button
          type="button"
          class="btn w-100 links mt-5"
        >
          <font-awesome-icon class="icon-fontawesome fa-5x" icon="at" />
        </button>
      </div>
      <div>
        <Marisaimg />
      </div>
      <div>
        <button
          type="button"
          class="btn w-100 links mb-5"
        >
          <font-awesome-icon class="icon-fontawesome fa-5x" icon="briefcase" />
        </button>
        <button
          type="button"
          class="btn w-100 links my-5"
        >
          <font-awesome-icon class="icon-fontawesome fa-5x" icon="graduation-cap" />
        </button>
        <button
          type="button"
          class="btn w-100 links mt-5"
        >
          <font-awesome-icon class="icon-fontawesome fa-5x" icon="address-card" />
        </button>
      </div>
    </div>
    <h1 class="title mt-3 d-flex justify-content-center">María Isabel Bonmatí Mendoza</h1>
  </div>
</template>

<script>
export default {};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
*/

.icon-fontawesome{
  color: #5e0000;
}

.icon-fontawesome:hover{
  font-size: 7rem;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: inline-block;
  font-weight: 300;
  font-size: 50px;
  color: #5e0000;
  letter-spacing: 1px;
}

.links {
  animation: 3s appear;
}
</style>
