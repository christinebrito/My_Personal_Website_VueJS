<template>
<div id="education" class="education">
    <div class="container">
        <h3 class="text-center"> MY EDUCATION </h3>
        <div class="row">
            <div class="col-md-4">  
                <div class="educ">
                    <div class="effect">
                        <ul>
                        <h4><span> 2012 </span></h4>
                        <h5>Dr. Ruperta G. Caluag Elementary School</h5>
                        <p>Ilang-Ilang, Guiguinto, Bulacan <br><br>
                           <b>Elementary</b>
                        </p><br>                            
                        </ul>
                    </div>
                </div> 
            </div>
            <div class="col-md-4">
                <div class="educ">
                    <div class="effect">
                        <ul>
                        <h4><span> 2018 </span></h4>
                        <h5>Guiguinto National <br> Vocational High School</h5>
                        <p>Poblacion, Guiguinto, Bulacan <br>
                           Junior - Senior High School <br><br>
                           <b>Information and Communications Technology - Programming</b>
                        </p><br>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="educ">
                    <div class="effect">
                        <ul>
                        <h4><span> 2023 </span></h4>
                        <h5>Bulacan State University</h5>
                        <p>City of Malolos, Bulacan <br><br>                               
                       <b> Bachelor of Science in Computer Engineering </b>
                        </p><br>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div> 
</div>
</template>
  
  
  <script>
  export default {
    name: 'EducationSection',
    
  };
  </script>
  
  
  <style>
  .education{
    background-color: #e3dcd0;
    margin-top: -341px;
    padding-top: 80px;
    padding-bottom: 80px;
    }

.education h3{
    font-family: Verdana;
    font-weight: bolder;
    padding-bottom: 30px;
    color: #3D292A;
    }

.education h4{
    font-family: Verdana;
    font-weight: bolder;
    font-size: 20px;
    /* padding-right: 5px;
    padding-left: 5px; */
    padding-top: 50px;
    }

.education h5{
    font-family: Verdana;
    font-weight: bolder;
    font-size: 15px;
    /* padding-right: 5px;
    padding-left: 5px; */
    padding-top: 5px;
    }

.education p{
    font-family: Verdana;
    font-size: 13px;
    /* padding-right: 5px;
    padding-left: 5px; */
    }

.educ{
    color: #FFECCE;
    padding-top: 25px;
    margin-left: 20px;
    width: 90%;
}

.effect{
    background-color: #525564;
    padding: 10px;
    margin-top: 20px;
    border-top-right-radius: 50px;
    padding-bottom: 20px;
    box-shadow: 5px 5px 20px 2px rgba(0, 0, 0, 0.2);
}

.effect:hover{
    background-color: #3D292A;     
    border-top-right-radius: 0;
    border-bottom-left-radius: 0;
    border-top-left-radius: 50px;
    border-bottom-right-radius: 50px;
    transition: 1s;}

  </style>
  