<template>
  <div class="hello">
    <h1>{{ title }}</h1>
    <h2>{{ descript }}</h2>
    <span>
      下面是数据分析：
    </span>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      title: '职位分析报告',
      descript: '数据来源：拉勾网'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
a {
  color: #42b983;
}
</style>
