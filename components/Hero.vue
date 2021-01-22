<template>
  <div class="hero">
    <h3 class="hero__text-sub">This is a short info about the product</h3>
    <h1 class="hero__text">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit debitis, sunt
      error a non veritatis.
    </h1>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.hero {
  margin: 50px 80px 50px 50px;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;

  &__text {
    font-size: 50px;
    line-height: 60px;
    font-weight: bold;

    &-sub {
      font-size: 16px;
      font-weight: 600;
      margin-bottom: 10px;
    }
  }
}
</style>
