<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/404/1">404</router-link> |
      <router-link to="/404/2">Animated </router-link> |
      <router-link to="/404/3">Minimal </router-link> |
      <router-link to="/404/4">Callout </router-link> |
      <router-link to="/404/5">Tree </router-link> |
      <router-link to="/404/6">Fargo </router-link> |
      <router-link to="/404/7">Oh </router-link> |
      <router-link to="/404/8">Monkey </router-link>  

    </div>
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
  background:#ffffff
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
