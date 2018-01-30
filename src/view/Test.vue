<template>
  <div class="hello">
    <h1>xcvz{{ msg }}cccccccccccccccccc</h1>
    <h2>project-test</h2>
    <ul>
      <li>
        <!-- target="_self":默认在同一框架中打开 -->
        <a
          href="https://www.baidu.com"
          target="_self"
        >
          百度一下-test-test
        </a>
      </li>
      <li>
        <!-- target="_self":默认在同一框架中打开 -->c
        <a
          href="https://www.baidu.com"
        >
          Example-test
        </a>
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
