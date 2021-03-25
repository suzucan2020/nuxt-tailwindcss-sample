<template>
  <main class="container relative min-h-screen pt-16">
    <Header />
    <Nuxt />
    <Hooter />
  </main>
</template>

<script>
  import Header from '@/components/Header.vue';
  import Hooter from '@/components/Hooter.vue';
  export default {
    components: {
      Header,
      Hooter
    }
  };
</script>
