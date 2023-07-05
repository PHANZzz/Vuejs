<template>
  <div>
    <h1>{{ message }}</h1>
    <br>
    <Home/>
  </div>
</template>

<script>
import Home from './components/icons/Home.vue'

export default {
  components: {
    Home
  },
  data() {
    return {
      message: 'Hello'
    }
  }
}
</script>
