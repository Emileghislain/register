<template>
  <div class="container">
    <div class="padding__1"></div>
    <div class="left">
      <div class="left__title">
        <span>chakra</span>
        <button>PRO</button>
      </div>
      <div class="left__content">
        <h1>Ready to build your next app ?</h1>
        <span>Create an account and start realizing your next project. With more than 220+ components, you'll get there fast</span>
        <div class="left__bottom">
          <div class="left__bottom__images">
            <img class="image left__bottom__images__1" src="/images/pexels-reign-martinez-11720281.jpg">
            <img class="image left__bottom__images__2" src="/images/pexels-reign-martinez-11720281.jpg">
            <img class="image left__bottom__images__3" src="/images/pexels-reign-martinez-11720281.jpg">
            <img class="image left__bottom__images__4" src="/images/pexels-reign-martinez-11720281.jpg">
            <img class="image left__bottom__images__5" src="/images/pexels-reign-martinez-11720281.jpg">
          </div>
          <span>Join 3.000+ customers</span>
        </div>
      </div>
      <div class="footer">&copy; 2022 Chakra UI Pro. All rights reserved.</div>
    </div>
    <div class="right">
      <div class="right__title1">
        <h2>Log in to your account</h2>
        <span>You don't need a password. Is safer that way.</span>
      </div>
      <div class="input">
        <input class="input__email" placeholder="Enter your email">
        <Button class="button button__login">Continue with Email</Button>
        <div class="diviser">
          <hr>OR<hr>
        </div>
        <Button class="button button__email">Continue with Email</Button>
        <Button class="button button__email">Continue with Email</Button>
        <Button class="button button__email">Continue with Email</Button>
        <Button class="button button__email">Continue with Email</Button>
        <span class="contact">Can't sign in? <a>Contact Us</a></span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'RegisterPage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import '../assets/register.scss';
</style>
