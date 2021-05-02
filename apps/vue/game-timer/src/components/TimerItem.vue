<template>
  <div>
    <p>Welcome to Game Item</p>
    <pre>Coutner: {{ counter }}</pre>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export interface Timer {
  name: string,
  counter: number
}

export default defineComponent({
  name: 'TimerItem',
  data():Timer {
    return {
      name: 'test',
      counter: 0,
    };
  },
  mounted() {
    setInterval(() => {
      this.counter++;
    }, 1000);
  },
});
</script>

<style scoped lang="scss"></style>
