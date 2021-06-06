<template>
  <div id="app">
    <b-container>
        <b-nav small  class="mx-auto bg-info d-flex justify-content-center">
          <b-nav-item to="/" class="text-white">Home</b-nav-item>
          <b-nav-item to="/cats"  class="text-white">Cats</b-nav-item>
          <b-nav-item to="/dogs" class="text-white">Dogs</b-nav-item>
        </b-nav>
    </b-container>
    <b-container>
      <router-view/>
    </b-container>
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
</style>
