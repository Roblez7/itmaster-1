# itmaster-1
itm- 1
<section>
 body{ background-color: rgb(217, 188, 236);
}
#banner{
   background-image: url(../img/mi\ diseño1.png);
   background-position: center;
   background-size: 100%;
   margin: auto;
   background-repeat: no-repeat;
   min-height: 45vh;
   z-index: 0;
}
section.aboud{
   margin-top: 5%;
}
/*
section.panerl{
   margin-top: 5%;;
}*/
/*  navbar*/
.bg-gris{
   background-color:rgb(10, 10, 10);
   height: 60px;  
   }
.list-group{
    --bs-list-group-bg:trasparent;
}
i.fa-brands.fa-facebook.fa-2xl,
i.fa-brands.fa-instagram.fa-2xl,
i.fa-solid.fa-user.fa-2xl{
    color: rgb(255, 255, 255);;
 }   
i.fa-brands.fa-facebook.fa-2xl:hover{
    color: blue;
 }
 .list-group.list-group-horizontal
{
--bs-list-group-border-color:trasparet;
}
i.fa-brands.fa-instagram.fa-2xl:hover{
    color: rgb(255, 72, 0);
 }
 i.fa-brands.fa-square-twitter.fa-2xl:hover{
    color: rgb(120, 120, 161);
 }
 i.fa-solid.fa-user-lock.fa-2xl:hover{
    color: rgb(168, 101, 231);
 } 
 i.fa-brands.fa-square-twitter.fa-2xl{
    color: rgb(255, 251, 251);;
 } 
 /* foto de perfil*/
 .rounded-circle {
   width: 150px;
   height: 150px;
   -moz-border-radius: 60%;
   -webkit-border-radius: 60%;
   border-radius: 60%;
} 
.rounded-circle.w-125{
   position: absolute;
   z-index: 1;
   background-color: #fff;
   height: auto;
   width: 10rem;
margin-top: -5rem;
margin-left: 8rem !important;
}
/*img:hover{
animation: vibrate 0.5s;
animation-iteration-count: infinite ;
}
@keyframes vibrate {
  0%{ transform: rotate(0deg);} 
  10%{ transform: rotate(-1deg);} 
  20%{ transform: rotate(1deg);} 
  30%{ transform: rotate(0deg);} 
  40%{ transform: rotate(1deg);} 
  50%{ transform: rotate(-1deg);} 
  60%{ transform: rotate(0deg);} 
  70%{ transform: rotate(-1deg);} 
  80%{ transform: rotate(1deg);} 
  90%{ transform: rotate(0deg);} 
  100%{ transform: rotate(-1deg);}  
} para que la img tiemble*/
/* texto debajo de la foto */
.text-start{
   margin-left: 4.5rem;
}
.login{
   height: 90vh;
}
.fotmulario-login{
   margin-top: 10rem;
}
/*panelAd principio*/
#img-perfil{
   left: -0.6rem !important;
   margin-top: -0rem;
}
.list-group{
   --bs-list-group-border-color:trasparet;
}
.lapiz{ 
margin-left: 10rem;
}
/*sobre mi*/
.col8{
   margin-top: -5rem;
   margin-left: 15rem;
}
/*card inicio */
.card{
   --bs-card-bg:trasparet;
   --bs-border-color-translucent:var(--bs-border-color-translucent)
}
.card1:hover{
box-shadow: 5px 50px 20px;
transform: translateY(-3%);
background-color: rgb(217, 175, 245);
}
.card5:hover{
   box-shadow: 5px 50px 20px;
transform: translateY(-3%);
   background-color: rgb(189, 157, 245);
}
/*footer */
</section>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>portfolio1</title>
       <!-- CSS only -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous"> 
     <script src="https://kit.fontawesome.com/87abc5694a.js" crossorigin="anonymous"></script>
     <link rel="stylesheet" type="text/css" href="ASSETS/CSS/style.css">
    </head>
