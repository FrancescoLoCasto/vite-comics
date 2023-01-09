
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

      <div class="banner-blue-bonus">

      </div>

      <div class="banner-bg">

         <div class="container-list">
            <div class="list-main">
            <div class="list-one">
               <h4>
                  DC Comics
               </h4>
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
                     Videos
                  </li>
                  <li>
                     News
                  </li>

               </ul>
            </div>
            <div class="list-one">
               <h4>
                  Shop
               </h4>
               <ul>
                  <li>
                     shop DC
                  </li>
                  <li>
                     Shop DC Collectibles
                  </li>
               </ul>
            </div>
         </div>

            <div class="list-second-main">
               <div class="list-one">
                  <h4>
                     DC 
                  </h4>
                  <ul>
                     <li>
                        Terms Of Use
                     </li>
                     <li>
                        Privacy policy (new)
                     </li>
                     <li>
                        Ad Choices 
                     </li>
                     <li>
                        Advertising
                     </li>
                     <li>
                        Jobs
                     </li>
                     <li>
                        Subscriptions
                     </li>
                     <li>
                        Talent Worckshops
                     </li>
                     <li>
                        CPSC Certificates
                     </li>
                     <li>
                        Ratings
                     </li>
                     <li>
                        Shop Help
                     </li>
                     <li>
                        Contact Us
                     </li>

                  </ul>
               </div>
               <div class="list-one">
                  <h4>
                     Sites
                  </h4>
                  <ul>
                     <li>
                        DC
                     </li>
                     <li>
                        MAD Magazine
                     </li>
                     <li>
                        DC Kids
                     </li>
                     <li>
                        DC Universe
                     </li>
                     <li>
                        DC Power Visa
                     </li>
                  </ul>
               </div>
            </div>

         </div>
         <div class="img-logo-transp">
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

   .container-list{
      display: flex;
      width: 50%;
   }

   .banner-bg{
      height: 550px;
      padding: 2rem;
      background-image: url(../assets/img/footer-bg.jpg);
      background-repeat: no-repeat;
      background-size: cover;
      display: flex;

      h4{
         color: white;
         font-size: 1.2rem;
         margin-left: 3rem;
      }
   }

   .list-one{
      padding: 2rem;

      ul{
         color: rgb(184, 184, 184);
         list-style-type: none;

         li{
            padding: .4rem;
         }
      }
   }




   .list-second-main{
      display: flex;
      flex-wrap: wrap;

      ul{
         color: rgb(184, 184, 184);
         list-style-type: none;

         li{
            padding: .4rem;
         }
      }
   }

   .img-logo-transp{
   width: 70%;
   background-image: url(../assets/img/dc-logo-bg.png);
   background-repeat: no-repeat;
   background-size: 800px;
   }

   .banner-blue-bonus{
      height: 200px;
      background-color: rgb(61, 61, 224);
   }
</style>