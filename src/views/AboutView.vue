<template>
  <div class="about">
    <div class="container">
      <HeaderMain />
      <MyProfile />
      <MySkill />
    </div>
    <FooterMain />
  </div>
</template>

<script>
// @ is an alias to /src
import MyProfile from '@/components/MyProfile.vue'
import MySkill from '@/components/MySkill.vue'
import HeaderMain from '@/components/HeaderMain.vue'
import FooterMain from '@/components/FooterMain.vue'

export default {
  name: 'HomeView',
  components: {
    MyProfile,
    MySkill,
    HeaderMain,
    FooterMain
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>