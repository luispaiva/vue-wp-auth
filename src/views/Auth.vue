<template>
  <div class="auth">
      <section class="content">
          <div class="content-left">
              <img class="auth-left" src="@/assets/img/auth-left.jpg" alt="login">
              <div class="register">
                  <h1>Welcome to Wordpress</h1>
                  <p>
                      Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  </p>
                  <a href="#">
                      Register
                  </a>
              </div>
          </div>
          <div class="content-right">
              <FormLogin/>
          </div>
      </section>
  </div>
</template>

<script>
import FormLogin from '@/components/FormLogin';

export default {
  name: 'Auth',
  components: {
      FormLogin
  }
}
</script>
<style lang="scss">
@import '@/assets/sass/auth';
</style>