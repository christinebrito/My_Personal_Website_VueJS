<template>
<!-- TABS SECTION - HOME, ABOUT, EDUC, SKILL, CONTACT -->
    <section id="user-info">
        <div class="nav-bar">
            <nav class="navbar navbar-expand-lg navbar-light">               
<!-- LEFT-SIDE LOGO -->
                <a class="navbar-brand" href="#"><img src="../assets/logo2.png" alt="logo"></a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
<!-- BOOTSTRAP ICON -->
                <i class="bi bi-layout-sidebar-inset"></i>
                </button>
<!-- NAVIGATION MENU -->
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link" aria-current="page" href="#top">HOME</a>
                        </li>

                        <li class="nav-item">
                            <a class="nav-link" href="#about">ABOUT ME</a>
                        </li>

                        <li class="nav-item">
                            <a class="nav-link" href="#education">EDUCATION</a> 
                        </li>

                        <li class="nav-item">
                            <a class="nav-link" href="#experience">EXPERIENCE</a> 
                        </li>

                        <li class="nav-item">
                            <a class="nav-link" href="#certificate">CERTIFICATIONS</a>
                        </li>

                        <li class="nav-item">
                            <a class="nav-link" href="#skills">SKILLS & LANGUAGES</a>
                        </li>

                        <li class="nav-item">
                            <a class="nav-link" href="#contact">CONTACT</a>
                        </li>                      
                    </ul>
                </div>
            </nav>
        </div>
    </section>
 
</template>
  

<script>
  export default {
    name: 'NavBar',
    
  };
</script>
  

<style>
.nav-bar{
    top: 0;
    position: sticky;
    z-index: 2;
}

.navbar{
    background-color: #E7D9C1;
    box-shadow: 5px 5px 20px 2px rgba(0, 0, 0, 0.2);
    opacity: 80%;
    font-weight: bold;
    }

.navbar-brand img{
    height: 30px;
    padding-left: 10px;
    }

.nav-bar .bi bi-layout-sidebar-inset{
    font-size: 35px;
    color: rgb(0, 38, 255);
    }

.navbar-toggler{
    outline: none !important;
    }

.navbar-nav{
    float: left;
    text-align: left;
    margin-right: auto;
    }

.nav-link{
   color: #000000 !important;
   font-weight: 600;
   font-weight: bold;
    }

.nav-link:hover{
   color: #ed0d18 !important;
    }
</style>
  