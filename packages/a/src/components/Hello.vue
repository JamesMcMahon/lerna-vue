<template>
  <div class="hello">
    <h1>{{ msg }} from Package A</h1>
  </div>
</template>

<script>
export default {
  name: "Hello",
  props: {
    msg: String
  }
};
</script>

<style scoped>
.hello {
  background-color: orangered;
}
</style>
