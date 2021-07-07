<template>
  <div class="product-card">
      <img :src="prod.thumb"  :alt="prod.titolo">
      <p>{{prod.series}}</p>

  </div>
</template>

<script>
export default {
    name:'Carte',
    props:["prod"]

}
</script>

<style>
p{
    color:white;
text-align:center ;
margin-top:10px;
max-width:200px;
}

</style>