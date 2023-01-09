
<script>
export default {

}
</script>

<template lang="">
      <div class="blue-row-container">
         <div class="text-content">
            <h1>
               Content goes here!
            </h1>
         </div>
      </div>

      <div class="banner-bg">
         <div class="list-main">
            <div class="list-one">
               <h4>
                  DC Comics
               </h4>
               <ul>
                  <li>
                     bla
                  </li>
                  <li>
                     bla
                  </li>
                  <li>
                     bla
                  </li>
                  <li>
                     bla
                  </li>
                  <li>
                     bla
                  </li>
                  <li>
                     bla
                  </li>
                  <li>
                     bla
                  </li>

               </ul>
            </div>
            <div class="list-one">
               <h4>
                  DC Comics
               </h4>
               <ul>
                  <li>
                     bla
                  </li>
                  <li>
                     bla
                  </li>
               </ul>
            </div>
         </div>

            <div class="list-second-main">
               <div class="list-one">
                  <h4>
                     DC Comics
                  </h4>
                  <ul>
                     <li>
                        bla
                     </li>
                     <li>
                        bla
                     </li>
                     <li>
                        bla
                     </li>
                     <li>
                        bla
                     </li>
                     <li>
                        bla
                     </li>
                     <li>
                        bla
                     </li>
                     <li>
                        bla
                     </li>
                     <li>
                        bla
                     </li>
                     <li>
                        bla
                     </li>
                     <li>
                        bla
                     </li>
                     <li>
                        bla
                     </li>

                  </ul>
               </div>
               <div class="list-one">
                  <h4>
                     DC Comics
                  </h4>
                  <ul>
                     <li>
                        bla
                     </li>
                  </ul>
               </div>
            </div>
      </div>
</template>


<style lang="scss">
   .blue-row-container {
      width: 100%;
      height: 150px;
      background-color: rgb(1, 1, 86);

      .text-content{
         color: white;
         margin-left: 10rem;
         padding-top: 3rem;
      }
   }

   .banner-bg{
      height: 550px;
      background-image: url(../assets/img/footer-bg.jpg);
      background-repeat: no-repeat;
      background-size: cover;
      display: flex;
   }

   .list-main{
      margin: 2rem;
   }




   .list-second-main{
      display: flex;
      flex-wrap: wrap;
      margin: 2rem;

      ul{
         color: white;
         list-style-type: none;

         li{
            padding: .4rem;
         }
      }
   }
</style>