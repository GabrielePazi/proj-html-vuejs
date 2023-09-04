<script>
export default {
  data() {
    return {
      bgImg: "first-bg-img"
    }
  },
  methods: {
    changeJumboBackground() {
      if (this.bgImg == "second-bg-img") {
        this.bgImg = "first-bg-img"
      } else {
        this.bgImg = "second-bg-img"
      }
    }
  },
}
</script>

<template>
  <!-- Freccia a sinistra -->
  <div class="jumbotron container-fluid w-100 d-flex p-0 position-relative">

    <!-- sfondo -->
    <div class="h-100 w-100" :class="bgImg"></div>

    <!-- overlay -->
    <div class="position-absolute d-flex w-100 h-100 ps-2">
      <div class="h-100 d-flex align-items-center text-white">
        <button @click="changeJumboBackground" class="btn-slider bg-transparent border-0 rounded-circle p-2">
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
      <div class="h-100 d-flex align-items-center text-white pe-2">
        <button @click="changeJumboBackground" class="btn-slider bg-transparent border-0 rounded-circle p-2">
          <i class="fa-solid fa-chevron-right text-white hover-green fs-4 py-1 px-2"></i>
        </button>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;
@use '../styles/partials/utilities.scss' as *;

.jumbotron {
  height: 600px;

  .first-bg-img {
    background-image: url(../assets/imgs/slider-1536x520.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    animation-name: deopacifier;
    animation-duration: 1s;

    @keyframes deopacifier {
      0% {
        opacity: 0;
      }

      100% {
        opacity: 1;
      }
    }
  }

  .second-bg-img {
    background-image: url(../assets/imgs/slider-2-1536x520.jpg);
    background-repeat: no-repeat;
    background-size: cover;
  }

  .content-container {
    margin-left: 45%;
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
  aspect-ratio: 1/1;

  &:hover {
    background-color: black !important;
  }
}

.read-me-btn {
  transition: background-color .7s, color .7s;

  &:hover {
    background-color: white;
    color: black !important;
  }
}
</style>