<template>
  <footer class="footer-container">
    <div class="footer">
      <div class="footer-top">
        <Logo class="footer__logo" />
        <div class="footer-links">
          <ul class="footer-column">
            <li class="footer-column__header">Product</li>
            <li>Enterprise</li>
            <li>Security</li>
            <li>Pricing</li>
            <li>Demo</li>
          </ul>
          <ul class="footer-column">
            <li class="footer-column__header">Company</li>
            <li>About us</li>
            <li>Blog</li>
            <li>News</li>
            <li>Careers</li>
          </ul>
          <ul class="footer-column">
            <li class="footer-column__header">Resources</li>
            <li>Help Center</li>
            <li>API</li>
          </ul>
        </div>
      </div>

      <div class="footer-bottom">
        <div class="footer-bottom-links">
          <span class="footer-bottom__text">Status</span>
          <span class="footer-bottom__text">Privacy & Terms</span>
          <span class="footer-bottom__text">Contact us</span>
        </div>
        <div class="footer-bottom-social">
          <a href="#"
            ><img
              class="footer-bottom-social__icon"
              :src="facebook"
              alt="facebook icon"
          /></a>
          <a href="#"
            ><img
              class="footer-bottom-social__icon"
              :src="linkedin"
              alt="linkedin icon"
          /></a>
          <a href="#"
            ><img
              class="footer-bottom-social__icon"
              :src="twitter"
              alt="twitter icon"
          /></a>
          <a href="#"
            ><img
              class="footer-bottom-social__icon"
              :src="youtube"
              alt="youtube icon"
          /></a>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
import facebook from '../assets/facebook.svg'
import linkedin from '../assets/linkedin.svg'
import twitter from '../assets/twitter.svg'
import youtube from '../assets/youtube.svg'

export default {
  data() {
    return {
      facebook,
      linkedin,
      twitter,
      youtube,
    }
  },
}
</script>

<style lang="scss">
.footer {
  margin: 50px 80px 20px 50px;
  &-top {
    display: flex;
    justify-content: space-between;
    border-top: 2px solid rgb(41, 57, 74);
    padding: 40px 0;
  }

  &-links {
    display: flex;
  }

  &-column {
    list-style-type: none;

    & > li {
      margin-bottom: 10px;
      font-size: 14px;
    }

    &__header {
      font-weight: bold;
    }
  }

  &__logo {
    align-items: start;
  }

  &-container {
    display: flex;
    flex-flow: column nowrap;
  }
  &-options {
    display: flex;
    flex-flow: row nowrap;
  }

  &-bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-top: 1px solid rgb(41, 57, 74);
    padding: 20px 0;
    max-height: 100px;
    width: 100%;

    &-social {
      display: flex;

      &__icon {
        width: 25px;
        height: 25px;
        margin-left: 15px;
      }
    }

    &__text {
      font-size: 12px;
      font-weight: bold;
      margin-right: 10px;
    }
  }
}
</style>
