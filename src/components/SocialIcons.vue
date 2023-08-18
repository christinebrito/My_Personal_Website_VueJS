<template>
    
    <div class="social-icons">
    <ul>
        <a href="https://www.instagram.com/engrchristineb/"><li><i class="bi bi-instagram"></i></li></a>
    </ul>

    <ul>
        <a href="https://www.facebook.com/engr.christineb"><li><i class="bi bi-facebook"></i></li></a>
    </ul>

    <ul>
        <a href="https://t.me/Christinebrito_8"><li><i class="bi bi-telegram"></i></li></a>
    </ul>

    <ul>
        <a href="https://discordapp.com/users/Christine418#0142/"><li><i class="bi bi-discord"></i></li></a>
    </ul>

    <ul>
        <a href="https://twitter.com/christinebrito_"><li><i class="bi bi-twitter"></i></li></a>
    </ul>

    <ul>
        <a href="https://www.snapchat.com/add/tinetine1821?share_id=6X5MTisKIhY&locale=en-US"><li><i class="bi bi-snapchat"></i></li></a>
    </ul>
    </div>
</template>
  

<script >
  export default {
    name: 'SocialIcons',
    
    
  };
</script>
  

<style>
/* Import Bootstrap styles */
@import '~bootstrap/dist/css/bootstrap.css'; /* Adjust the path based on your project structure */

.social-icons{
    top: 50%;
    transform: translateY(-50%);
    position: sticky;
    z-index: 1;
    width: 80px;
    }

.social-icons ul{
    padding: initial;
    }

.social-icons ul li{
    height: 40px;
    width: 40px;
    list-style-type: none;
    padding-left: 12px;
    padding-top: 6px;
    margin-top: 5px;
    background-color: #3D292A;
    color: #FFFF;
    }

.social-icons ul li:hover{
    padding-left: 30px;
    width: 80px;
    transition: 1s;
    }
</style>
  