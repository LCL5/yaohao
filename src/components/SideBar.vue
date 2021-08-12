<template>
  <div class="sideBar">
    <!--跳转到哪里就去to哪里，写路径-->
    <router-link to="">
      <button @click="getMethod" class="button">导入学生信息</button>
    </router-link>
    <router-link to="">
      <button @click="getMethod" class="button">抽取学生</button>
    </router-link>
    <router-link to="">
      <button @click="getMethod" class="button" >导出学生信息</button>
    </router-link>
  </div>
</template>

<script>
export default {
  name: 'SideBar',
  mounted(){
  }

}
</script>
<style>
  .sideBar{
    width: 13%;
    height: 600px;
    background-color:#0f4a7b;
    float: left;
  }
  button{
    width: 95%;
    color: white;
    height: 60px;
    margin-top: 35px;
    font-size: 20px;
    font-family: 'Times New Roman', serif;
    background-color: #0f79c3;
    border: 2px solid #80daf7;
    border-radius: 5px;
  }
  button hover{
    color:red;
  }
</style>
