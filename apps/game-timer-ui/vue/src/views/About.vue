<template>
  <div class="about">
    <h1>This is an about page</h1>
    <timer-item></timer-item>
  </div>
</template>

<script lang="ts">
import TimerItem from '../components/TimerItem.vue';
import { defineComponent } from 'vue';
export default defineComponent({
  components: {
    TimerItem,
  },
});
</script>
