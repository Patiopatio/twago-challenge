<template>
  <div class="logo-container">
    <NuxtLink to="/" class="logo-link"
      ><img :src="logo" class="logo" alt="logo" />
      <p class="logo-text">ACME</p>
    </NuxtLink>
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
.logo {
  height: 30px;
  margin-right: 10px;

  &-link {
    display: flex;
    align-items: center;
    font-weight: 800;

    text-decoration: none;
  }

  &-container {
    display: flex;
    flex-direction: row;
  }

  &-text {
    color: rgb(41, 57, 74);
  }
}
</style>
