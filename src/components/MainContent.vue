<template>
  <div>
    <h3>作品一覧</h3>
    <MainContentItem />
  </div>
</template>

<script>
// @ is an alias to /src
import MainContentItem from '@/components/MainContentItem.vue'

export default {
  name: 'MainContent',
  components: {
    MainContentItem
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
