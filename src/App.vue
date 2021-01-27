<template>
  <div class="app">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view />
</template>

<script>
export default {
    name: 'App'
};
</script>

<style lang="scss">
*,
:after,
:before {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Roboto', sans-serif;
  background-color: #262626;
}

.app {
  max-width: 80vw;
  background-color: #fff;
  margin: 200px auto 0;
  padding: 40px;
  border-radius: 8px;
}
</style>
