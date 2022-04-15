<template>
  <div class="home">
    <div class="container">
      <HeaderMain />
      <MainContent />
    </div>
    <FooterMain />
  </div>
</template>

<script>
// @ is an alias to /src
import MainContent from '@/components/MainContent.vue'
import HeaderMain from '@/components/HeaderMain.vue'
import FooterMain from '@/components/FooterMain.vue'

export default {
  name: 'HomeView',
  components: {
    MainContent,
    HeaderMain,
    FooterMain
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

