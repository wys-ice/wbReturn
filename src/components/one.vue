<template>
  <div>
    <p>one commit</p>
  </div>
</template>

<script>
export default {
  name: 'scroll',
  data () {
    return {
      textArr: [
        '1 第一条公告',
        '2 第二条公告第二条公告',
        '3 第三条公告第三条公告第三条公告',
        '4 one commit'
      ],
      number: 0,
      timer: null
    }
  },
  computed: {
  },
  mounted () {
  },
  methods: {
  }
}
</script>

<style scoped>

</style>
