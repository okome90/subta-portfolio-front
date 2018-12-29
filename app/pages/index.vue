<template>
  <section class="container">
    <div class="main-header">
      <main-header/>
    </div>
  </section>
</template>

<script>
import MainHeader from '~/components/main_header/MainHeader.vue'

export default {
  components: {
    MainHeader
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
