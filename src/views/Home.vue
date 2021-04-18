<template>
  <div class="home">
    <div class="flex justify-center align-center">
          <img alt="Vue logo" src="../assets/logo.png">
    </div>
    <startComponent msg="Start Component Loading...  "/>
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
