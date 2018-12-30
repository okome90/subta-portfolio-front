<template>
  <div class="tile is-ancestor">
    <div class="tile is-parent">
      <div class="tile is-child box">
        <profile-header/>
      </div>
    
      <main class="tile is-child box">
        <profile-main/>
      </main>
    </div>
  </div>
</template>

<script>
import ProfileHeader from '@/components/profile/atomic/ProfileHeader.vue'
import ProfileMain from '@/components/profile/atomic/ProfileMain.vue'
import ProfileImage from '@/components/profile/atomic/ProfileImage.vue'

export default {
  components: {
    ProfileHeader,
    ProfileMain
  }
}
</script>
