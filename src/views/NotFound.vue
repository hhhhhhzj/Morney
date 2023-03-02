<!--
 * @Author: “hhhhhhzj” “2327475180@qq.com”
 * @Date: 2023-03-02 15:21:13
 * @LastEditors: “hhhhhhzj” “2327475180@qq.com”
 * @LastEditTime: 2023-03-02 15:21:23
 * @FilePath: \morny\src\views\NotFound.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>
  <div>
    <div>你当前页面不存在，请检查网址是否正确</div>
    <div><router-link to="/">返回首页</router-link></div>
  </div>
  
</template>

<script lang="ts">
  export default {
    name: "NotFound"
  }
</script>

<style lang="scss" scoped>

</style>