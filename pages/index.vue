<template>
  <div class="grand-father d-flex">
    <div class="father d-flex">
      <div class="container">
        <div class="d-flex align-items-center justify-content-center">
          <div class="icons-group">
            <a href="" class="btn w-100 links">
              <font-awesome-icon class="icon-fontawesome icon-video fa-5x" icon="video" />
            </a>
            <a href="" class="btn w-100 links">
              <font-awesome-icon class="icon-fontawesome fa-5x" icon="heart" />
            </a>
            <a href="" class="btn w-100 links">
              <font-awesome-icon class="icon-fontawesome icon-at fa-5x" icon="at" />
            </a>
          </div>
          <div>
            <Marisaimg />
          </div>
          <div class="icons-group">
            <a href="work.vue" class="btn w-100 links">
              <NuxtLink to="work.vue">
                <font-awesome-icon
                  class="icon-fontawesome icon-briefcase fa-5x"
                  icon="briefcase"
                />
              </NuxtLink>
            </a>
            <a href="" class="btn w-100 links">
              <font-awesome-icon
                class="icon-fontawesome fa-5x"
                icon="graduation-cap"
              />
            </a>
            <a href="" class="btn w-100 links">
              <font-awesome-icon
                class="icon-fontawesome icon-address fa-5x"
                icon="address-card"
              />
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.grand-father {
  min-height: 100vh;
  flex-direction: column;
}
.father {
  align-items: center;
  flex: 1;
}

.icons-group {
  flex: 1;
}

.icon-fontawesome {
  color: #5e0000;
}

.icon-fontawesome:hover {
  font-size: 7rem;
}

.icon-video svg{
  margin-bottom: 200px;
}

.icon-at{
  margin-bottom: -200px;
}

.links {
  animation: 3s appear;
  position: relative;
}

.links svg {
  position: absolute;
  bottom: 0;
  right: 0;
  left: 0;
  margin: 0 auto;
}
</style>
