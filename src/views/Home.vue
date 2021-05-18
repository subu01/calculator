<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Video/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Video from '@/components/Video.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Video
  }
}
</script>
