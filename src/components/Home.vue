<template>
  <div>
    <h1>Home Component</h1>
    <Users/>
    <Products />
  </div>
</template>
<script>
import Users from './Users'
import Products from './Products'

export default {
  name:"vue-home",
  components:{
    Users,
    Products
}
}
</script>
<style>
div{ 
    background-color: #dde5ec;
    height: 500px
}
</style>