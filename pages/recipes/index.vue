<template>
  <section class="recipes">
    <Recipe
      thumbnail="https://www.sbs.com.au/food/sites/sbs.com.au.food/files/styles/full/public/ep8_okonomiyaki.jpg?itok=KkLAmsnT&mtime=1596596304"
      title="Delicious kind of Okonomiyaki"
      previewText="Awesome!"
    />
    <Recipe
      thumbnail="https://www.dailyhawker.com/wp-content/uploads/2018/11/dubai-street-food.jpg"
      title=" Amazing tacos directly from Mexico"
      previewText="just Woooow!"
    />
    <Recipe
      thumbnail="https://s1.qwant.com/thumbr/0x380/1/0/6bcbc59b88c0c5b7dad179992f8c0a8c495eee53b6f0d3abfc555b7c6cc072/Canadian-Food.jpg?u=http%3A%2F%2Fflavorverse.com%2Fwp-content%2Fuploads%2F2017%2F12%2FCanadian-Food.jpg&q=0&b=1&p=0&a=1"
      title="Real Canadian pancakes"
      previewText="so Good!"
    />
  </section>
</template>

<script>
import Recipe from "@/components/Recipe";

export default {
  components: { Recipe }
};
</script>

<style scoped>
.recipes {
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-items: center;
}
.recipe {
  box-sizing: border-box;
  width: 280px;
  padding: 8px;
  margin: 8px;
  border: 1px solid #ccc;
  box-shadow: 0 2px 2px #aaa;
}

h1,
p {
  text-align: center;
}

.thumbnail {
  background-position: center;
  background-size: cover;
  width: 100%;
  height: 200px;
}
</style>
