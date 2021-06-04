<template>
  <div id="app">
    <h3>{{title}}</h3>
    <character />
  </div>
</template>

<script>
import character from './components/Character.vue'

export default {
  name: 'app',
  data() {
    return {
      title: "Generate your team"
    }
  },
  components: {
    character
  }
}
</script>
