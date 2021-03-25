<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">nuxt-tailwindcss-sample</h1>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a>
        <button class="mb-3 rounded-full flex items-center shadow bg-blue-500 px-4 py-2 text-white hover:bg-blue-400">
    Default
        </button>

    <!-- Primary -->
    <button class="flex items-center shadow bg-teal-500 px-4 py-2 text-white hover:bg-teal-400">
        Default
    </button>
    <!-- Border bottom --> 
    <button
      class="bg-blue-500 py-2 px-4 border-b-4 border-blue-800 rounded text-white hover:border-blue-lighter hover:bg-blue-400">
      Default
    </button>
    <!-- Border-->
    <button class="border-2 border-blue-500 px-4 py-2 text-blue-500 hover:text-white hover:bg-blue-500 rounded">
        <p>Default</p>
    </button>
    <!-- Line down -->
    <button class="mt-4 px-4 py-2 border-b-2 border-blue-400 font-bold text-blue-500 hover:border-blue-500">
        Default
    </button>


      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
