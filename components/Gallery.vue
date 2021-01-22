<template>
  <section class="gallery">
    <img :src="palm" class="gallery__image" alt="palm image" />
    <img :src="mountain" class="gallery__image" alt="moutain image" />
    <img :src="palm" class="gallery__image" alt="palm image" />
  </section>
</template>

<script>
import mountain from '../assets/mountain.jpg'
import palm from '../assets/palm.jpg'
export default {
  data() {
    return {
      mountain,
      palm,
    }
  },
}
</script>

<style lang="scss">
.gallery {
  margin: 60px 0;
  display: flex;
  overflow: hidden;

  &__image {
    height: 280px;
    width: 500px;
    margin-right: 14px;

    &:first-child {
      margin-left: -160px;
    }
  }
}
</style>
