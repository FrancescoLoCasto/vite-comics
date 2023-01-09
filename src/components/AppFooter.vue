
<script>
export default {
   
}
</script>

<template lang="">
   <div class="banner-footer-gray">
      <div class="button-box">

         <div class="button-signUp">
            <h3>
               Sign-Up Now!
            </h3>
         </div>
      </div>
      <div class="social-box">
         <div class="social">
            <h3>
                  Follow us
            </h3>
            <img src="../assets/img/footer-facebook.png" alt="">
            <img src="../assets/img/footer-periscope.png" alt="">
            <img src="../assets/img/footer-pinterest.png" alt="">
            <img src="../assets/img/footer-twitter.png" alt="">
            <img src="../assets/img/footer-youtube.png" alt="">
         </div>
      </div>
   </div>
</template>


<style lang="scss">

   .banner-footer-gray{
      height: 150px;
      background-color: #303030;
      display: flex;
   }
   
   .button-box{
      height: 100%;
      width: 50%;
   }

   .social-box{
      height: 100%;
      width: 50%;
      margin-top: 2rem;
   }

   .button-signUp{
      margin-left: 5rem;
      margin-top: 3rem;
      text-align: center;
      width: 170px;
      border: 1px solid rgb(75, 75, 228);

      h3{
         color: white;
      }
   }

   .social{
      display: flex;

      h3{
         padding: 1rem;
         font-size: 1.5rem;
         color: #6e6e6e;
      }

      img{
         padding: 1rem;
         height: 3rem;
      }
      
   }
</style>