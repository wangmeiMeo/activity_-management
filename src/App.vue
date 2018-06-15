<template>
  <div id="app">
    <!-- 登陆页面 -->
    <div class="login">
      <div class="wrap">
        <div class="logo">
          <h2>商户活动管理系统</h2>
        </div>
        <el-input class="account" placeholder="请输入账号" v-model="input0" clearable></el-input>
        <el-input class="password" placeholder="请输入密码" v-model="input1" clearable></el-input>
        <el-button  class="submit"  type="primary">登录</el-button>
      </div>
      
    </div>
  </div>
</template>
<script>

</script>

<style>
body {
  margin: 0;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.wrap{
   width: 400px;
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  top: 200px;
  margin: auto;
}
.login {
  width: 100%;
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  margin: auto;
  height: 100%;
  background: url(../src/assets/bg.jpg) no-repeat;
}
.account {
  margin: 0px auto 20px;
}
.submit {
  width: 400px;
  margin-top: 30px;
}
h2 {
  margin: 0;
  font-size: 24px;
  line-height: 24px;
  padding: 30px 0;
  display: block;
  text-align: center;
  width: 100%;
  color: #666;
}
</style>
