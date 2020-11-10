<template>
  <div class="container">
    <Navhome />
    <div class="d-flex align-items-center justify-content-center">
      <div>
        <button
          type="button"
          class="btn btn-primary w-100 links links-left mb-5"
        >
          <font-awesome-icon icon="user-secret" />Primary
        </button>
        <button
          type="button"
          class="btn btn-primary w-100 links links-left my-5"
        >
          Primary
        </button>
        <button
          type="button"
          class="btn btn-primary w-100 links links-left mt-5"
        >
          Primary
        </button>
      </div>
      <div>
        <Marisaimg />
      </div>
      <div>
        <button
          type="button"
          class="btn btn-primary w-100 links links-right mb-5"
        >
          Primary
        </button>
        <button
          type="button"
          class="btn btn-primary w-100 links links-right my-5"
        >
          Primary
        </button>
        <button
          type="button"
          class="btn btn-primary w-100 links links-right mt-5"
        >
          Primary
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
