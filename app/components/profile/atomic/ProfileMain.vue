<template>
  <div class="columns is-mobile">
    <div class="column is-two-fifths">
      <profile-image/>
    </div>
    <div class="column is-half">
      <profile-detail/>
    </div>
  </div>
</template>

<script>
import ProfileDetail from '@/components/profile/atomic/ProfileDetail.vue'
import ProfileImage from '@/components/profile/atomic/ProfileImage.vue'

export default {
  components: {
    ProfileDetail,
    ProfileImage
  }
}
</script>
