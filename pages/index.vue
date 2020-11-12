<template>
  <div class="body">
    <div class="container">
      <Navhome />
      <div class="d-flex align-items-center justify-content-center">
        <div>
          <a href="" class="btn w-100 links mb-5">
            <font-awesome-icon class="icon-fontawesome fa-5x" icon="video" />
          </a>
          <a href="" class="btn w-100 links my-5">
            <font-awesome-icon class="icon-fontawesome fa-5x" icon="heart" />
          </a>
          <a href="" class="btn w-100 links mt-5">
            <font-awesome-icon class="icon-fontawesome fa-5x" icon="at" />
          </a>
        </div>
        <div>
          <Marisaimg />
        </div>
        <div>
          <a href="work.vue" class="btn w-100 links mb-5">
            <font-awesome-icon
              class="icon-fontawesome fa-5x"
              icon="briefcase"
            />
          </a>
          <a href="" class="btn w-100 links my-5">
            <font-awesome-icon
              class="icon-fontawesome fa-5x"
              icon="graduation-cap"
            />
          </a>
          <a href="" class="btn w-100 links mt-5">
            <font-awesome-icon
              class="icon-fontawesome fa-5x"
              icon="address-card"
            />
          </a>
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
export default {};
</script>

<style>
.body {
  background-image: url("../static/background.jpg");
  background-size: cover;
}

.icon-fontawesome {
  color: #5e0000;
}

.icon-fontawesome:hover {
  font-size: 7rem;
}

.links {
  animation: 3s appear;
}
</style>
