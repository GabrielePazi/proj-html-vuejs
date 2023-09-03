<script>
export default {

}
</script>

<template>
  <section class="my-4">
    <div class="container-fluid position-relative h-100 p-0">
      <div class="overlay position-absolute w-100 h-100  text-white">
        <div class="banner-overlay text-center position-absolute" style="width: 350px;">
          <h5 class="green-primary fw-bolder">COMING SOON MOVIES</h5>
          <h2 class="display-2">MAX STILL</h2>

          <div class="new-movie-actors p-2">
            <h5 class="fs-5 fw-bolder">JON PLAYER <span class="green-primary">&</span> EMILY ROSE</h5>
          </div>

          <!-- countdown -->
          <div class="d-flex justify-content-center gap-3 p-3 w-100 fw-bolder">
            <div class="green-primary">
              <div class="square d-flex justify-content-center align-items-center">
                1111
              </div>
              Days
            </div>
            <div style="color: rgb(255, 168, 0)!important;">
              <div class="square d-flex justify-content-center align-items-center">
                22
              </div>
              Hours
            </div>
            <div style="color: rgb(111, 255, 243)!important;">
              <div class="square d-flex justify-content-center align-items-center">
                33
              </div>
              Minutes
            </div>
            <div style="color: rgb(206, 219, 56)!important;">
              <div class="square d-flex justify-content-center align-items-center">
                44
              </div>
              Seconds
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;
@use '../styles/partials/utilities.scss' as *;

section {
  background-image: url(../assets/imgs/coming-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: 50%;
  height: 600px;
}

.overlay {
  background-color: rgba(0, 0, 0, 0.4);

  .banner-overlay {
    left: 50%;
    top: 50%;
    transform: translateY(-50%);
  }

  .new-movie-actors {
    background-color: $bg-header;
  }

  .square {
    width: 60px;
    aspect-ratio: 1/1;
    background-color: $bg-header;
  }
}
</style>