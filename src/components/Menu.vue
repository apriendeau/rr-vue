<script setup>

</script>

<template>
  <nav>
    <ul class="main-nav">
      <li><router-link to="/">home</router-link></li>
      <li><router-link to="/about">about</router-link></li>
    </ul>
  </nav>
</template>

<style lang="less">
  @import "../assets/variables.less";
  nav {
    background: @black;
    width: 100%;
  }
  .main-nav {
    margin: 0;
    padding: 5px 22px;
    list-style-type: none;  
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    & li {
    order: 0;
    text-align: center;
    width: 100%;
      & a {
        display: block;
        padding: 15px 5px;
        text-decoration: none;
        color: @white;
        & :visited {
          text-decoration: none;
          color: @white;            
        }
      }
    }
  }
  @media all and (min-width: 700px) {
    .main-nav{
      justify-content: center;
    }
  }
  
  @media all and (min-width: 960px) {
    .main-nav {
      align-items: flex-start;     
      flex-wrap: nowrap;
      justify-content: left;
      & li {
        order: 1;
        position: relative;
        display: block; 
        width: auto;
      }
    }
  }
</style>