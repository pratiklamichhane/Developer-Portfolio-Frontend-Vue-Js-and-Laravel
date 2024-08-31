<template>
    <header>
        <div class="logo">
        <img src="../assets/logo.png" alt="Vue Logo" />
        </div>
      <nav>
        <ul>
          <li><router-link to="/">Home</router-link></li>
          <li><router-link to="/about">About</router-link></li>
            <li><router-link to="/services">Projects</router-link></li>
            <button><router-link to="/contact">Let's Work !</router-link></button>
        </ul>
      </nav>
    </header>
</template>


<script>
export default {
    name: 'AppNavbar'
}
</script>


<style scoped>
   
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 3rem 10rem;
        height: 10vh;
    }

    .logo {
        display: flex;
        align-items: center;
    }

  

    .logo img {
        width: 100px;
        height: 100px;
        border-radius: 50%;
    }

    nav ul {
        display: flex;
        justify-content: space-between;
        align-items: center;
        gap: 5rem;
        list-style: none;
    }

    nav ul li a {
        text-decoration: none;
        color: white;
        font-size: 1.2rem;
        font-weight: 500;
        text-transform: uppercase;
    }

    nav ul li a:hover {
        color: #00ff37;
    }


    nav button {
        padding: 0.5rem 1rem;
        border: none;
        border-radius: 5px;
        background-color: #00ff37;
        color: #333;
        font-size: 1.2rem;
        font-weight: 500;
        cursor: pointer;
    }

    nav button a {
        text-decoration: none;
        color: #333;
        text-transform: capitalize;
    }

    nav button:hover {
        background-color: white;
    }

    nav ul li .router-link-active {
        color: #00ff37; /* Green color for the active route */
    }

    /* ipad responsive */
    @media (max-width: 1024px) {
        header {
            padding: 2rem 5rem;
            gap: 2rem;
        }

        .logo img {
            width: 80px;
            height: 80px;
        }

        nav ul {
            gap: 3rem;
        }

        nav ul li a {
            font-size: 1rem;
        }

        nav button {
            padding: 0.5rem 1rem;
        }

        nav button a {
            font-size: 1rem;
        }
    }

    @media (max-width: 768px) {
        header {
            padding: 1rem 1rem;
            gap: 1rem;

        }

        .logo img {
            width: 50px;
            height: 50px;
        }

        nav ul {
            gap: 1rem;
        }

        nav ul li a {
            font-size: 0.8rem;
        }

        nav button {
            padding: 0.3rem 0.5rem;
        }

        nav button a {
            font-size: 0.8rem;
        }
    }
    

</style>