<template>
  <nav>
    <router-link to="/">Inicio</router-link> |
    <router-link to="/about">Realizar Pedido</router-link>
  </nav>
  <input type="color">
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
  margin: -8px;
  font-size: 21px;
  text-align: left;
  background-color: #2c3e50;
}

nav a {
  font-weight: bold;
  color: #ecaf52;
}

nav a.router-link-exact-active {
  color: #ecaf52;
}
</style>
