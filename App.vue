<template>
  <div id="app">
    <product-list-one v-bind:prod="products"></product-list-one>
    <product-list-two v-bind:prod="products"></product-list-two>
  </div>
</template>

<script>
import ProductListOne from './components/ProductListOne.vue'
import ProductListTwo from './components/ProductListTwo.vue'
export default {
  components: {
    'product-list-one': ProductListOne,
    'product-list-two': ProductListTwo
  },
  name: 'app',
  data() {
    return {
      products: [
        {name: 'Banana Skin', price: 20},
        {name: 'Shiny Star', price: 40},
        {name: 'Green Shell', price: 60},
        {name: 'Red Shell', price: 80}
      ]
    }
    
  }
}
</script>

<style>

</style>
