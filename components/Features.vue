<template>
  <div class="features">
    <div class="features-row">
      <Feature class="features-column border-bottom border-right" />
      <Feature class="features-column border-bottom" />
    </div>
    <div class="features-row">
      <Feature class="features-column border-right" />
      <Feature class="features-column" />
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.features {
  margin: 50px 80px 50px 50px;
  border: 4px solid rgb(41, 57, 74);

  &-row {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    width: 100%;
  }

  &-column {
    display: flex;
    flex-direction: column;
    flex-basis: 100%;
    flex: 1;
    height: 380px;
  }
}
.border {
  &-bottom {
    border-bottom: 4px solid rgb(41, 57, 74);
  }
  &-right {
    border-right: 4px solid rgb(41, 57, 74);
  }
}
</style>
