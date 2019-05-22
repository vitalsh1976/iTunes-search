<template>
  <v-toolbar dark color="blue">
    <v-toolbar-side-icon></v-toolbar-side-icon>
    <v-toolbar-title>
      <nuxt-link class="title" to="/">iTunes Search</nuxt-link>
    </v-toolbar-title>
    <v-spacer></v-spacer>
    <v-btn to="/" icon>
      <v-icon>refresh</v-icon>
    </v-btn>
  </v-toolbar>
</template>

<script>
export default {};
</script>


<style>
.title {
  text-decoration: none !important;
}
.title:visited {
  color: white;
}
</style>

