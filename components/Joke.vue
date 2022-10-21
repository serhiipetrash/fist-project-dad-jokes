<template>
  <nuxt-link :to="'jokes/' + id">
    <div class="box ">
      <p>{{ joke }}</p>
    </div>
  </nuxt-link>
</template>

<script>
export default {
  name: "Joke",
  props: ["joke", "id"]
};
</script>

<style>
.box {
  margin: 1rem 0;
}
</style>