<template>
  <div class="home">
    <h1>Welcome to My Vue.js Homepage</h1>
    <p>Explore the basics of Vue.js with a simple example page.</p>

    <div class="links">
      <a href="https://vuejs.org" target="_blank" rel="noopener">Official Vue.js Docs</a>
      <a href="https://github.com/vuejs/vue" target="_blank" rel="noopener">GitHub - Vue.js</a>
      <a href="https://vue-router.vuejs.org" target="_blank" rel="noopener">Vue Router</a>
      <a href="https://vuex.vuejs.org" target="_blank" rel="noopener">Vuex</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
}
</script>

<style scoped>
.home {
  text-align: center;
  padding: 20px;
}

h1 {
  color: #2c3e50;
}

p {
  font-size: 18px;
  color: #34495e;
}

.links {
  margin-top: 20px;
}

.links a {
  margin: 0 15px;
  text-decoration: none;
  color: #42b983;
}

.links a:hover {
  text-decoration: underline;
}
</style>
