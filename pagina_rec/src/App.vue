<script >
import BarraNavegacion from './components/BarraNavegacion.vue';
import Bienvenida from './components/Bienvenida.vue';
import Carrito from './components/Carrito.vue';
import Banner from './components/Banner.vue';
import ProductosDestacados from './components/ProductosDestacados.vue';
import Footer from './components/Footer.vue';

export default {
  components: {
    BarraNavegacion,
    Bienvenida,
    Carrito,
    Banner,
    ProductosDestacados,
    Footer
  }
};
</script>

<template>
  <BarraNavegacion/>
  <Bienvenida/>
  <Carrito/>
  <Banner/>
  <ProductosDestacados/>
  <Footer/>
</template>

<style scoped>
</style>

