<template>
  <AppLayout>
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
    <div class="home">asdas</div>
  </AppLayout>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HelloWorld from '@/components/HelloWorld.vue';
import AppLayout from '@/layouts/AppLayout.vue';

export default defineComponent({
  name: 'Home',
  components: {
    HelloWorld,
    AppLayout,
  },
});
</script>
