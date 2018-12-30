<template>
  <div>
    <div class="main-header">
      <main-header/>
    </div>
    <div class="profile">
      <profile-container/>
    </div>
  </div>
</template>

<script>
import MainHeader from '~/components/main_header/MainHeader.vue'
import ProfileContainer from '~/components/profile/ProfileContainer.vue'

export default {
  components: {
    MainHeader,
    ProfileContainer
  }
}
</script>

<style>
</style>
