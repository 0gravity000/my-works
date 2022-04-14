<template>
  <div class="home">
    <MainContent
      title="ポートフォリオ@0gravity"
      sub-title="Thank you for visiting my site"
    />
  </div>
</template>

<script>
// @ is an alias to /src
import MainContent from '@/components/MainContent.vue'

export default {
  name: 'HomeView',
  components: {
    MainContent
  }
}
</script>
