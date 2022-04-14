<template>
  <div class="home">
    <HeaderMain />
    <MainContent />
  </div>
</template>

<script>
// @ is an alias to /src
import MainContent from '@/components/MainContent.vue'
import HeaderMain from '@/components/HeaderMain.vue'

export default {
  name: 'HomeView',
  components: {
    MainContent,
    HeaderMain
  }
}
</script>
