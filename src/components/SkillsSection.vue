<template>
<div id="skills" class="skills">
        <div class="row">
            <h3 class="text-center"> MY SKILLS & LANGUAGES </h3>

            <div class="col-md-1">
            </div>

            <div class="col-md-5">
                
                <div class="skills-bar" >
                    <p>Microsoft Office Applications ( Word | Excel | PowerPoint )</p>
                    <div class="progress">
                        <div class="progress-bar" style="width: 90%;">90%</div>
                    </div>

                    <p>Social Media Management</p>
                    <div class="progress">
                    <div class="progress-bar" style="width: 90%;">90%</div>
                    </div> 

                    <p>Software Troubleshooting</p>
                    <div class="progress">
                        <div class="progress-bar" style="width: 75%;">75%</div>
                    </div>
            
                    <p>Photo Editing ( Photoshop | Lightroom | Canva )</p>
                    <div class="progress">
                    <div class="progress-bar" style="width: 85%;">85%</div>
                    </div>

                    <p>HTML | CSS</p>
                    <div class="progress">
                    <div class="progress-bar" style="width: 90%;">90%</div>
                    </div>

                    <p>JavaScript</p>
                    <div class="progress">
                    <div class="progress-bar" style="width: 80%;">80%</div>
                    </div>
                </div>          
            </div>

            <div class="col-md-5">
                <div class="skills-bar" >
                    <p>Java | Python | C++</p>
                    <div class="progress">
                    <div class="progress-bar" style="width: 75%;">75%</div>
                    </div>

                    <p>PHP</p>
                    <div class="progress">
                    <div class="progress-bar" style="width: 80%;">80%</div>
                    </div>

                    <p>Vue.js Framework</p>
                    <div class="progress">
                    <div class="progress-bar" style="width: 80%;">80%</div>
                    </div>

                    <p>Bootstrap Framework</p>
                    <div class="progress">
                    <div class="progress-bar" style="width: 85%;">85%</div>
                    </div>
                    <br>
                                        
                    <p>Filipino</p>
                    <div class="progress">
                    <div class="progress-bar" style="width: 100%;">100%</div>
                    </div>

                    <p>English</p>
                    <div class="progress">
                    <div class="progress-bar" style="width: 75%;">75%</div>
                    </div>
                </div><br><br><br>
            </div>
        </div>
</div>
</template>
      
      
<script>
      export default {
        name: 'SkillsSection',
        
      };
</script>
      
      
<style>
.skills{
    background-color: #525564;
    } 

.skills h3{
    padding-top: 80px;
    padding-bottom: 30px;
    font-family: Verdana;
    font-weight: bolder;
    color: #FFECCE;
    }
    
.skills-bar p{
    margin-bottom: 6px;
    font-weight: 500;
    color: #FFECCE;
    }
     
.progress{
    border-radius: 16px !important;
    margin-bottom: 10px;
    background-color: #E7D9C1 !important;
    border-style: double;
    border-color: #3D292A;
    width: 95%;
    }
     
.progress-bar{
    border-radius: 16px;
    background-color: #3D292A !important;
    }

</style>
      