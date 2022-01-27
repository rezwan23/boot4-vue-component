<template>
  <div>
    <span v-if="!content">
        <center class="text-danger"><h1>No Content</h1></center>
    </span>
    <span v-html="content" v-else></span>
  </div>
</template>

<script>
require('bootstrap')
export default {
    props:['content'],
  name: "GhaniBootstrap4Component",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url(https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css);
</style>
