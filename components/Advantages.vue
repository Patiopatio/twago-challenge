<template>
  <div class="advantages">
    <p class="advantages__text">
      Lorem ipsum dolor sit amet<br />
      sunt error a non veritatis dolores consequatur<br />
      voluptates officia, quasi distinctio aut nostrum
    </p>
    <p class="advantages__text-right">150 CC</p>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.advantages {
  display: flex;
  flex-flow: row nowrap;
  justify-content: space-between;
  margin: 50px 80px 50px 50px;

  &__text {
    font-weight: bold;
    font-size: 24px;
    line-height: 32px;

    &-right {
      font-size: 12px;
    }
  }
}
</style>