<body> 
  <!--navbar-->  
    <nav class="navbar navbar-expand-lg bg-gris sticky-top">
        <div class="container-fluid">
            <a class="navbar-brand" href="index.html">
                <img src="ASSETS/img/APLogo-20-20.png" alt="" width="15%" height="">
              </a> 
        <ul class="list-group list-group-horizontal">
        <li class="list-group-item"><a href="https://linkedin.com" target="_blank"><i class="fa-brands fa-instagram fa-2xl"></i></a></li>  
        <li class="list-group-item"><a href="https://twitter.com/" target="_blank"><i class="fa-brands fa-square-twitter fa-2xl"></i></a></li>
        <li class="list-group-item"><a href="https://es-la.facebook.com/login/device-based/regular/login/" target="_blank"><i class="fa-brands fa-facebook fa-2xl"></i></a></li>
        <!-- Button trigger modal -->
        <li class="list-group-item"><a href="login.html" class="link-light" ><i class="fa-solid fa-user-lock fa-2xl"></i></a></li>
        </ul>
  <!-- Modal -->
  <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="exampleModalLabel">login</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
            <div class="mb-3 row">
              <label for="staticEmail" class="col-sm-2 col-form-label">Email</label>
              <div class="col-sm-10">
             <input type="text" class="form-control-plaintext" id="staticEmail" value="email@Ejemplo.com">
             </div>
            </div>
              <div class="mb-3 row">
                <label for="inputPassword" class="col-sm-2 col-form-label">Contraceña</label>
                <div class="col-sm-10">
               <input type="password" class="form-control" id="inputPassword">
              </div>
              </div>
        </div>
        <div class="modal-footer">
          <button type="submit" class="btn btn-primary">iniciar sesion</button>
        </div>
      </div>
    </div>
  </div>
        </div>
      </nav> 
      <!--banner-->
      <section>  
      <header id="banner" >
          <div class="container text-center">
            <div class="row">
              <div class="col-3 me-5 ms-5 ">
             <h1></h1> <!--texto sobre el banner-->
              </div>
              <div class="col-3 mt-5">
                <h5> </h5>
              </div>
              <div class="col-3"></div>
              <h1> </h1>
            </div>
          </div> 
      </header> 
      <!--foto de perfil-->
      <img src="ASSETS/img/unafoto (1).png "  class="rounded-circle img-fluid w-125" alt="foto perfil" title="foto de perfil">
      <div>
        <section class="Sobre MI pt-1 mt-1">
        <div class="row">
          <div class="col-3 me-5 ms-5 pt-5 ">
            <!--text debajo de la foto de perfil -->
          <h5 class="text-center text-fluid pt-5  ">Anabel M Roblez</h5>
          <h5 class="text-center text-fluid ">full stack developer jr</h5></div>
          <div class="col-4 pt-5">
            <div class="card   ms-5 card1 " style="width: 40rem;">
              <div class="card-header text-start">
                <h5>Sobre Mi</h5>
              </div>
              <div class="card-body">
                <h5 class="card-title"> Hola soy Anabel Roblez, desarolladora Full stack developer Jr , tengo 25 años y vivo en la provincia de Rio Negro  </h5>
                <p class="card-text pt-3"></p>
              </div>
            </div>
        </div>
      </div>
    </section>
