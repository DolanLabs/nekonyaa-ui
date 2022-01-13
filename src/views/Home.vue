<template>
  <div class="home">
    <box-with-tokens />
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
import BoxWithTokens from '../components/BoxWithTokens.vue';

export default {
  name: 'Home',
  components: {
    // HelloWorld,
    BoxWithTokens,
  },
};
</script>
