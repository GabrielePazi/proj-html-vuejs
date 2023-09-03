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
  <footer>
    <!-- Footer Primario -->
    <div class="footer-primary w-100">
      <div class="footer-content w-100 h-100">
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-10">

              <div class="d-flex text-white my-5 gap-3">
                <!-- About Us -->
                <div class="footer-list">
                  <div class="mb-3">
                    <h5 class="fw-bolder m-0">About Us</h5>
                    <div class="list-title-border"></div>
                  </div>

                  <ul class="list-unstyled">
                    <li class="mb-3">Mauris malesuada arcu eu posuere eleifen. Ut egestas tortor at leo egestas tincidunt.
                      Nam
                      tincidunt metus tristique tristique viverra. Mauris erat ante, egestas vitae dapibus seds.</li>
                    <li class="icons d-flex gap-3 ms-0">
                      <a href="#" class="social-icon"><i
                          class="icon m-2 fa-brands p-2 rounded-circle fa-facebook-f text-white w-100 h-100 text-center"
                          style="background-color: #3b5998;"></i></a>
                      <a href="#" class="social-icon"><i
                          class="icon m-2 fa-brands p-2 rounded-circle fa-twitter text-white w-100 h-100 text-center"
                          style="background-color: #00acee;"></i></a>
                      <a href="#" class="social-icon"><i
                          class="icon m-2 fa-brands p-2 rounded-circle fa-linkedin-in text-white w-100 h-100 text-center"
                          style="background-color: #0e76a8;"></i></a>
                      <a href="#" class="social-icon"><i
                          class="icon m-2 fa-brands p-2 rounded-circle fa-instagram text-white w-100 h-100 text-center"
                          style="background-color: #c8232c;"></i></a>
                      <a href="#" class="social-icon"><i
                          class="icon m-2 fa-brands p-2 rounded-circle fa-google-plus-g text-white w-100 h-100 text-center"
                          style="background-color: #db4a39;"></i></a>
                    </li>
                  </ul>
                </div>

                <!-- Movie Categories -->
                <div class="footer-list">
                  <div class="mb-3">
                    <h5 class="fw-bolder m-0">Movie Category</h5>
                    <div class="list-title-border"></div>
                  </div>

                  <ul class="list-unstyled">
                    <li class="mb-4" v-for="category in store.footerCategoryUl"><a href="#"
                        class="text-white text-decoration-none hover-green">{{ category }}</a></li>
                  </ul>
                </div>

                <!-- Movie Categories -->
                <div class="footer-list">
                  <div class="mb-3">
                    <h5 class="fw-bolder m-0">Information</h5>
                    <div class="list-title-border"></div>
                  </div>

                  <ul class="list-unstyled">
                    <li class="mb-4" v-for="info in store.footerInfoUl"><a href="#"
                        class="text-white text-decoration-none hover-green">{{ info }}</a></li>
                  </ul>
                </div>

                <!-- Recent Posts -->
                <div class="footer-list">
                  <div class="mb-3">
                    <h5 class="fw-bolder m-0">Recent Posts</h5>
                    <div class="list-title-border"></div>
                  </div>

                  <ul class="list-unstyled">
                    <li class="mb-4">
                      <div class="d-flex">
                        <a href="#"><img class="flex-shrink-1 movie-poster" src="../assets/imgs/blog1-100x100.jpg"
                            alt=""></a>
                        <div class="pt-1 ps-2 w-100 h-100 flex-shrink-0">
                          <h6><a href="#" class="text-white text-decoration-none hover-green">Actor The Concept Movie High
                              Concept Theory see the post</a></h6>
                          <p>April,14 2020</p>
                        </div>
                      </div>
                    </li>
                    <li class="mb-4">
                      <div class="d-flex">
                        <a href="#"><img class="flex-shrink-1 movie-poster" src="../assets/imgs/blog2-100x100.jpg"
                            alt=""></a>
                        <div class="pt-1 ps-2 w-100 h-100 flex-shrink-0">
                          <h6><a href="#" class="text-white text-decoration-none hover-green">Consequat Nam lectus nibh
                              aucibus It has turpis survived.</a></h6>
                          <p>April,14 2020</p>
                        </div>
                      </div>
                    </li>
                    <li class="mb-4">
                      <div class="d-flex">
                        <a href="#"><img class="flex-shrink-1 movie-poster" src="../assets/imgs/blog3-100x100.jpg"
                            alt=""></a>
                        <div class="pt-1 ps-2 w-100 h-100 flex-shrink-0">
                          <h6><a href="#" class="text-white text-decoration-none hover-green">Nam lectus nibh consequat
                              aucibus turpis It has survived.</a></h6>
                          <p>April,14 2020</p>
                        </div>
                      </div>
                    </li>
                  </ul>
                </div>

              </div>
            </div>
          </div>
        </div>

      </div>
    </div>

    <!-- Footer Secondario -->
    <div class="footer-secondary">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-10">
            <div class="d-flex justify-content-between my-3">
              <div class="d-flex align-items-center gap-3">
                <p class="m-0"><a href="#" class="text-white text-decoration-none hover-green">Terms And Conditions</a>
                </p>
                <p class="m-0"><a href="#" class="text-white text-decoration-none hover-green">Policy</a></p>
                <p class="m-0"><a href="#" class="text-white text-decoration-none hover-green">About</a></p>
              </div>

              <div class="d-flex align-items-center text-white">
                <p class="m-0">© 2020 <a href="#" class="green-primary theme-ft text-decoration-none">@Themepul</a> All
                  Rights Reserved.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;
@use '../styles/partials/utilities.scss' as *;

.footer-primary {
  height: 500px;
  background-image: url(../assets/imgs/ft-bg.jpg);
  background-size: cover;
  background-repeat: no-repeat;

  .movie-poster {
    width: 80px;
    height: 80px;
  }
}

.footer-content {
  background-color: $bg-primary;
  opacity: 0.9;

  .footer-list {
    width: 25%;
  }

  .list-title-border {
    height: 1.5px;
    background-color: white;
    width: 15%;
  }

  .social-icon {
    width: 35px;
    height: 35px;


    & .icon {
      transition: background-color .5s, color .5s;
    }

    &:hover .icon {
      background-color: transparent !important;
      color: $green-primary !important;
    }

    .icon {
      line-height: 1.3rem;
    }
  }
}

.footer-secondary {
  background-color: $bg-header;
}

.theme-ft {
  transition: color .5s;

  &:hover {
    color: white !important;
  }
}
</style>