<template>
  <div>
    <h1 class="header-1 left">VUTTR</h1>
    <h3 class="header-4 left">Very Userfull Tools to Remember</h3>
    <HelloWorld class="body-smallest" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/iconsExample.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped lang="sass">
.left
  text-align: left
</style>
