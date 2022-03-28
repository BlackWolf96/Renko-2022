<template>
  <header class="navbar flex bg__black">
    <nav class="navbar__nav">
      <ul class="navbar__nav__menu">
        <li class="navbar__nav__menu__item">
          <nuxt-link to="/" class="navbar__nav__menu__item__link">
            Home
          </nuxt-link>
        </li>
        <li class="navbar__nav__menu__item">
          <nuxt-link to="/" class="navbar__nav__menu__item__link">
            Kontakt
          </nuxt-link>
        </li>
      </ul>
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
