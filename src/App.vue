<template>
  <nav>
    <router-link to="/journal"><h1>Journal</h1></router-link>
    <router-link to="/contact"><h1>Contact</h1></router-link>
    <router-link to="/clavier"><h1>Clavier</h1></router-link>
  </nav>
  <router-view/>
</template>

<style>
body{
  background-color: #121920;
  color: white;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  display: flex;
  flex-direction: row;
  justify-content: center;
  border: white solid 5px;
  height: 30vh;
  margin: auto;
}

nav {
  display: flex;
  flex-direction: column;
  padding-right: 50px;
}

nav a {
  font-weight: bold;
  color: white;
  border: white solid 3px;
  width: 200px;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
