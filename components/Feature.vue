<template>
  <div class="feature">
    <div><img :src="logo" class="feature__logo" alt="logo" /></div>
    <div>
      <h2 class="feature__header">This is a header</h2>
      <p class="feature__text">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Itaque
        dignissimos debitis, sunt error a non veritatis dolores consequatur
        voluptates officia, quasi distinctio aut nostrum et at nam veniam
        reiciendis repudiandae.
      </p>
    </div>
  </div>
</template>

<script>
import logo from '../assets/logo.svg'

export default {
  data() {
    return {
      logo,
    }
  },
}
</script>

<style lang="scss">
.feature {
  display: flex;
  flex-direction: row;
  padding: 50px;

  &__header {
    margin-bottom: 30px;
  }

  &__logo {
    height: 30px;
    margin-right: 10px;
  }
  &__text {
    font-size: 16px;
    font-weight: 600;
    line-height: 24px;
  }
}
</style>
