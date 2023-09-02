<script>
import { store } from '../store.js'
export default {
  data() {
    return {
      store
    }
  }
}
</script>

<template>
  <header>
    <div class="container-fluid">
      <div class="row justify-content-center">
        <div class="col-9">
          <!-- Prima Nav -->
          <div class="nav-primary w-100 d-flex align-items-center py-2 pe-">
            <!-- Elementi a sinistra -->
            <div class="d-flex align-items-center gap-2">
              <i class="fa-regular fa-envelope text-white"></i>
              <span class="text-white"> Superhit Top Movie </span>
              <span class="green-primary fw-semibold">** King Star **</span>

              <!-- Social Icons -->
              <div>
                <a href="#"><i class="m-2 fa-brands fa-facebook-f hover-green" style="color: #3b5998"></i></a>
                <a href="#"><i class="m-2 fa-brands fa-twitter hover-green" style="color: #00acee"></i></a>
                <a href="#"><i class="m-2 fa-brands fa-linkedin-in hover-green" style="color: #0e76a8"></i></a>
                <a href="#"><i class="m-2 fa-brands fa-instagram hover-green" style="color: #c8232c"></i></a>
                <a href="#"><i class="m-2 fa-brands fa-google-plus-g hover-green" style="color: #db4a39"></i></a>
              </div>
            </div>

            <!-- Elementi a Destra -->
            <div class="ms-auto">
              <a href="#" class="text-white text-decoration-none">
                <div class="hover-green">
                  <i class="fa-solid fa-lock"></i>
                  <span> Login</span>
                </div>
              </a>
            </div>
          </div>
        </div>

        <hr>
        <div class="col-9">
          <!-- Nav grande -->
          <div class="nav-secondary d-flex align-items-center mt-4 mb-5">
            <div>
              <a href="#"><img src="../assets/imgs/cropped-logo.png" alt="logo"></a>
            </div>

            <!-- Search Bar -->
            <div class="ms-auto">
              <div class="input-group">
                <button class="btn btn-outline-secondary dropdown-toggle rounded-0 border-dark px-4" type="button"
                  data-bs-toggle="dropdown" aria-expanded="false" style="padding-top: .7rem; padding-bottom: .7rem;">All
                  Movies</button>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">All Movie Categort</a></li>
                  <li><a class="dropdown-item" href="#">Coming Soon</a></li>
                  <li><a class="dropdown-item" href="#">Latest Movies</a></li>
                  <li><a class="dropdown-item" href="#">Top Rating</a></li>
                  <li><a class="dropdown-item" href="#">TV Series</a></li>

                </ul>

                <input type="text" class="search-bar form-control border-secondary border-dark" placeholder="Search..."
                  aria-label="Amount (to the nearest dollar)">
                <button
                  class="input-group-text rounded-0 border-0 bg-green-primary border-dark text-light fw-bolder">Search</button>
              </div>
            </div>
          </div>
        </div>

        <hr>

        <div class="col-9">
          <!-- Terza Nav -->
          <div class="nav-tertiary d-flex align-items-center py-3">
            <div class="d-flex align-items-center">
              <!-- primo dropdown -->
              <div class="dropdown">
                <button
                  class="btn btn-secondary dropdown-toggle text-white bg-transparent border-0 hover-green fw-bold fs-5"
                  type="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Home
                </button>
                <ul class="dropdown-menu dropdown-menu-dark">
                  <li v-for="homeElement in store.headerHomeUl"><a class="dropdown-item" href="#">{{ homeElement }}</a>
                  </li>
                </ul>
              </div>

              <!-- secondo dropdown -->
              <div class="dropdown">
                <button
                  class="btn btn-secondary dropdown-toggle text-white bg-transparent border-0 hover-green fw-bold fs-5"
                  type="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Celebrity
                </button>
                <ul class="dropdown-menu dropdown-menu-dark">
                  <li v-for="celebrityElement in store.headerCelebrityUl"><a class="dropdown-item" href="#">{{
                    celebrityElement }}</a></li>
                </ul>
              </div>

              <!-- terzo dropdown -->
              <div class="dropdown">
                <button
                  class="btn btn-secondary dropdown-toggle text-white bg-transparent border-0 hover-green fw-bold fs-5"
                  type="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Movie
                </button>
                <ul class="dropdown-menu dropdown-menu-dark">
                  <li v-for="movieElement in store.headerMovieUl"><a class="dropdown-item" href="#">{{ movieElement }}</a>
                  </li>
                </ul>
              </div>

              <!-- quarto dropdown -->
              <div class="dropdown">
                <button
                  class="btn btn-secondary dropdown-toggle text-white bg-transparent border-0 hover-green fw-bold fs-5"
                  type="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Page
                </button>
                <ul class="dropdown-menu dropdown-menu-dark">
                  <li v-for="pageElement in store.headerPageUl"><a class="dropdown-item" href="#">{{ pageElement }}</a>
                  </li>
                </ul>
              </div>

              <!-- quinto dropdown -->
              <div class="dropdown">
                <button
                  class="btn btn-secondary dropdown-toggle text-white bg-transparent border-0 hover-green fw-bold fs-5"
                  type="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Shop
                </button>
                <ul class="dropdown-menu dropdown-menu-dark">
                  <li v-for="shopElement in store.headerShopUl"><a class="dropdown-item" href="#">{{ shopElement }}</a>
                  </li>
                </ul>
              </div>

              <button class="btn btn-secondary text-white bg-transparent border-0 hover-green fw-bold fs-5" type="button">
                Blog
              </button>

              <button class="btn btn-secondary text-white bg-transparent border-0 hover-green fw-bold fs-5" type="button">
                Contact Us
              </button>
            </div>

            <div class="position-relative ms-auto">
              <a href="#"><i class="fa-solid fa-basket-shopping text-white hover-green"></i></a>
              <span
                class="header-cart position-absolute top-0 start-100 translate-middle bg-green-primary rounded-circle text-white">0</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;
@use '../styles/partials/utilities.scss' as *;

.container-fluid {
  background-color: $bg-header;
}

.hover-green {
  transition: color .5s;

  &:hover {
    color: $green-primary !important;
  }
}

.search-bar {
  background-color: $bg-header;
}

::placeholder {
  color: grey
}

hr {
  width: 100vw;
  color: lightgrey;
}

.header-cart {
  font-size: .8rem;
  padding: 0rem .35rem;
}
</style>