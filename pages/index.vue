<template>
  <div>
    <h1>Search Itunes</h1>
    <br>
    <form @submit.prevent="submit">
      <input placeholder="Enter artist name" v-model="search" ref="search" autofocus>
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      search: ""
    };
  },
  methods: {
    submit(event) {
      this.$router.push(`results/${this.search}`);
    }
  }
};
</script>

<style>
* {
  text-align: center;
}
h1 {
  padding: 20px;
}
</style>

