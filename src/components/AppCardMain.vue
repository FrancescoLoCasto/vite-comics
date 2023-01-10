
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
      <p>{{ filmName }}</p>
   </div>
</template>


<style lang="scss">

   .card-box{
      padding: 2rem;
      width: calc((100% / 6))

      img{
         width: 100%;
         height: 100%;
      }

      span{
         color: white;
         font-size: 1rem;
         text-transform: uppercase
      }
   }
</style>