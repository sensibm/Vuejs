<template>
  <div id="Product_List_Two_F">
    <h2> Product List Two </h2>
      <ul>
          <li v-for="product in prod">
            <span class='name'>{{ product.name }}</span>
            <span class='price'> ${{ product.price }}</span>
          </li>
      </ul>
  </div>
</template>

<script>

export default {
    props:['prod']
}
</script>

<style>

</style>
