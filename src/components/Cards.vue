<script>
export default {
  props: {
    comics: Array,
  },
};
</script>
<template>
  <ul>
    <li v-for="(comic, index) in comics">
      <img :src="comic.thumb" alt="comic" />
      <p>{{ comic.price }}</p>
    </li>
  </ul>
</template>
<style lang="scss" scoped></style>
