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
              <p>Lorem Ipsum is simply dummy text of the printing and typesetting</p>
            </div>
          </div>

          <!-- Movie Filter -->
          <div>
            <ul class="list-unstyled d-flex gap-5">
              <li><a href="#" class="movie-filter text-decoration-none text-white hover-green fs-5">All</a></li>
              <li><a href="#" class="movie-filter text-decoration-none text-white hover-green fs-5">Coming Soon</a></li>
              <li><a href="#" class="movie-filter text-decoration-none text-white hover-green fs-5">Latest Movies</a></li>
              <li><a href="#" class="movie-filter text-decoration-none text-white hover-green fs-5">Top Rating</a></li>
              <li><a href="#" class="movie-filter text-decoration-none text-white hover-green fs-5">TV Series</a></li>
            </ul>
          </div>

          <!-- Cards container -->
          <div class="d-flex gap-4 align-items-center my-5 flex-wrap">

            <!-- Card 1 -->
            <div class="card card-active h-100 text-bg-dark rounded-0 overflow-hidden">
              <div class="card-overlay position-absolute w-100 h-100"></div>
              <img src="../assets/imgs/1.jpg" class="card-img active-img rounded-0" alt="1">
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

            <!-- Card 2 -->
            <div class="card card-active h-100 text-bg-dark rounded-0 overflow-hidden">
              <div class="card-overlay position-absolute w-100 h-100"></div>
              <img src="../assets/imgs/5-1.jpg" class="card-img active-img rounded-0" alt="1">
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

            <!-- Card 3 -->
            <div class="card card-active h-100 text-bg-dark rounded-0 overflow-hidden">
              <div class="card-overlay position-absolute w-100 h-100"></div>
              <img src="../assets/imgs/3.jpg" class="card-img active-img rounded-0" alt="1">
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

            <!-- Card 4 -->
            <div class="card card-active h-100 text-bg-dark rounded-0 overflow-hidden">
              <div class="card-overlay position-absolute w-100 h-100"></div>
              <img src="../assets/imgs/4.jpg" class="card-img active-img rounded-0" alt="1">
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

            <!-- Card 5 -->
            <div class="card card-active h-100 text-bg-dark rounded-0 overflow-hidden">
              <div class="card-overlay position-absolute w-100 h-100"></div>
              <img src="../assets/imgs/3 (1).jpg" class="card-img active-img rounded-0" alt="1">
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

            <!-- Card 6 -->
            <div class="card card-active h-100 text-bg-dark rounded-0 overflow-hidden">
              <div class="card-overlay position-absolute w-100 h-100"></div>
              <img src="../assets/imgs/2.jpg" class="card-img active-img rounded-0" alt="1">
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

          </div>

        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;
@use '../styles/partials/utilities.scss' as *;


.movie-filter {
  transition: border-bottom;

  &:hover {
    border-bottom: 1px solid $green-primary;
  }
}

.card {
  width: 31%;
}

.card-img {
  filter: opacity(50%);
  object-fit: cover;
  height: 550px;
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

.card-overlay {
  background-color: transparent;
  transition: background-color .8s;
}

.card:hover .card-overlay {
  background: rgb(2, 0, 36);
  background: linear-gradient(180deg, rgba(2, 0, 36, 1) 0%, rgba(25, 237, 0, 0.5999649859943977) 0%, rgba(0, 0, 0, 1) 100%);
}
</style>