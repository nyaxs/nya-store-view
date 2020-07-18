<template>
  <div id="login">
    <ul>
      <li><input placeholder="这里输入用户名"></li>
      <li><input placeholder="这里输入密码"></li>
      <li><button v-on:click="submitMember">提交</button></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'login',
  props: {
    name:String,
    password:String
  },
  method:{
    loginMember: function(){

    },
    submitMember: function () {
      this.loginMember();
    }
  }
}
</script>

<style>
#login {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
