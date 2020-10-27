<template>
  <article class="recipe">
    <div
      class="thumbnail"
      :style="{ backgroundImage: 'url(' + thumbnail + ')' }"
    ></div>
    <h1>{{ title }}</h1>
    <p>{{ previewText }}</p>
  </article>
</template>

<script>
export default {
  props: ["thumbnail", "title", "previewText"],
  data() {
    return {};
  },
  created() {}
};
</script>

<style lang="css" scoped>
.thumbnail {
  background-position: center;
  background-size: cover;
  width: 100%;
  height: 200px;
}
</style>
