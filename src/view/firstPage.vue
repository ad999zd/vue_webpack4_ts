<template>
  <div class='first-page'>
    {{msg}}
  </div>
</template>

<script lang='ts'>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  created () {
    let name: string = "bob"
    name = "Welcome to Your Vue.ts App"
    this.msg = name
  },
  methods: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .first-page{
    font-size: .28rem;
  }
</style>
