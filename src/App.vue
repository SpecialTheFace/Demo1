<template>
  <div id="app">
    <form action="./user.jsp">
      用户名文本框：<input class="out" type="text" name="name" /><br />
      年龄文本框：&nbsp;&nbsp; <input class="out" type="text" name="age" /><br />
      <label>性别：</label>
        <input type="radio" name="gender" value="male" />男   <input type="radio" name="gender" value="female" />女<br />
      地址文本框：<input class="out" type="text" name="address" /><br />
      <router-link to="./components/user.vue">提交按钮</router-link>
    </form>
  </div>
</template>

<script>
;``
import User from './components/user.vue'

export default {
  name: 'App',
  components: {
    User
  }
}
</script>

<style lang="less">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
