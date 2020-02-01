<template>
  <div>
    home
    <top></top>
    <button @click="open">按钮</button>
  </div>
</template>

<script>
export default {
  data () {
    return {
    }
  },
  components: {},
  mounted() {
    
  },
  methods: {
    open() {
      window.open('https://www.baidu.com?a=1')
    }
  },
  watch: {},
  computed: {}
}
</script>

<style lang='scss' scoped>

</style>