<template>
    <!-- 登陆页面 -->
    <div class="login" >
      <div class="wrap">
        <div class="logo">
          <h2>商户活动管理系统</h2>
        </div>
       <el-row>  
          <el-col :span="8">  
              <el-input id="name"  v-model="name" placeholder="请输入帐号">  
                  <template slot="prepend">帐号</template>  
              </el-input>   
          </el-col>  
        </el-row>  
        <el-row>  
            <el-col :span="8">  
                <el-input id="password" v-model="password" type="password" placeholder="请输入密码">  
                    <template slot="prepend">密码</template>  
                </el-input>  
            </el-col>  
        </el-row>  
        <el-row>  
            <el-col :span="8">  
                <el-button id="login" v-on:click="check" style="width:100%" type="primary">登录</el-button>  
            </el-col>  
        </el-row>  
      </div>
    </div>
</template>
<style>
.wrap {
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
  background: url(../../src/assets/bg.jpg) no-repeat;
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
#password,#name{
  width: 300px!important;
}
#login{
  width: 370px!important;
}
.el-row{
  margin-bottom: 20px;
}
</style>
