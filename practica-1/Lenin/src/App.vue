<template>
  <div id="app">
    <head></head>
    <body>

      <!-- Primera barra (negra) -->
      <div class="top-bar-black">
          <div style="float: left;" class="logo">TRAIN HARD</div>
          <div class="social-icons">
            <a href="#">Facebook</a>
            <a href="#">Twitter</a>
            <a href="#">Instagram</a>
            
          </div>
      </div>
  
      <!-- Segunda barra (blanca) -->
      <div class="top-bar-white">
          <a href="#">HOME</a>
          <a href="#">SHOP</a>
          <a href="#">ABOUT</a>
          <a href="#">CONTACT</a>
          <a href="#">FAQ</a>
          <a href="#">
          </a>
          
      </div>
  
      <!-- Imagen principal -->
      <div class="main-image"></div>
  
      <!-- Footer con tres cajas -->
      <div class="footer">
          <div class="footer-box box-grey">PROGRESSION</div>
          <div class="footer-box box-white">WORKOUT</div>
          <div class="footer-box box-red">NUTRITION</div>
      </div>
  
  </body>
  </div>
</template>

<style lang="scss">
@import '@/styles/styles.scss';
</style>


<script>


export default {
  
  name: 'App',
  components: {
  }
};
</script>
