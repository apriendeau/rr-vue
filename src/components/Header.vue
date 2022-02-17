<script setup>

</script>

<template>
  <div class="header">
    <div class="title">
      <h1>riptide rhythm</h1>
    </div>
  </div>
</template>

<style lang="less">
  @import "../assets/variables.less";
  .header {
    height: 250px;
    background-color: #2a2a2a;
    padding: 10px;
    display: flex;
    flex-direction: column;
    & .title{
      margin-top: auto;
      align-self: flex-start;
      width: auto;
      padding: 0px 10px;
      & h1 {
        color: @white;
        font-size: 2.1em;
        padding: 5px;
        margin: 0 0 -25px 0;
      }
    }
  }

</style>