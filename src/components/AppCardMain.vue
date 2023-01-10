
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
      <h4>{{ filmName }}</h4>
   </div>
</template>


<style lang="scss">

   .card-box{
      padding: 2rem;
      width: calc((100% / 6))

      img{
         width: 200px;
         height: 200px;
      }

      h3{
         color: white;
         font-size: 1rem;
         text-transform: uppercase
      }
   }
</style>