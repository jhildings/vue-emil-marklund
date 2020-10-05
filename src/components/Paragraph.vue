<template>
<div>
  <b v-if="bold">
    {{ msg }}
  </b>
  <span v-else>
      {{ msg }}
  </span>

</div>
</template>

<script>
export default {
  name: 'Paragraph',
  props: {
    msg: String,
    bold: {
      type: Boolean,
      default: false
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
