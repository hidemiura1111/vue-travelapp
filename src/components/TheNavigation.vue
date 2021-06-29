<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/Brazil">Brazil</router-link>
    <router-link to="/Hawaii">Hawaii</router-link>
    <router-link to="/Jamaica">Jamaica</router-link>
    <router-link to="/Panama">Panama</router-link>
  </div>
</template>

<style scoped>
#nav {
  display: flex;
  justify-content: center;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  padding: 0 10px;
}

#nav a.vue-school-active-class {
  color: #42b983;
}
</style>