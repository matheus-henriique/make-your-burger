<template>
  <div id="main-banner">
    <h1>Make Your Burger</h1>
  </div>
</template>

<script>
export default {
  name: 'Banner'
}
</script> 

<style scoped>

  #main-banner {
    background-image: url("/public/img/burger.jpg");
    background-position: center;
    background-size: unset;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }

  #main-banner h1 {
    color: #FFF;
    text-align: center;
    font-size: 22px;
    background-color: #222;
    padding: 20px 40px;
    width: 100%;
  }

  @media (min-width: 512px) {

    #main-banner h1 {
      width: unset;
      font-size: 40px;
    }
  }

  @media (min-width: 1024px) {
    #main-banner h1 {
      font-size: 60px;
    }
  }

</style>