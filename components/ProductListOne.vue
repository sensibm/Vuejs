<template>
  <div id="Product_List_One_F">
      <h2> Product List One </h2>
      <ul>
          <li v-for="product in prod">
            <span class='name'>  @ {{ product.name }}</span>
            <span class='price'> ${{ product.price }}</span>
          </li>
      </ul>
  </div>
</template>

<script>

export default {
    props: ['prod']
}
</script>

<style>

</style>
