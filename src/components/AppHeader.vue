<script>
export default {
   data() {
      return{
         mainMenu : [
         {
          text : 'characters',
          status: false,
        },
        {
          text : 'comics',
          status: true,
        },
        {
          text : 'movies',
          status: false,
        },
        {
          text : 'tv',
          status: false,
        },
        {
          text : 'games',
          status: false,
        },
        {
          text : 'collectibles',
          status: false,
        },
        {
          text : 'videos',
          status: false,
        },
        {
          text : 'fans',
          status: false,
        },
        {
          text : 'news',
          status: false,
        },
        {
          text : 'shop',
          status: true,
        },
         ]
      }
   }

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
               <li v-for="menuItem in mainMenu" :class="(menuItem.status) ? 'active' : ''">
                   {{ menuItem.text }}
                   </li>
            </li>
         </ul>
      </div>
   </div>

</template>

<style lang="scss">
.container {
   height: 100px;
   width: 100%;
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
         display: inline;
         padding: .7rem;
      }

   }


}

.list-navBar {
   margin: 0 auto;
   display: flex;
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

.active {
      border-bottom: 0.5rem solid #0282f9;
      color: #0282f9;
      }

</style>