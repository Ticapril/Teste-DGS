<template>
    <div class="banner">
      <div class="banner-container"><h1 class="header">STARK MARINE SHIPYARD</h1><h2 class="sub-header">Welcome aboard!</h2></div>
      <img src="https://stark-marine.com/wp-content/uploads/2019/10/img_barco1.png" alt="Oceano Azul">
    </div>
</template>
  
  <script>
  export default {
    name: 'Banner',
  }
  </script>
  
  <style scoped>
    .banner-container {
      padding: 20px;
    }
    .header, .sub-header {
      margin:0;
      color: #fff;
      text-align: center;
    }
    .banner img{
      width: 100%;
      height: 100%;
    }
    .banner {
      background-image: url('https://stark-marine.com/wp-content/uploads/2019/09/bg_slider.png');
    }
  </style>