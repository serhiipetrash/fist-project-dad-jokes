<template>

  <section class="hero is-halfheight">
    <div class="hero-body">
      <div>
        <h1 class="title">
          Dad Jokes
        </h1>
        
        <h2 class="subtitle">
          Welcome to the best corny dad jokes app on the web
        </h2>

      </div>
    </div>
  </section>

</template>

<script>
export default {
  head() {
    return {
      title: "Welcome To Dad Jokes",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Best place for corny dad jokes"
        }
      ]
    };
  }
};
</script>