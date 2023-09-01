<script>
export default {

}
</script>

<template>
  <!-- Freccia a sinistra -->
  <div class="jumbotron container-fluid w-100 d-flex">
    <div class="h-100 d-flex align-items-center text-white">
      <button class="btn-slider bg-transparent border-0 rounded-circle p-2" style="aspect-ratio: 1/1;">
        <i class="fa-solid fa-chevron-left text-white hover-green fs-4 px-2"></i>
      </button>
    </div>

    <!-- elemento al centro -->
    <div class="flex-grow-1 text-white d-flex align-items-center content-container">
      <div class="content text-center">
        <h6>Welcome To Our Movie Site</h6>
        <p class="display-5" style="letter-spacing: -2px;">OUR SPECIAL <span class="green-primary">MOVIES</span></p>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptate mollitia libero nulla rem perferendis
          cumque
          quibusdam id in facilis iusto laboriosam reprehenderit, quos molestias aperiam minima inventore quas veniam
          placeat.</p>
        <button class="btn read-me-btn text-white rounded-5 px-3 bg-green-primary fw-semibold">Read More</button>
      </div>
    </div>

    <!-- freccia a sinistra -->
    <div class="h-100 d-flex align-items-center text-white">
      <button class="btn-slider bg-transparent border-0 rounded-circle p-2">
        <i class="fa-solid fa-chevron-right text-white hover-green fs-4 py-1 px-2"></i>
      </button>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;
@use '../styles/partials/utilities.scss' as *;

.jumbotron {
  height: 600px;
  background-image: url(../assets/imgs/slider-1536x520.jpg);
  background-size: cover;
  background-repeat: no-repeat;

  .content-container {
    margin-left: 45%
  }

  .content {
    width: 470px;
  }
}

.hover-green {
  transition: color .5s;

  &:hover {
    color: $green-primary !important;
  }
}

.btn-slider {

  &:hover {
    background-color: black !important;
  }
}

.read-me-btn {
  transition: background-color, color 1s;

  &:hover {
    background-color: white;
    color: black !important;
  }
}
</style>