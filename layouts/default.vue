<template>
  <div>
    <nav-bar />
    <nuxt />
  </div>
</template>

<script>
import NavBar from '~/components/layout/nav-bar'
export default {
  name: 'DefaultLayout',
  components: {
    navBar: NavBar,
  }
}
</script>