<template>
  <header class="navbar">
    <nav class="navbar_nav">
      <ul class="navbar_nav_menu">
        <li class="navbar_nav_menu_item">
          <nuxt-link to="/" class="navbar_nav_menu_item_link">
            Home
          </nuxt-link>
        </li>
        <li class="navbar_nav_menu_item">
          <nuxt-link to="/" class="navbar_nav_menu_item_link">
            Kontakta
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
