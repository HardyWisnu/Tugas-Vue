<script setup></script>

<template>
  <section class="hero py-3 px-4">
            <div class="container px-3 py-4">
                <div class="row align-items-center g-lg-5 py-3">
                  <div class="col-lg-7 text-center text-lg-start">
                    <h1 class="display-4 fw-bold lh-1 mb-3">Vertically centered hero sign-up form</h1>
                    <p class="col-lg-10 fs-4">Below is an example form built entirely with Bootstrap’s form controls. Each required form group has a validation state that can be triggered by attempting to submit the form without completing it.</p>
                  </div>
                  <div class="col-md-10 mx-auto col-lg-5">
                    <form class="p-4 p-md-5 border rounded-3 bg-light">
                      <div class="form-floating mb-3">
                        <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
                        <label for="floatingInput">Email address</label>
                      </div>
                      <div class="form-floating mb-3">
                        <input type="password" class="form-control" id="floatingPassword" placeholder="Password">
                        <label for="floatingPassword">Password</label>
                      </div>
                      <div class="checkbox mb-3">
                        <label>
                          <input type="checkbox" value="remember-me"> Remember me
                        </label>
                      </div>
                      <button class="w-100 btn btn-lg btn-primary" type="submit">Sign up</button>
                      <hr class="my-4">
                      <small class="text-muted">By clicking Sign up, you agree to the terms of use.</small>
                      <lottie-player src="https://assets3.lottiefiles.com/packages/lf20_sk5h1kfn.json" background="transparent" speed="1"
                        style="width: 100%; height: auto;" loop autoplay></lottie-player>
                    </form>
                  </div>
                </div>
              </div>
        </section>
</template>

<style scoped></style>
