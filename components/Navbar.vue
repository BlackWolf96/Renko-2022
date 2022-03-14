<template>
  <header class="navigation flex bg__black">
    <nav class="navigation__nav">
      <nuxt-link to="/" class="navigation__link">
        Home
      </nuxt-link>
      <nuxt-link to="/" class="navigation__link">
        Kontakt
      </nuxt-link>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'NavBar',
  data () {
    return {
      mobile: ''
    }
  },
  methods: {

  }
}
</script>
