<script>
export default {

}
</script>

<template>
  <section>
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-10">

          <div class="subscribe-section-container position-relative my-5">
            <div class="subscribe-overlay position-absolute w-100 h-100 d-flex flex-column align-items-center">

              <div class="d-flex gap-4" style="width: 80%;">
                <!-- FirstName input -->
                <div class="input-group flex-nowrap" style="height: 3.3rem;">
                  <input type="text" class="form-control rounded-5 border-white bg-green-primary" placeholder="First Name"
                    aria-describedby="addon-wrapping">
                </div>

                <!-- LastName input -->
                <div class="input-group flex-nowrap" style="height: 3.3rem;">
                  <input type="text" class="form-control rounded-5 border-white bg-green-primary" placeholder="Last Name"
                    aria-describedby="addon-wrapping">
                </div>

                <!-- Email input -->
                <div class="input-group flex-nowrap" style="height: 3.3rem;">
                  <input type="text" class="form-control rounded-5 border-white bg-green-primary"
                    placeholder="Email Address" aria-describedby="addon-wrapping">
                </div>
              </div>

              <button class="subscribe-btn btn rounded-5 text-white px-5 py-3 mt-5 fw-semibold">Subscribe</button>
            </div>

            <img class="postion-absolute" src="../assets/imgs/form-bg-1.png" alt="">
          </div>

        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;
@use '../styles/partials/utilities.scss' as *;

img {
  width: 100%;
  object-fit: contain;
}

.subscribe-overlay {
  top: 25%;
}

.subscribe-btn {
  background-color: $bg-header;
  transition: background-color 1s;

  &:hover {
    background-color: white;
    color: black !important;
  }
}

::placeholder {
  color: white;
}
</style>