<template>
  <div id="app2">
    <div id="nav">
      <router-link to="/">Home2</router-link> |
      <router-link to="/about">About2</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app2 {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;
}

#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    text-decoration: none;

    &.router-link-exact-active {
      // color: #42b983;
    }
  }
}
</style>
