<template>
  <b-navbar type="is-primary">
    <template #brand>
      <!-- <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img
                    src="https://raw.githubusercontent.com/buefy/buefy/dev/static/img/buefy-logo.png"
                    alt="Lightweight UI components for Vue.js based on Bulma"
                >
            </b-navbar-item> -->
    </template>
    <template #start>
      <b-navbar-item href="#"> Mi app </b-navbar-item>
      <!-- <b-navbar-item href="#">
                Documentation
            </b-navbar-item> -->
      <!-- <b-navbar-dropdown label="Info">
                <b-navbar-item href="#">
                    About
                </b-navbar-item>
                <b-navbar-item href="#">
                    Contact
                </b-navbar-item>
            </b-navbar-dropdown> -->
    </template>

    <template #end>
      <b-navbar-item tag="div">
        <div class="buttons">
          <span class="button">
            <router-link to="/">Home</router-link>
          </span>
          <span class="button">
            <router-link to="/about">About</router-link>
          </span>
        </div>
      </b-navbar-item>
    </template>
  </b-navbar>
</template>

<script>
export default {};
</script>

<style>
</style>