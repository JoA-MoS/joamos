<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <hello-world-2 msg="Welcome to Your Vue.js + TypeScript App" />
  </div>
</template>

<script>
import { defineComponent } from 'vue';
import HelloWorld2 from '../components/HelloWorld2.vue';

export default defineComponent({
  name: 'Home',
  components: {
    HelloWorld2,
  },
});
</script>
