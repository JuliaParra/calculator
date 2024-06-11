<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import WelcomeItem from './components/WelcomeItem.vue';
</script>

<template>
  <div id="app">
    <WelcomeItem/>
  </div>
</template>

<script>
import Calculator from './components/WelcomeItem.vue'

export default {
  name: 'app',
  components: {
    WelcomeItem
  }
}
</script>

<style lang="scss">
  body {
    background-color: #222;
    margin: 0;
    padding: 0;
  }

  #app {
    font-family: 'Avenir', Helvetica, Arial;
    text-align: center;
    color: #fff;
  }
</style>
<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
