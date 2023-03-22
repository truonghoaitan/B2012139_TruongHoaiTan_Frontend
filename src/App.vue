<script>

import AppHeader from "./components/AppHeader.vue";

export default {
  components: {
    AppHeader,
  },
};
</script>

<template>
  <div id="app">
    <AppHeader />

    <div class="container mt-3">
      <router-view />
    </div>
  </div>
  <header>
    <h1>Hello, Vue.js!</h1>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style >
.page {
  max-width: 400px;
  margin: auto;
}
</style>
