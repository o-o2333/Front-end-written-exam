<template>
  <div class="home">
    <div class="right">
      <div class="user"><p class="el-icon-user"></p>You</div>
      <div class="seachtext">猪八戒</div>
    </div>
    <div class="left">
      
      <div class="left_user" ><p class="el-icon-edit-outline"></p>面试展示</div>
      <div >猪八sdfsdasdasdfsdfsxfggggggggfsdfsdgdffssfsdfsdfsdfadf戒</div>
    </div>

    <div style="margin-top: 15px;">
  <el-input placeholder="请输入内容" v-model="input3" class="input-with-select">
  
    <el-button slot="append" icon="el-icon-search"></el-button>
  </el-input>
</div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  
  },
  data(){
   return{
  input3:""
   }
  }
};
</script>
<style scoped>
.right {
  margin-top: 20px;
  width: 200px;
  height: 100%;
  float: right;
  background-color: #ffff;
  box-shadow: 2px 1px 20px rgb(201, 199, 199);
  border-radius: 5px;
  text-align: left;
}
.user {
    color: #FFFF;
  border-radius: 5px 5px 0px 0px;
  background-color: #2067c6;
  height: 50px;
  line-height: 50px;
  bottom: 10px;
}
.seachtext {
  height: 50px;
  line-height: 50px;
}
.left{
  margin-top: 20px;
  width: 200px;
  height: 100%;
  float: left;
  background-color: #ffff;
  box-shadow: 2px 1px 20px rgb(201, 199, 199);
  border-radius: 5px;
  text-align: left;
   word-wrap:break-word;
  word-break: break-all;
}
.left_user{
  color: #FFFF;
   border-radius: 5px 5px 0px 0px;
  background-color: #28780f;
  height: 50px;
  line-height: 50px;
  bottom: 10px;
}
.input-with-select{
 
      position: fixed;
  bottom: 0;
  width: 100%;
  height: var(--footer-height);
  left: 0px;

}
</style>
