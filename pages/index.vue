<template>
  <div class="container">
    <NuxtLink to="/garden">Garden</NuxtLink>
    <div>
      <Logo />
      <h1 class="title block font-light text-6xl tracking-wide">
        nuxt-app
      </h1>
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
  color: #35495e;
}
</style>
