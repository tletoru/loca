<template>
  <nav>

    <img alt="Vue logo" src="@/assets/logo.png" >
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/whitepaper">White-paper</router-link> |
    <router-link to="/roadmap">Roadmap</router-link> |
    <router-link to="/allcollections">All Collections</router-link> |
    <router-link to="/team">Team</router-link>



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
  text-align: left;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
