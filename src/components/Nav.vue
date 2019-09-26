<template>
  <div>
    <nav class="nav-bar">
      <router-link class="nav-link" to="/">Home</router-link>
      <router-link class="nav-link" to="/about">About</router-link>
      <div class="nav-logo">West<br />Lens<br />Photography</div>
      <router-link class="nav-link" to="/portfolio">Portfolio</router-link>
      <router-link class="nav-link" to="/contact">Contact</router-link>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Nav'
}
</script>

<style>
nav.nav-bar {
  display: flex;
  flex-flow: row nowrap;
  justify-content: space-around;
  align-items: flex-end;
}
.nav-logo {
  width: 200px;
  height: 80px;
  background-color: darkslategrey;
  color: white;
  text-align: center;
}
a.nav-link {
  display: flex;
  text-decoration: none;
}
a.nav-link:link {
  color: black;
}
a.nav-link:visited {
  color: black;
}
a.nav-link:hover {
  color: grey;
}
a.nav-link:active {
  color: grey;
}
</style>
