<template>
    
  <div class="container">
    <logo/>
    <h1>About page</h1>
    <nuxt-link to="/">Home page</nuxt-link>
    <p>fjj, halmoni</p>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
export default {
  components: {
    Logo
  },
  transition: 'bounce',
  head: {
    title: 'About Webcentury',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      { hid: 'description', name: 'description', content: 'Learn by doing with webcentury.' }
    ]
  }
}
</script>