</section>   
       <!--fin-->
           <!---Experiencia Labortal -->
      <section class="Experiencia Labortal pt-5 mt-5">
        <div class="card   ms-5 card1 " style="width: 67rem;">
          <div class="card-header text-start">
            <h4>Experiencia Labortal</h4>
          </div>
          <div class="card-body">
            <h5 class="card-title text-start">Actualmente me encuentro en busca de trabajo. Estoy ocupando mi tiempo en estudios y capacitaciones</h5>
            <p class="card-text pt-3"></p>
          </div>
        </div>
      </section> <!--fin-->
                <!-- Formacion Academica-->          
      <section class="Formacion Academica pt-5 mt-5">
        <div class="card  ms-5 card1 " style="width: 67rem;">
          <div class="card-header text-center">
            <h4>Formacion Academica</h4>
          </div>
          <div class="card-body text-fluid">
            <h5 class="card-title text-start">Primaria :</h5>
            <h6 class="card-title text-start">Escula N°85 Italia. Villa Regina Rio Negro </h6>
            <p class="card-text text-start"> finalizado en 2012</p>
            <h5 class="card-title text-start">Secundario:</h5>
            <h6 class="card-title text-start">C.E.M  N°49 General Enrique Godoy. Rio Negro </h6>
            <h6 class="card-title text-start">Titulo en Perito Mercantil con Especialidad Axiliar en Admindtracion </h6>
            <p class="card-text text-start"> finalizado en 2018</p>
          </div>
        </div>
      </section> <!--fin-->
               <!--Hard & Golft Skills -->
      <section class="Hard & Golft Skills pt-5 mt-5">
        <div class="card  ms-5 card1 " style="width: 70rem;">
          <div class="card-header text-start">
            <h4>Hard & Golft Skills</h4>
          </div>
          <div class="card-body">
            <h5 class="card-title text-start">HTML :</h5>
            <div class="progress" style="height: 20px;">
              <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-label="Basic example"  style="width: 60%;" aria-valuenow="60;" aria-valuemin="60" aria-valuemax="100">60%</div>
            </div>
            <h5 class="card-title text-start">CSS :</h5>
            <div class="progress"style="height: 20px;" >
              <div class="progress-bar progress-bar-striped progress-bar-animated " role="progressbar" aria-label="Basic example" style="width: 49.5%;" aria-valuenow="49.5" aria-valuemin="49.5" aria-valuemax="100">49.5%</div>
            </div>
            <h5 class="card-title text-start">JavaScript:</h5>
            <div class="progress" style="height: 20px;" >
              <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-label="Example with label" style="width: 50%;" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100">50%</div>
            </div>
            <h5 class="card-title text-start"> Angular:</h5>
            <div class="progress" style="height: 20px;" >
              <div class="progress-bar progress-bar-striped progress-bar-animated " role="progressbar" aria-label="Example with label" style="width: 30%;" aria-valuenow="30%" aria-valuemin="0" aria-valuemax="100">30%</div>
            </div>
            <h5 class="card-title text-start">FronEnd:</h5>
            <div class="progress" style="height: 20px;">
              <div class="progress-bar progress-bar-striped progress-bar-animated " role="progressbar" aria-label="Example with label" style="width: 50%;" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100">50%</div>
            </div>
            <h5 class="card-title text-start">BackEnd:</h5>
            <div class="progress" style="height: 20px;">
              <div class="progress-bar progress-bar-striped progress-bar-animated " role="progressbar" aria-label="Example with label" style="width: 5%;" aria-valuenow="5" aria-valuemin="0" aria-valuemax="100">5%</div>
            </div> 
          </div>
        </div>
      </section> <!--fin-->
      <!---idioma -->
      <section class="Idiomas  mt-5">
        <div class="card   ms-5 card1 " style="width: 70rem;">
          <div class="card-header text-start">
            <h4>Idiomas</h4>
          </div>
          <div class="card-body">
            <h5 class="card-title text-start">Ingles</h5>
            <div class="progress" style="height: 20px;">
              <div class="progress-bar progress-bar-striped progress-bar-animated " role="progressbar" aria-label="Example with label" style="width: 50.5%;" aria-valuenow="50.5%" aria-valuemin="0" aria-valuemax="100">50.5%</div>
            </div>
            <h5 class="card-title text-start">Coreano</h5>
            <div class="progress" style="height: 20px;">
              <div class="progress-bar progress-bar-striped progress-bar-animated " role="progressbar" aria-label="Example with label" style="width: 21%;" aria-valuenow="21" aria-valuemin="0" aria-valuemax="100">21%</div>
            </div> 
          </div>
        </div>
      </section> <!--fin-->
 <!---Proyectos -->
 <section class="proyectos  mt-5">
  <div class="card ms-5   " style="width: 80rem;">
    <div class="card-header text-center">
      <h4>Proyectos</h4>
    </div>
    <h5 class="card-title text-center">Actualmente no tengo ningun proyecto. pero estoy trabajdo en eso! </h5>
  </div>
  <div class="row row-cols-1 row-cols-md-3 g-4">
    <div class="col pt-5 mt-5" >  
        <div class="card ms-5 card5 " style="width: 25rem;">
          <div class="card-header text-start">
            <h4>Proyecto </h4>
          </div>
          <div class="card-body">
            <img src="ASSETS/img/proyecto1.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Nombre del project</h5>
              <p class="card-text">Informacio del project..</p>
            </div>
          </div>
        </div>
    </div>
    <div class="col">
      <div class="card h-100 pt-4 mt-5">
          <div class="card   ms-5 card5 " style="width: 25rem;">
            <div class="card-header text-start">
              <h4>Proyecto </h4>
            </div>
            <div class="card-body">
              <img src="ASSETS/img/proyecto1.jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">Nombre del project</h5>
                <p class="card-text">Informacio del project..</p>
              </div>
            </div>
          </div>
      </div>
    </div>
    <div class="col">
      <div class="card h-100 pt-4 mt-5">
          <div class="card   ms-5 card5 " style="width: 25rem;">
            <div class="card-header text-start">
              <h4>Proyecto </h4>
            </div>
            <div class="card-body">
              <img src="ASSETS/img/proyecto1.jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">Nombre del project</h5>
                <p class="card-text"> Informacion del project ...</p>
              </div>
            </div>
          </div>
      </div>
    </div>
  </div>
</section> <!--fin-->      
<footer class="footer text-center bg-gris mt-5">
    <img src="ASSETS/img/APLogo-20-20.png" alt="" width="7%" height="">  
</ul>
</footer>   
<!-- JavaScript Bundle with Popper -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa" crossorigin="anonymous"></script>
</body>
</html>