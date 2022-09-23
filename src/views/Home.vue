<template>
  <div class="home">
    <Three msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Three from '@/components/Three.vue'

export default {
  name: 'Home',
  components: {
    Three
  }
}
</script>
