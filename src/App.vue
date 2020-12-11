<template>
  <div id="app">
    <!-- <Offer /> -->
    <ProductWindowFree />
    <!-- <ProductWindowBusy /> -->
    <!-- <PopupSell /> -->
    <!-- <PopupNotEnoughMoney /> -->
    <!-- <PopupSuccess /> -->
    <!-- <PopupOperation /> -->
  </div>
</template>

<script>
import Offer from '@/components/Offer';
import ProductWindowFree from '@/components/ProductWindowFree';
import ProductWindowBusy from '@/components/ProductWindowBusy';
import PopupSell from '@/components/PopupSell';
import PopupNotEnoughMoney from '@/components/PopupNotEnoughMoney';
import PopupSuccess from '@/components/PopupSuccess';
import PopupOperation from '@/components/PopupOperation';
export default {
  name: 'App',
  components: {
    Offer,
    ProductWindowFree,
    PopupSell,
    PopupNotEnoughMoney,
    PopupSuccess,
    PopupOperation,
    ProductWindowBusy
  }
}
</script>

<style lang="scss">
body {
  margin:0;
  padding:0;
  overflow: hidden;
  font-family: 'Montserrat', sans-serif;
}
h1,h2,h3,h4,h5,h6,p,span,ul,li {
  margin: 0;
  padding: 0;
}
ul {
  list-style: none;
}
#app {
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
