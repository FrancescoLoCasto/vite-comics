
<script>
export default {
   name: 'AppCardMain',
   props: [
            'imageUrl',
            'filmPrice',
            'filmName',
            'filmType'
      ]
}
</script>

<template lang="">
   <div class="card-box">
      <img :src="imageUrl" :alt="filmName">
      <h3>{{ filmName }}</h3>
   </div>
</template>


<style lang="scss">

   .card{
      width: calc((100% / 6))
      

      img{
         width: 250px;
         height: 250px;
      }
   }
</style>