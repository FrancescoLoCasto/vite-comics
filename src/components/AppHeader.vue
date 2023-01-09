<script>
export default {

}
</script>

<template>
   <div class="container">

      <div class="logo-img">
         <img src="../assets/img/dc-logo.png" alt="">
      </div>
      <div class="list-navBar">
         <ul>
            <li>
               Characters
            </li>
            <li>
               Comics
            </li>
            <li>
               Movies
            </li>
            <li>
               TV
            </li>
            <li>
               Games
            </li>
            <li>
               Collectibles
            </li>
            <li>
               videos
            </li>
            <li>
               fans
            </li>
            <li>
               news
            </li>
            <li>
               shop
            </li>
         </ul>
      </div>
   </div>

</template>

<style lang="scss">
.container {
   height: 100px;
   width: 100%;
   background-color: rgb(2, 213, 104);
   padding: 0;
   display: flex;
   flex-wrap: wrap;

   ul {
      width: 100%;
      padding: 0;
      margin-left: 20rem;
      display: flex;
      list-style-type: none;

      li {
         padding: .7rem;
      }

   }


}

.list-navBar {
   width: 305px;
}

.logo-img {
   width: 105px;

   img{
      height: 70px;
      padding: 1rem;
      margin-left: 3rem;
   }
}
</style>