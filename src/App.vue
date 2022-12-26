<template>
  <nav>
    <router-link to="/Readfast" class="readfast">Read Fast</router-link>
  </nav>
  <router-view/>
</template>

<style>
nav{
  width: 100%;
  height: 2rem;
  padding: 0;
  background-color: #2c3e50;
  margin-top:2vh;
  margin-bottom: 2vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav a {
  font-weight: bold;
  color: white;
  text-decoration: none;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
