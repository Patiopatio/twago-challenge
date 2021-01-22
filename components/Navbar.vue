<template>
  <div class="navbar-container">
    <Logo />
    <span class="navbar-action">Login</span>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.navbar {
  &-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 3px solid rgb(41, 57, 74);
    padding: 20px 40px 20px 50px;
    max-height: 100px;
    width: 100%;
  }
  &-action {
    font-weight: 600;
    font-size: 14px;
  }
}
</style>
