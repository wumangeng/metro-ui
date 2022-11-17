<template>
    <div class="main">
      <el-row :gutter="20">
      <el-col :span="6">
        <div class="grid-content bg-purple">
          <h1>1</h1>
      </div>
    </el-col>
      <el-col :span="6">
        <div class="grid-content bg-purple">
          <h1>2</h1>
        </div>
      </el-col>
      <el-col :span="6">
        <div class="grid-content bg-purple">
          <h1>3</h1>
        </div>
      </el-col>
      <el-col :span="6">
        <div class="grid-content bg-purple">
          <h1>4</h1>
        </div>
      </el-col>
    </el-row>
    </div>
  </template>
  
  <script>
  export default {
    name: 'main',
    data () {
      return {
        
      }
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  .el-row {
      margin-bottom: 20px;
      
    }
    .el-row:last-child {
        margin-bottom: 0;
      }
    .el-col {
      border-radius: 4px;
    }
    .bg-purple-dark {
      background: #99a9bf;
    }
    .bg-purple {
      background: #d3dce6;
    }
    .bg-purple-light {
      background: #e5e9f2;
    }
    .grid-content {
      border-radius: 4px;
      min-height: 36px;
    }
    .row-bg {
      padding: 10px 0;
      background-color: #f9fafc;
    }
  </style>
  