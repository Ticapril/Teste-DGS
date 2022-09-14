<template>
  <menu class="menu">
    <a><img src="https://stark-marine.com/wp-content/uploads/2019/09/logo_stark-1.png" alt="logo DGS" class="image"/></a>
    <li class="item" @click="show = !show"><a href="">Home</a></li>
    <li class="item"><a href="">About Us</a></li>
    <li class="item"><a href="">Contact</a></li>
    <li class="item"><a href="">Products</a></li>

  </menu>
</template>
  
<script>
export default {
  name: 'Header',
  data() {
    return {
      show: false
    }
  }
}
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.menu {
  font-size: 25px;
  display: grid;
  grid-auto-flow: column;
  justify-content: center;
  background-color: #5959b7;
}

.menu li {
  list-style: none;
  padding: 20px;
  text-transform: uppercase;
  font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
  font-weight: 300;
  display: grid;
  align-items: center;
}

.menu a {
  text-decoration: none;
  color: #fff;
}
.image {
  width: 100%;
  height: 100%;
}
</style>
  