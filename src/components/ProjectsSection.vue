<template>
     <div class="title">
       <h2>My Projects</h2>
       <p>Here are some list of the recent projects i've worked on</p>
    </div>

    <div class="projects-card-container">
       <div class="project-card">
              <img src="https://th.bing.com/th/id/OIP.d5YothNl19qfY9PGsRJRFAHaD4?rs=1&pid=ImgDetMain" alt="project1" />
              <div class="card-body">
              <h3>Gym Management System</h3>
              <p>Client : GymSathi</p>
            <p class="tags">React, Node, Express, MongoDB</p>
              </div>
              <div class="card-footer">
                <button>Live Link</button>
                <button>Project Details</button>
              </div>
       </div>

       <div class="project-card">
              <img src="https://th.bing.com/th/id/OIP.d5YothNl19qfY9PGsRJRFAHaD4?rs=1&pid=ImgDetMain" alt="project1" />
              <div class="card-body">
              <h3>Gym Management System</h3>
              <p>Client : GymSathi</p>
            <p class="tags">React, Node, Express, MongoDB</p>
              </div>
              <div class="card-footer">
                <button>Live Link</button>
                <button>Project Details</button>
              </div>
       </div>

       <div class="project-card">
              <img src="https://th.bing.com/th/id/OIP.d5YothNl19qfY9PGsRJRFAHaD4?rs=1&pid=ImgDetMain" alt="project1" />
              <div class="card-body">
              <h3>Gym Management System</h3>
              <p>Client : GymSathi</p>
            <p class="tags">React, Node, Express, MongoDB</p>
              </div>
              <div class="card-footer">
                <button>Live Link</button>
                <button>Project Details</button>
              </div>
       </div>

       <div class="project-card">
              <img src="https://th.bing.com/th/id/OIP.d5YothNl19qfY9PGsRJRFAHaD4?rs=1&pid=ImgDetMain" alt="project1" />
              <div class="card-body">
              <h3>Gym Management System</h3>
              <p>Client : GymSathi</p>
            <p class="tags">React, Node, Express, MongoDB</p>
              </div>
              <div class="card-footer">
                <button>Live Link</button>
                <button>Project Details</button>
              </div>
       </div>

       <div class="project-card">
              <img src="https://th.bing.com/th/id/OIP.d5YothNl19qfY9PGsRJRFAHaD4?rs=1&pid=ImgDetMain" alt="project1" />
              <div class="card-body">
              <h3>Gym Management System</h3>
              <p>Client : GymSathi</p>
            <p class="tags">React, Node, Express, MongoDB</p>
              </div>
              <div class="card-footer">
                <button>Live Link</button>
                <button>Project Details</button>
              </div>
       </div>
    </div>
    <div class="button-container">
    <button class="all-projects-btn">View All Projects</button>
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

    .projects-card-container{
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 2rem;
        flex-wrap: wrap;
        margin-top: 3rem;
        padding: 0 10rem;
        animation: slideInFromLeft 2s ease;
    }

    .project-card{
        width: 300px;
        height: auto;
        border-radius: 1rem;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        transition: transform 0.5s;
        overflow: hidden;
    }

    .project-card img{
        width: 100%;
        height: 50%;
        object-fit: cover;
    }
    .card-body{
        padding: 0.5rem;
        margin-bottom: 1rem;
    }

    .card-body h3{
        font-weight: 500;
        font-size: 1.2rem;
    }

    .card-body p{
        font-size: 0.8rem;
        letter-spacing: 0.1rem;
        font-weight: 400;
    }

    .tags{
        color: #00ff37;
        font-size: 1rem;
        letter-spacing: 0.1rem;
        font-weight: 400;
    }

    .card-footer{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0.5rem 1rem;
        background-color: #00ff37;
        border-radius: 0 0 1rem 1rem;
    }

    .card-footer button{
        padding: 0.5rem 1rem;
        border: none;
        border-radius: 5px;
        background-color: white;
        color: #333;
        font-size: 1rem;
        font-weight: 500;
        cursor: pointer;
    }

    .card-footer button:hover{
        background-color: #000000;
        color: white;
    }

    .project-card:hover{
        transform: scale(1.05);
    }
    .button-container{
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .all-projects-btn{
        margin: auto;
        padding: 0.6rem 1.2rem;
        background-color: white;
        color: #000;
        font-size: 1.2em;
        font-weight: 500;
        border: none;
        border-radius: 1rem;
        cursor: pointer;
        margin-top: 2rem;
    }

    .all-projects-btn:hover{
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

        .projects-card-container{
            padding: 0 2rem;
        }

        .project-card{
            width: 300px;
        }

        .project-card img{
            height: 50%;
        }

        .card-body h3{
            font-size: 1.5rem;
        }

        .card-body p{
            font-size: 0.8rem;
        }

        .tags{
            font-size: 0.8rem;
        }

        .card-footer button{
            padding: 0.5rem 1rem;
            font-size: 0.8rem;
        }

        .all-projects-btn{
            padding: 0.5rem 1rem;
            font-size: 1rem;
        }






    }
</style>