<template>
  <div class="">

    <section class="vh-100 bg-danger" style="">
      <div class="container py-3 h-100">
        <div class="row d-flex justify-content-center align-items-center h-100">
          <div class="col col-xl-12">
            <div class="card" style="border-radius: 1rem">
              <div class="row g-0">
                <div class="col-md-6 col-lg-5 d-none d-md-block">
                  <img
                    src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-login-form/img1.webp"
                    alt="login form"
                    class="img-fluid"
                    style="border-radius: 1rem 0 0 1rem"
                  />
                </div>
                <div class="col-md-6 col-lg-7 d-flex align-items-center">
                  <div class="card-body p-4 p-lg-5 text-black">
                    <form>
                      <div class="d-flex align-items-center mb-3 pb-1">
                        <i
                          class="fas fa-cubes fa-2x me-3"
                          style="color: #ff6219"
                        ></i>
                        <span
                          class="h1 fw-bold mb-0 text-center text-danger mx-4.5"
                          >PAYHOUSE LOGIN</span
                        >
                      </div>

                      <div class="form-outline mb-4">
                        <input
                          type="email"
                          id="form2Example17"
                          class="form-control form-control-lg"
                          required
                        />
                        <label class="form-label" for="form2Example17"
                          >Email address</label
                        >
                      </div>

                      <div class="form-outline mb-4">
                        <input
                          type="password"
                          id="form2Example27"
                          class="form-control form-control-lg"
                          required
                        />
                        <label class="form-label" for="form2Example27"
                          >Password</label
                        >
                      </div>

                      <div class="pt-1 mb-4">
                        <button
                          class="btn btn-dark btn-lg btn-block"
                          type="button"
                        >
                          <router-link to="/home" class="text-light"
                            >Login</router-link
                          >
                        </button>
                      </div>

                      <a class="small text-muted" href="#!">Forgot password?</a>
                      <p class="mb-5 pb-lg-2" style="color: #393f81">
                        Don't have an account?
                        <a href="#!" style="color: #393f81"
                          >
                          
                          <button
                            type="button"
                            class="btn btn-danger mx-4"
                            data-bs-toggle="modal"
                            data-bs-target="#staticBackdrop"
                          >
                          <router-link to="/register"  class="text-light" styel="font-style:none">  Register</router-link>
                          
                          </button></a
                        >
                      </p>
                      <a href="#!" class="small text-muted">Terms of use.</a>
                      <a href="#!" class="small text-muted">Privacy policy</a>
                    </form>
                  </div>
                 
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>

export default {
  name: "loginPage",
  components: {
   
  },
};
</script>

<style lang="scss" scoped></style>
