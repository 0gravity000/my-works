<template>
  <div class="about">
    <HeaderMain />
    <MyProfile />
    <MySkill />
  </div>
</template>

<script>
// @ is an alias to /src
import MyProfile from '@/components/MyProfile.vue'
import MySkill from '@/components/MySkill.vue'
import HeaderMain from '@/components/HeaderMain.vue'

export default {
  name: 'HomeView',
  components: {
    MyProfile,
    MySkill,
    HeaderMain
  }
}
</script>
