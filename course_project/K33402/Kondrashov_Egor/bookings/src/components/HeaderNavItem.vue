<template>
  <b-nav-item class="px-3" :to="{ name: routeName }">
    {{ navText }}
  </b-nav-item>
</template>

<script>
export default {
  name: "HeaderNavItem",
  props: {
    routeName: String,
    navText: String
  }
}
</script>
<style>
.nav-link {
  color: var(--accent-text) !important;
}
</style>
