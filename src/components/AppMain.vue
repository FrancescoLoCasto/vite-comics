
<script>
import AppCardMain from './AppCardMain.vue';
export default {
   components:{
         AppCardMain,
            },
            data() {
               return{
                  filmDetails : [
   {
      "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
      "price": "$19.99",
      "series": "Action Comics",
      "type": "comic book"
   },
   {
      "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
      "price": "$3.99",
      "series": "American Vampire 1976",
      "type": "comic book"
   },
   {
      "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
      "price": "$16.99",
      "series": "Aquaman",
      "type": "graphic novel"
   },
   {
      "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
      "price": "$2.99",
      "series": "Batgirl",
      "type": "comic book"
   },
   {
      "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
      "price": "$3.99",
      "series": "Batman",
      "type": "comic book"
   },
   {
      "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
      "price": "$2.99",
      "series": "Batman Beyond",
      "type": "comic book"
   },
   {
      "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
      "price": "$3.99",
      "series": "Batman/Superman",
      "type": "comic book"
   },
   {
      "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
      "price": "$4.99",
      "series": "Batman/Superman Annual",
      "type": "comic book"
   },
   {
      "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
      "price": "$5.99",
      "series": "Batman: The Joker War Zone",
      "type": "comic book"
   },
   {
      "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
      "price": "$6.99",
      "series": "Batman: Three Jokers",
      "type": "comic book"
   },
   {
      "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
      "price": "$4.99",
      "series": "Batman: White Knight Presents: Harley Quinn",
      "type": "comic book"
   },
   {
      "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
      "price": "$16.99",
      "series": "Catwoman",
      "type": "graphic novel"
   }
   ]    
               }
            }
}
</script>

<template lang="">

      <div class="jumbotron-container">  
      </div>


      <div class="blue-row-container">
         <div class="text-content">
            <AppCardMain
            v-for="details in filmDetails" :imageUrl="details.thumb" :filmPrice="details.price" :filmName="details.series" :filmType="details.type"
            />
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

   .jumbotron-container{
      width: 100%;
      height: 600px;
      background-image: url(../assets/img/jumbotron.jpg);
   }


   .blue-row-container {
      background-color: #1c1c1c;

      .text-content{
         color: white;
         margin-left: 10rem;
         padding-top: 3rem;
         display: flex;
         flex-wrap: wrap;
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