<template>
  <el-form class="form" ref="form" :model="form" label-width="80px">
    <el-form-item label="商家名称">
      <el-input v-model="form.name"></el-input>
    </el-form-item>
    <el-form-item label="活动名称">
      <el-input v-model="form.name"></el-input>
    </el-form-item>
     <el-form-item label="活动详情">
      <el-input v-model="form.name"></el-input>
    </el-form-item>
    <el-form-item label="logo地址">
      <el-input v-model="form.name"></el-input>
    </el-form-item>
    <el-form-item label="活动时间">
      <el-col :span="11">
        <el-date-picker type="date" placeholder="开始日期" v-model="form.date1" style="width: 100%;"></el-date-picker>
      </el-col>
      <el-col class="line" :span="2">-</el-col>
      <el-col :span="11">
        <el-date-picker type="date" placeholder="结束日期" v-model="form.date2" style="width: 100%;"></el-date-picker>
      </el-col>
    </el-form-item>
    <el-button class="submit" type="primary">添加活动</el-button>
    <div class="inp">
      <el-input placeholder="请输入内容" v-model="input10" clearable></el-input>
      <el-input placeholder="请输入内容" v-model="input10" clearable></el-input>
      <el-button class="submit" type="primary">添加活动</el-button>
    </div>
  </el-form>
</template>


<script>
export default {
  name:"activity",
  data() {
    return {
      form: {
        name: "",
        region: "",
        date1: "",
        date2: "",
        delivery: false,
        type: [],
        resource: "",
        desc: "",
        input10: ""
      }
    };
  },
  methods: {
    onSubmit() {
      console.log("submit!");
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
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
.form[data-v-469af010] {
  width: 600px;
  margin: 40px auto 0;
}
.submit {
  width: 400px;
}
.inp{
  margin-top: 40px;
}
</style>
