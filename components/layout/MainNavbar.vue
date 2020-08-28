<template>
    <navbar position="fixed"
            :transparent="transparent"
            :color-on-scroll="colorOnScroll"
            menu-classes="ml-auto">
        <template slot-scope="{toggle, isToggled, extraClass}">
          <nuxt-link class="navbar-brand" to="/">
                    <img src="/img/logo_text_inline_black.svg" width="180" v-if="extraClass">
            <img src="/img/logo_text_inline_white.svg" width="180" v-else>
          </nuxt-link>
        </template>
        <template slot="navbar-menu">
          <li class="nav-item">
            <nuxt-link class="nav-link"
               to="#events">
              <p>Events</p>
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link"
               to="#team">
              <p>Unser Team</p>
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link"
               to="#about">
              <p>Über uns</p>
            </nuxt-link>
          </li>
            <li class="nav-item">
              <nuxt-link class="nav-link"
                 to="#contact">
                <p>Kontakt</p>
              </nuxt-link>
            </li>

        </template>
    </navbar>
</template>

<script>
  import { DropDown, NavbarToggleButton, Navbar, NavLink } from '@/components';
  import { Popover } from 'element-ui'
  export default {
    name: 'main-navbar',
    props: {
      transparent: Boolean,
      colorOnScroll: Number,
    },
    components: {
      DropDown,
      Navbar,
      NavbarToggleButton,
      NavLink,
      [Popover.name]: Popover
    }
  }
</script>

<style scoped>

</style>
