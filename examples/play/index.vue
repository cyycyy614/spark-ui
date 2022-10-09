<template>
  <div style="margin: 20px;">
    <el-input v-model="input" placeholder="请输入内容"></el-input>
    <login></login>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        input: 'Hello Element UI new!'
      };
  },
    mounted () {
      console.log(this.generateId());
      console.log(this.isEmpty(11));
    },
  };
</script>
