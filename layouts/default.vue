<template>
  <div>
    <Header />
    <Nuxt />
    <Hooter />
  <div>
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
