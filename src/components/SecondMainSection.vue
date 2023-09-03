<script>
export default {

}
</script>

<template>
  <!-- SEZIONE CON VIDEO YOUTUBE -->
  <section>
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-10">

          <!-- banner -->
          <div class="new-movie-banner d-flex w-100 text-white border-bottom border-dark my-5 px-3 pt-1">
            <div>
              <h4>Movie Playlist</h4>
              <p>Lorem Ipsum is simply dummy text of the printing and typesetting</p>
            </div>

            <div class="d-flex ms-auto">
              <div class="h-100 d-flex align-items-center text-white">
                <button class="btn-slider bg-transparent border-0 rounded-circle p-2">
                  <i class="fa-solid fa-chevron-left text-white hover-green fs-4 px-2"></i>
                </button>
              </div>
              <div class="h-100 d-flex align-items-center text-white">
                <button class="btn-slider bg-transparent border-0 rounded-circle p-2">
                  <i class="fa-solid fa-chevron-right text-white hover-green fs-4 px-2"></i>
                </button>
              </div>
            </div>
          </div>

          <!-- schermata con video youtube e consigliati -->
          <div class="d-flex mb-5 gap-4">
            <div class="youtube-video position-relative text-white">
              <div class="youtube-overlay h-100 position-absolute w-100">

                <!-- titolo video e altri elementi -->
                <div class="channel-logo d-flex align-items-center gap-2 mt-2 w-100">

                  <!-- Logo del canale e titolo del video -->
                  <img class="channel-img rounded-circle mx-2" src="../assets/imgs/channels4_profile.jpg" alt="">
                  <h5 class="m-0 text-truncate video-title">Yeh Saali Aashiqui | Official Trailer | Vardhan Puri,
                    Shivaleeka Oberoi | Cherag Ruparel | 29 Nov</h5>

                  <!-- Guarda più tardi -->
                  <div class="d-flex flex-column justify-content-center align-items-center pt-1">
                    <i class="fa-solid fa-clock text-center"></i>
                    <p>Guarda...</p>
                  </div>

                  <!-- Condividi -->
                  <div class="d-flex flex-column justify-content-center align-items-center pt-1 mx-2">
                    <i class="fa-solid fa-share"></i>
                    <p>Condividi</p>
                  </div>
                </div>

                <!-- Logo Youtube -->
                <div class="position-absolute youtube-logo">
                  <img src="../assets/imgs/image (11).svg" alt="youtube-logo">
                </div>

                <!-- link a video youtube -->
                <div class="position-absolute link-youtube">
                  <button class="text-white border-0 p-2 fw-medium">
                    Guarda su <i class="fa-brands fa-youtube ms-1"></i>
                  </button>
                </div>
              </div>
            </div>

            <div class="flex-grow-1 text-white movies-list overflow-hidden">

              <div class="border-bottom border-black p-3 overflow-hidden">
                <h5>New Movie</h5>
                <p class="m-0">Playing 24</p>
              </div>

              <!-- lista scorrevole di film -->
              <div class="overflow-auto p-3 h-100">

                <!-- Primo film -->
                <div class="d-flex">
                  <img class="flex-shrink-1 movie-poster" src="../assets/imgs/2-100x100.jpg" alt="">
                  <div class="pt-1 ps-2 w-100 h-100">
                    <h6 class="hover-green fw-bolder">Quisque Auctor Movie in Struck</h6>
                    <p class="my-1" style="font-size: .8rem;">1037 Views</p>
                    <div class="d-flex justify-content-between w-100">
                      <p>February 12, 2016</p>
                      <p>2.30.00</p>
                    </div>
                  </div>
                </div>

                <!-- secondo film  -->
                <div class="d-flex">
                  <img class="flex-shrink-1 movie-poster" src="../assets/imgs/5-100x100.jpg" alt="">
                  <div class="pt-1 ps-2 w-100 h-100">
                    <h6 class="hover-green fw-bolder">Quisque Auctor Movie in Struck</h6>
                    <p class="my-1" style="font-size: .8rem;">1037 Views</p>
                    <div class="d-flex justify-content-between w-100">
                      <p>February 12, 2016</p>
                      <p>2.30.00</p>
                    </div>
                  </div>
                </div>

                <!-- terzo film  -->
                <div class="d-flex">
                  <img class="flex-shrink-1 movie-poster" src="../assets/imgs/3-100x100.jpg" alt="">
                  <div class="pt-1 ps-2 w-100 h-100">
                    <h6 class="hover-green fw-bolder">Quisque Auctor Movie in Struck</h6>
                    <p class="my-1" style="font-size: .8rem;">1037 Views</p>
                    <div class="d-flex justify-content-between w-100">
                      <p>February 12, 2016</p>
                      <p>2.30.00</p>
                    </div>
                  </div>
                </div>

                <!-- quarto film  -->
                <div class="d-flex">
                  <img class="flex-shrink-1 movie-poster" src="../assets/imgs/3-1-100x100.jpg" alt="">
                  <div class="pt-1 ps-2 w-100 h-100">
                    <h6 class="hover-green fw-bolder">Quisque Auctor Movie in Struck</h6>
                    <p class="my-1" style="font-size: .8rem;">1037 Views</p>
                    <div class="d-flex justify-content-between w-100">
                      <p>February 12, 2016</p>
                      <p>2.30.00</p>
                    </div>
                  </div>
                </div>

                <!-- quinto film  -->
                <div class="d-flex">
                  <img class="flex-shrink-1 movie-poster" src="../assets/imgs/2-1-100x100 (1).jpg" alt="">
                  <div class="pt-1 ps-2 w-100 h-100">
                    <h6 class="hover-green fw-bolder">Quisque Auctor Movie in Struck</h6>
                    <p class="my-1" style="font-size: .8rem;">1037 Views</p>
                    <div class="d-flex justify-content-between w-100">
                      <p>February 12, 2016</p>
                      <p>2.30.00</p>
                    </div>
                  </div>
                </div>

                <!-- sesto film  -->
                <div class="d-flex">
                  <img class="flex-shrink-1 movie-poster" src="../assets/imgs/4-1-100x100.jpg" alt="">
                  <div class="pt-1 ps-2 w-100 h-100">
                    <h6 class="hover-green fw-bolder">Quisque Auctor Movie in Struck</h6>
                    <p class="my-1" style="font-size: .8rem;">1037 Views</p>
                    <div class="d-flex justify-content-between w-100">
                      <p>February 12, 2016</p>
                      <p>2.30.00</p>
                    </div>
                  </div>
                </div>

                <!-- settimo film  -->
                <div class="d-flex">
                  <img class="flex-shrink-1 movie-poster" src="../assets/imgs/6-100x100.jpg" alt="">
                  <div class="pt-1 ps-2 w-100 h-100">
                    <h6 class="hover-green fw-bolder">Quisque Auctor Movie in Struck</h6>
                    <p class="my-1" style="font-size: .8rem;">1037 Views</p>
                    <div class="d-flex justify-content-between w-100">
                      <p>February 12, 2016</p>
                      <p>2.30.00</p>
                    </div>
                  </div>
                </div>

                <!-- ottavo film  -->
                <div class="d-flex">
                  <img class="flex-shrink-1 movie-poster" src="../assets/imgs/5-150x150 (1).jpg" alt="">
                  <div class="pt-1 ps-2 w-100 h-100">
                    <h6 class="hover-green fw-bolder">Quisque Auctor Movie in Struck</h6>
                    <p class="my-1" style="font-size: .8rem;">1037 Views</p>
                    <div class="d-flex justify-content-between w-100">
                      <p>February 12, 2016</p>
                      <p>2.30.00</p>
                    </div>
                  </div>
                </div>

                <!-- nono film  -->
                <div class="d-flex">
                  <img class="flex-shrink-1 movie-poster" src="../assets/imgs/1-2-100x100.jpg" alt="">
                  <div class="pt-1 ps-2 w-100 h-100">
                    <h6 class="hover-green fw-bolder">Quisque Auctor Movie in Struck</h6>
                    <p class="my-1" style="font-size: .8rem;">1037 Views</p>
                    <div class="d-flex justify-content-between w-100">
                      <p>February 12, 2016</p>
                      <p>2.30.00</p>
                    </div>
                  </div>
                </div>

                <!-- decimo film  -->
                <div class="d-flex" style="margin-bottom: 100px;">
                  <img class="flex-shrink-1 movie-poster" src="../assets/imgs/2-100x100.jpg" alt="">
                  <div class="pt-1 ps-2 w-100 h-100">
                    <h6 class="hover-green fw-bolder">Quisque Auctor Movie in Struck</h6>
                    <p class="my-1" style="font-size: .8rem;">1037 Views</p>
                    <div class="d-flex justify-content-between w-100">
                      <p>February 12, 2016</p>
                      <p>2.30.00</p>
                    </div>
                  </div>
                </div>

              </div>
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

.youtube-video {
  background-image: url(../assets/imgs/hqdefault.webp);
  background-repeat: no-repeat;
  background-size: cover;
  width: 67%;
}

.channel-img {
  width: 40px;
  aspect-ratio: 1/1;
}

.youtube-logo {
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 70px;
  height: 70px;
}

.video-title {
  width: 70%;
}

.link-youtube {
  bottom: 5px;

  button {
    background-color: $bg-primary;
  }
}

.movies-list {
  background-color: $bg-primary;
  height: 500px;

  .movie-poster {
    width: 100px;
    height: 100px;
  }
}
</style>