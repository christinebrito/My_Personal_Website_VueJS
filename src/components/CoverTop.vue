<template>
    <div>
        <section id="header">
            <div class="containertextcentre">
                <div class="userbox">
                    <img src="../assets/profile_pic1.png">
                    <h1>CHRISTINE BRITO</h1>
                    <p>BS in Computer Engineering</p>
                </div>
            </div>
            <div class="scroll-btn">
                <div class="scroll-bar">
                    <a href="#about"><span></span></a>
                </div>
            </div>
        </section>
    </div>
</template>
  

<script>
  export default {
    name: 'CoverTop',
    
  };
</script>
  

<style>
    
#header{
    height: 100vh;
    background: url("../assets/wallpaper.jpg");
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
    }

.userbox{
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    position: absolute;
    }

.userbox img{
    border-radius: 50%;
    width: 250px;
    border: 4px double #FFECCE;
    }

.userbox p{
    position: relative;
    animation: mymove 3s infinite;
    }

@keyframes mymove {
    0%   {top: 0px;}
    50%  {top: 8px;}
    100% {top: 0px;}
    } 

.userbox h1{
    background-color: #FFECCE;
    color: #b31f27;
    font-family: 'Ubuntu', sans-serif;
    font-weight: 500;
    font-size: 30px;
    text-align: center;
    margin: 10px;
    border-top-left-radius: 0px;
    border-bottom-right-radius:0px;
    border-top-right-radius: 50px;
    border-bottom-left-radius: 50px;
    }

.userbox h1:hover{
    color: #b31f27;
    border-top-right-radius: 0;
    border-bottom-left-radius: 0;
    border-top-left-radius: 50px;
    border-bottom-right-radius: 50px;
    transition: 1s;
    }

.userbox p{
    background-color: #FFECCE;
    color: #b31f27;
    font-family: 'Baloo Bhaina 2', cursive;
    text-align: center;
    font-weight: bolder;
    font-size: 20px;
    }

.scroll-btn{
    margin-top: 300px;
    bottom: 30px;
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    border: 2px solid #FFECCE;
    padding: 10px 10px 20px;
    border-radius: 30px;
    }

.scroll-bar span{
   border:2px solid #FFECCE;
   font-size: 10px;
   border-radius: 30px;
    }

.scroll-bar{
    animation: mover 1s infinite alternate;}
@keyframes mover {
    0%{
        transform: translateY(0);
    }
    100%{
        transform: translateY(10px);
    }
    }
</style>
  