<template>
  <nav>
    <router-link to="/" >Inicio</router-link> |
    <router-link to="/about" >Realizar Pedido</router-link>
    <h1>Pastelería Amanecer</h1>
  </nav>
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
  text-align: right;
  color: #ecaf52;
  background-color: #57330a;
}

nav a {
  font-weight: bold;
  color: #ecaf52;
}

nav a.router-link-exact-active {
  color: #e9dfb9;
}

nav h1{
  color: #ecaf52;
  text-align: left;
  position: absolute;
  left: 30px;
  top: -4px;
}
</style>
