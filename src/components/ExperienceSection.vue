<template>
<div id="experience" class="experience">
    <div class="container">
        <h3 class="text-center"> MY EXPERIENCE </h3>
        <div class="row">
            <div class="col-md-4">  
                <div class="expi">
                <ul>
                    <h4><span> December 2018 </span></h4>
                    <h5>Jan William Corporation Balagtas, Bulacan</h5>
                    <h6>Work Immersion<br>
                       Senior High <br><br>
                       Tasks and tools:
                    </h6>
                    <p>
                        <ul class="timeline">
                            <li>
                                <p><span> Typing Job  </span></p>                           
                            </li>
                            <li>
                                <p><span> Document Printing and Filing </span></p>                           
                            </li>
                            <li>
                                <p><span> Certificate and Receipt Making </span></p>                           
                            </li>
                            <li>
                                <p><span> Customer Support </span></p>                           
                            </li>
                        </ul>
                    </p><br>                            
                </ul>
                </div> 
            </div>
            <div class="col-md-4">
                <div class="expi">
                <ul>
                    <h4><span> June 2022 </span></h4>
                    <h5> Xfnite Computer Services</h5>
                    <h6>Part-time Virtual Labeler <br><br>
                        Tasks and tools:
                    </h6>
                        <p>
                        <ul class="timeline">
                            <li>
                                <p><span> Labeling roofs and buildings  </span></p>                           
                            </li>
                            <li>
                                <p><span> 3d Roof projects </span></p>                           
                            </li>
                            <li>
                                <p><span> Building, tree, and water repair projects </span></p>                           
                            </li>
                        </ul>
                        </p><br>
                </ul>
                </div>
            </div>
            <div class="col-md-4">
                <div class="expi">
                <ul>
                    <h4><span> August 2022 </span></h4>
                                <h5>ICargo Pacific</h5>
                                <h6>Internship <br>
                                   Front-End Developer <br><br>
                                   Tasks and tools:
                                </h6>
                                <p>
                                <ul class="timeline">
                                    <li>
                                        <p><span> Web Design and Development </span></p>                           
                                    </li>
                                    <li>
                                        <p><span> HTML, CSS, Vue.JS, and Bootstrap Framework </span></p>                           
                                    </li>
                                    <li>
                                        <p><span> GitHub and Vercel Deployment </span></p>                           
                                    </li>
                                    <li>
                                        <p><span> Basic Middleware Functions <br> ( Get, Post, and Update ) </span></p>                           
                                    </li>
                                </ul>
                                </p><br>
                </ul>
                </div>
            </div>
        </div>
    </div>    
</div>
</template>
  
  
<script>
  export default {
    name: 'ExperienceSection',
    
  };
</script>
  
  
<style>
.experience{
    background-color: #525564;
    padding-top: 80px;
    padding-bottom: 80px;
    }

.experience h3{
    color: #FFECCE;
    font-family: Verdana;
    font-weight: bolder;
    padding-bottom: 30px;
}

.expi{
    background-color: #E7D9C1;
    border-top-right-radius: 50px;
    border-bottom-left-radius: 50px;
    color: #3D292A;
    padding-top: 25px;
    margin-left: 20px;
    width: 90%;
    box-shadow: 5px 5px 20px 2px rgba(0, 0, 0, 0.2);
}

.expi:hover{   
    border-top-right-radius: 0;
    border-bottom-left-radius: 0;
    border-top-left-radius: 50px;
    border-bottom-right-radius: 50px;
    transition: 1s;
}

.expi p{
    font-family: Verdana;
    font-size: 13px;
    padding-right: 40px;
    }

.expi .p ul{
    padding-left: -50px;
    }

.expi h4{
    font-family: Verdana;
    font-weight: bolder;
    font-size: 18px;
    padding-right: 5px;
    padding-left: 5px;
    padding-top: 5px;
    }

.expi h5{
    font-family: Verdana;
    font-weight: bolder;
    font-size: 15px;
    padding-right: 5px;
    padding-left: 5px;
    padding-top: 5px;
    }

.expi h6{
    font-family: Verdana;
    font-size: 13px;
    padding-right: 5px;
    padding-left: 5px;
    }
</style>
  