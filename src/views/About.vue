<template>
  <div class="about">
    <h1>This is an about page</h1>
    <Video />
  </div>
</template>

<script>
// @ is an alias to /src
import Video from '@/components/Video.vue'

export default {
  name: 'Home',
  components: {
    Video
  }
}
</script>
