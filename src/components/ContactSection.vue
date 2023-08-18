<template>
<div class="contact" id="contact">
            <div class="container text-center">
                    <h1>contact me</h1>
                    <p>you can contact me as follows</p>

                <div class="row">
                    <div class="col-md-4">
                        <i class="bi bi-envelope-fill"></i>
                        <p>britochristine8@gmail.com</p>
                    </div>

                    <div class="col-md-4">
                        <i class="bi bi-instagram"></i>
                        <p>@engrchristineb</p>
                    </div>

                    <div class="col-md-4">
                        <i class="bi bi-telephone-fill"></i>
                        <p>0926 570 9687</p>
                    </div>
                </div> <br><br>
                <a href="../assets/ChristineBrito_CV.pdf"><button type="button" class="btn btn-primary"><i class="bi bi-cloud-arrow-down-fill"></i> Curriculum Vitae</button></a>
            </div>
</div>
</template>
      
      
<script>
      export default {
        name: 'ContactSection',
        
      };
</script>
      
      
<style>
@import url(https://cdn.jsdelivr.net/npm/bootstrap-icons@1.6.0/font/bootstrap-icons.css);

.contact{
    padding-top: 50px;
    padding-bottom: 50px;
    background: url(../assets/wp6927395.png);    
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
    color: #B31F27;
    font-weight: 700;
    font-family: 'Ubuntu', sans-serif;
    font-weight: lighter;
    }

.contact .row{
    padding: 30x 0;
    font-size: 15px;
    color: #3D292A;;
    background-color: #E7D9C1;
    border-radius: 50%;    
    font-family: 'Ubuntu', sans-serif !important;
    font-weight: lighter;
    }

.contact .row:hover{
    border-radius: 0px;
    }

.contact .col-md-4{
    padding: 10px;
    font-size: 20px;
    }

.contact .btn{
    padding: 10px 25px 10px 25px;
    margin: 5px;
    border-radius: 30px;
    border: 2px solid #B31F27;
    background: transparent;
    color: #B31F27;
    font-family: 'Ubuntu', sans-serif;
    font-weight: lighter;
    }

.contact .btn:focus{
    box-shadow: none !important;}

.contact .btn:hover{
    border: 2px solid green !important;
    background-color: honeydew;
    color: goldenrod;
    transition: 0.6s;
    }

.contact .btn .fa{
    margin-right: 10px;
    }  
</style>
      