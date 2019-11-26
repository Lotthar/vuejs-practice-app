<template>
  <div id="app">
    <div id="nav" class="nav">
      <router-link to="/">Home</router-link>|
      <router-link to="/cats">Cats</router-link>|
      <router-link to="/dogs">Dogs</router-link>|
    </div>
    <b-container>
      <router-view />
    </b-container>
  </div>
</template>

<style scoped>
.nav {
  display: flex;
  justify-content: center;
  margin: 15px;
}
</style>