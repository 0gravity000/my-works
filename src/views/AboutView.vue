<template>
  <div class="about">
    <MyProfile />
    <MySkill />
  </div>
</template>

<script>
// @ is an alias to /src
import MyProfile from '@/components/MyProfile.vue'
import MySkill from '@/components/MySkill.vue'

export default {
  name: 'HomeView',
  components: {
    MyProfile,
    MySkill
  }
}
</script>
