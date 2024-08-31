<template>
    <div>
    <h1><span>Hey , </span>It's Me Pratik</h1>
    <h1>I'm a <span>Software Developer</span></h1>
    <p>I Develop Apps , Websites and Softwares</p>
     <button class="primary-button">Get In Touch</button>
    </div>
</template>


<script setup>
</script>


<style scoped>
   div{
        margin-top: 3rem;
         display: flex;
         flex-direction: column;
         justify-content: center;
         align-items: center;
         height: 60vh;
           text-align: center;
               animation: slideInFromLeft 1s ease;
   }

   span{
         color: #00ff37;
    }


    h1{
         font-size: 3.5rem;
         letter-spacing: 0.3rem;
         font-weight: 700;
    }

    h2{
         font-size: 2.5rem;
         letter-spacing: 0.2rem;
         font-weight: 500;
    }

    p{
         font-size: 1.5rem;
         letter-spacing: 0.1rem;
         font-weight: 400;
    }

     .primary-button{
           padding: 0.6rem 1.2rem;
           background-color: white;
           color: #000;
           font-size: 1.5rem;
           font-weight: 500;
           border: none;
           border-radius: 1rem;
           cursor: pointer;
           margin-top: 2rem;
     }

     .primary-button:hover{
           background-color: #00ff37;
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
        div{
            height: 35vh;    
            margin-top: 2rem;    
        }
         h1{
            font-size: 2rem;
            letter-spacing: 0.2rem;
         }
         h2{
              font-size: 1.5rem;
         }
         p{
              font-size: 1rem;
              letter-spacing: 0;
         }

           .primary-button{
                 padding: 0.5rem 1rem;
                 font-size: 1rem;
           }
    }



    
</style>