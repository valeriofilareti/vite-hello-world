
<script>

import Jumbo from "./components/Jumbo.vue"
export default {
  name: 'App',

  data(){
    return {
      title: 'hello-vite'
    }
  },
  components: {
    Jumbo
  }
}
</script>

<template>
  <div>
    <Jumbo />
    <h1> {{ title }} </h1>

  </div>
</template>

<style scoped>

</style>