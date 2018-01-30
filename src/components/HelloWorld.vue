<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>project-test</h2>
    <ul>
      <li>
        <!-- target="_self":默认在同一框架中打开 -->
        <a
          href="https://www.baidu.com"
          target="_self"
        >
          百度一下
        </a>
      </li>
      <li>
        <router-link to="test">Example click</router-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '欢迎来到菜鸟教程！！！！！！'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
