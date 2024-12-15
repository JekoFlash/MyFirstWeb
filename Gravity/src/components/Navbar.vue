<script>
export default {
    name:"NavbarGravity",
    data(){
        return{
            message: "Navbar จ้า"
        }
    }
}
</script>

<template>
 <nav>
    <div class="Nav-container">
        <div class="nav-con">
            <img src="../assets/logo-light.png.png" style="width: 180px; height: 42px;"/>
            <ul class="menu">
                <li><a href="#">ABOUT US</a></li>
                <li>
                    <a href="#">OUR SERVICES </a>
                    <img src="../assets/drop.png" style="width: 15px; height: 15px;"/>
                    
                </li>
                
                <li><a href="#">WORK WITH US</a></li>
                <li><a href="#">BLOG</a></li>
            </ul>
            <div class="circle">
                <p>GET IN TOUCH</p>
            </div>
        </div>
    </div>
 </nav>
</template>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    nav {
        background-color: black;
    }
    
    .Nav-container {
        max-width: 1600px;
        margin: 0 auto;

    }

    .nav-con {
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 88px;
        
    }

    .menu {
        display: flex;
    }

    .menu li{
        list-style: none;
        margin: 2rem;
    }

    .menu li a {
        color: white;
    }

    a {
        color: white;
        text-decoration: none;
    }

    p {
        color: white;
        text-decoration: none;
    }

    .logo {
        font-size: 1.5rem;
    }

    .circle {
      width: 10px;
      height: 10px;
      background: linear-gradient(135deg, #665DCD 0%, #5FA4E6 44.76%, #D2AB67 100%);
      display: flex;
      align-items: center;
      border-radius: 50%;
      margin: 5rem;
  }
    
    .circle p {
        color: white;
        font-size: 15px;
        margin: 1rem;
    }

    @media screen and (max-width: 360px){
        .nav-con{
            padding: 3rem 0;
            flex-direction: column;
            height: auto;
        }
    }
</style>

