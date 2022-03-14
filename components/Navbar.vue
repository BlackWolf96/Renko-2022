<template>
  <header class="navigation flex">
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
