<template>
  
  <form @submit.prevent="onSubmit">
    <div class="field has-addons">
      <div class="control">
        <input class="input" type="text" v-model="text" placeholder="Search Jokes...">
      </div>
      <div class="control">
        <a class="button is-info">
          Search Jokes
        </a>
      </div>
    </div>

  </form>
</template>

<script>
export default {
  name: "SearchJokes",
  data() {
    return {
      text: ""
    };
  },
  methods: {
    onSubmit() {
      this.$emit("search-text", this.text);
      this.text = "";
    }
  }
};
</script>

<style>

</style>