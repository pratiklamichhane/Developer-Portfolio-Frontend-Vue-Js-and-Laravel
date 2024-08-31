<template>
    <div class="title">
      <h2>Technologies I use</h2>
      <p>List of technologies I'm Familiar with.</p>
   </div>

   <div class="logos-container">
      <img src="../assets/logos/html.png" alt="html" title="HTML"/>   
        <img src="../assets/logos/css.png" alt="css" title="CSS"/>
        <img src="../assets/logos/js.png" alt="js" title="JavaScript"/>
        <img src="../assets/logos/php.png" alt="node" title="PHP"/>
        <img src="../assets/logos/python.png" alt="node" title="Python"/>
        <img src="../assets/logos/laravel.png" alt="node" title="Laravel"/>
        <img src="../assets/logos/django.png" alt="node" title="Django"/>
        <img src="../assets/logos/vue.png" alt="vue" title="Vue"/>
        <img src="../assets/logos/react.png" alt="react" title="React"/>
   </div>
</template>



<script setup>
</script>



<style scoped>
 
   .title{
       display: flex;
       flex-direction: column;
       justify-content: center;
       align-items: center;
       margin-top: 3rem;
       animation: slideInFromRight 1s ease;
   }

   .title h2{
       color : #00ff37;
       font-size: 2.5rem;
       letter-spacing: 0.2rem;
       font-weight: 500;
   }

   .title p{
       font-size: 1.5rem;
       letter-spacing: 0.1rem;
       font-weight: 400;
   }

    .logos-container{
         display: flex;
         flex-wrap: wrap;
         justify-content: center;
         align-items: center;
         gap: 2rem;
         margin-top: 2rem;
         padding: 0 20rem;
         animation: slideInFromLeft 1s ease;
    }

    .logos-container img{
         width: 80px;
         height: 80px;
    }



   @keyframes slideInFromLeft {
       0% {
           transform: translateX(-100%);
       }
       100% {
           transform: translateX(0);
       }
   }

   @keyframes slideInFromRight {
       0% {
           transform: translateX(100%);
       }
       100% {
           transform: translateX(0);
       }
   }





   @media (max-width: 768px){
       .title{
           margin-top: 1rem;
       }

       .title h2{
           font-size: 2rem;
           letter-spacing: 0.1rem;
       }

       .title p{
           font-size: 1rem;
           letter-spacing: 0rem;
       }

         .logos-container{
              padding: 0 2rem;
         }

            .logos-container img{
                width: 50px;
                height: 50px;
            }


   }
</style>