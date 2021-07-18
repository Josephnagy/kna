<template>
  <div id="app"> 
    <h1> Kate &amp; Ally's Restaurant</h1>
    <h2> Located in Forked River NJ</h2>
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>

      <b-nav-item-dropdown text="Weddings" right>

      </b-nav-item-dropdown> 
      <router-view/>
    </div>
    
  </div>
  
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
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
