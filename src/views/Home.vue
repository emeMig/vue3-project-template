<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <startComponent msg="Start Component launched "/>
  </div>
</template>

<script>
// @ is an alias to /src
import startComponent from '@/components/startComponent.vue'

export default {
  name: 'Home',
  components: {
    startComponent
  }
}
</script>
