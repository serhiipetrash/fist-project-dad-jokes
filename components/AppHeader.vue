<template>
  <b-navbar class="is-warning">
    <template #brand>
      <!-- <b-navbar-item tag="nuxt-link" to="/">
            <h1 class="title">Dad Jokes</h1>
          </b-navbar-item> -->
    </template>
    <template #start>
      <b-navbar-item tag="nuxt-link" to="/">
        Home
      </b-navbar-item>
      <b-navbar-item tag="nuxt-link" to="/jokes">
        Jokes
      </b-navbar-item>
      <b-navbar-item tag="nuxt-link" to="/about">
        About
      </b-navbar-item>
      <b-navbar-dropdown label="Info">
        <b-navbar-item href="/about">
          About
        </b-navbar-item>
        <b-navbar-item href="#">
          Contact
        </b-navbar-item>
      </b-navbar-dropdown>
    </template>
  </b-navbar>
</template>


<script>
export default {
  name: "AppHeader"
};
</script>

