<script>
export default {

}
</script>

<template>
  <section>
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-10">

          <!-- banner -->
          <div class="new-movie-banner d-flex w-100 text-white border-bottom border-dark my-5 px-3 pt-1">
            <div>
              <h4>New Movie</h4>
              <p>Lorem Ipsum is simply dummy text of the printing and typesettin</p>
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

          <!-- cards -->
          <div class="d-flex align-items-center my-5">

            <!-- CARD 1 -->
            <div class="card h-100 text-bg-dark rounded-5">
              <img src="../assets/imgs/1.jpg" class="card-img rounded-5" alt="1">
              <!-- informazioni card in absolute -->
              <div class="position-absolute card-rating">
                <a href="#" class="text-decoration-none text-white"><i class="fa-solid fa-star green-primary"></i>
                  4/10</a>
              </div>
              <div class="title-card position-absolute w-100 ps-4">
                <h5 class="fw-bold fs-5">Hurry Animate Blue Strack New Movie</h5>
                <span class="fw-bold fs-5">Category: </span>
                <span class="fs-5">Top Rating</span>
              </div>
              <button
                class="details-btn position-absolute bg-main hover-bg-green text-white fw-medium rounded-end-5 border-0 py-2 ps-2 pe-3">Details</button>
              <button
                class="views-btn position-absolute bg-main hover-bg-green text-white fw-medium rounded-start-5 border-0 py-2 ps-3 pe-3">598
                Views</button>
            </div>

            <!-- CARD 2 -->
            <div class="card card-active text-bg-dark rounded-5 overflow-hidden">
              <img src="../assets/imgs/2.jpg" class="card-img rounded-5 h-100 active-img" alt="1">

              <!-- informazioni card in absolute -->
              <div class="position-absolute card-rating">
                <a href="#" class="text-decoration-none text-white"><i class="fa-solid fa-star green-primary"></i>
                  4/10</a>
              </div>
              <div class="title-card position-absolute w-100 ps-4">
                <h5 class="fw-bold fs-5">Quisque Auctor Movie in Struck</h5>
                <span class="fw-bold fs-5">Category: </span>
                <span class="fs-5">Coming Soon</span>
              </div>
              <button
                class="details-btn position-absolute bg-main hover-bg-green text-white fw-medium rounded-end-5 border-0 py-2 ps-2 pe-3">Details</button>
              <button
                class="views-btn position-absolute bg-main hover-bg-green text-white fw-medium rounded-start-5 border-0 py-2 ps-3 pe-3">1037
                Views</button>
              <div
                class="movie-duration-banner position-absolute bg-green-primary text-white rounded-end-5 p-2 text-center">
                <p class="m-0">2.30.00</p>
              </div>
            </div>

            <!-- CARD 3 -->
            <div class="card h-100 text-bg-dark rounded-5">
              <img src="../assets/imgs/5.jpg" class="card-img rounded-5" alt="1">
              <!-- informazioni card in absolute -->
              <div class="position-absolute card-rating">
                <a href="#" class="text-decoration-none text-white"><i class="fa-solid fa-star green-primary"></i>
                  4/10</a>
              </div>
              <div class="title-card position-absolute w-100 ps-4">
                <h5 class="fw-bold fs-5">New Movie Quisque in Struck</h5>
                <span class="fw-bold fs-5">Category: </span>
                <span class="fs-5">Latest Movies</span>
              </div>
              <button
                class="details-btn position-absolute bg-main hover-bg-green text-white fw-medium rounded-end-5 border-0 py-2 ps-2 pe-3">Details</button>
              <button
                class="views-btn position-absolute bg-main hover-bg-green text-white fw-medium rounded-start-5 border-0 py-2 ps-3 pe-3">438
                Views</button>
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

.movie-duration-banner {
  top: 5%;
  left: -200px;
  transition: left .5s;
}

.card-active:hover .movie-duration-banner {
  left: 0;
}

.btn-slider {
  aspect-ratio: 1/1;

  &:hover {
    background-color: black !important;
  }
}

.card-img {
  filter: opacity(30%);
}

.card-active {
  height: 550px !important;
}

.card-active .active-img {
  transition: transform 1s, filter .7s;
}

.card-active:hover .active-img {
  transform: scale(1.2);
  filter: opacity(50%);
}

.title-card {
  top: 65%;
}

.card-rating {
  top: 4%;
  right: 10px;
}

.details-btn {
  top: 85%;
}

.views-btn {
  top: 85%;
  right: 0%;
}
</style>