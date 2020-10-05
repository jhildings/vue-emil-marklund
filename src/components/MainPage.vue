<template>
  <div>
    <div>
      <Paragraph msg="Kollegor är rätt, kolleger är fel." bold="true" />
      <Paragraph msg="Man kan inte göra markdown syntax på länkar i facebook" bold="true" />
      <Paragraph msg="Både större än jag och större än mig funkar."/>
    </div>

    <div>
      <a href="https://emil-marklund.se/reps.php">Gå till sidan om växthus</a>
    </div>
  </div>
</template>

<script>

import Paragraph from './Paragraph.vue'

export default {
  name: 'MainPage',
  props: {
    msg: String
  },
  components: {
    Paragraph
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
