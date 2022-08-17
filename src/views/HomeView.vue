<template>
  <Banner />
  <div class="main-container">
    <h1>Monte o seu burger:</h1>
    <Burgerform />
  </div>
</template>

<script>
import Banner from '../components/Banner.vue'
import Burgerform from '../components/Burgerform.vue'
export default {
  name: 'Home',
  components: {
    Banner,
    Burgerform
  }
}
</script>

<style scoped>
  
  h1 {
    font-size: 22px;
    
  }

  @media (min-width: 512px) {

    h1 {
      font-size: 30px;
    }
  }

  @media (min-width: 1024px) {
    h1 {
      font-size: 40px;
    }
  }
</style>


