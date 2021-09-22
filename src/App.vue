<template>
  <div id="app" class="container container--fluid">
        <router-link to="/">POST</router-link> |
        <router-link to="/category">CATEGORY</router-link>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  font-size: 22px;
}
</style>
