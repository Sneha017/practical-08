: <!Doctype html> 
<html> 
<head> 
<title>Bookstrap</title> 
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" 
integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous"> 
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-
IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script> 
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script> 
</head> 
<body> 
<nav class="navbar navbar-expand-lg navbar-light bg-light"> 
  <div class="container-fluid"> 
    <a class="navbar-brand" href="#">Navbar</a> 
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-
target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" arialabel="Toggle navigation"> 
      <span class="navbar-toggler-icon"></span> 
    </button> 
    <div class="collapse navbar-collapse" id="navbarSupportedContent"> 
      <ul class="navbar-nav me-auto mb-2 mb-lg-0"> 
        <li class="nav-item"> 
          <a class="nav-link active" aria-current="page" href="#">Home</a> 
        </li> 
        <li class="nav-item"> 
          <a class="nav-link" href="#">Link</a> 
        </li> 
        <li class="nav-item dropdown"> 
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bstoggle="dropdown" aria-expanded="false"> 
            Dropdown           </a> 
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown"> 
            <li><a class="dropdown-item" href="#">Action</a></li> 
            <li><a class="dropdown-item" href="#">Another action</a></li> 
            <li><hr class="dropdown-divider"></li> 
            <li><a class="dropdown-item" href="#">Something else here</a></li> 
          </ul> 
        </li> 
        <li class="nav-item"> 
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a> 
        </li> 
      </ul> 
      <form class="d-flex"> 
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">         <button class="btn btn-outline-success" type="submit">Search</button>       </form> 
    </div> 
  </div> 
</nav> 
<div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel"> 
  <div class="carousel-inner" style="height:400px;"> 
    <div class="carousel-item active"> 
     <img src="image1.jpg" class="d-block w-100" alt="...">  
    </div> 
    <div class="carousel-item" style="text-align:center;margin-top:100px;"> 
      <div class="spinner-border" role="status"> 
  <span class="visually-hidden">Loading...</span> 
</div> 
    </div> 
    <div class="carousel-item"> 
      <img src="image2.jpg" class="d-block w-100" alt="..."> 
    </div> 
 <div class="carousel-item"> 
      <img src="image3.jpg" class="d-block w-100" alt="..."> 
    </div> 
  </div> 
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bsslide="prev"> 
    <span class="carousel-control-prev-icon" aria-hidden="true"></span> 
    <span class="visually-hidden">Previous</span> 
  </button> 
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bsslide="next"> 
    <span class="carousel-control-next-icon" aria-hidden="true"></span> 
    <span class="visually-hidden">Next</span> 
  </button> 
</div> 
<section class=""> 
  <!-- Footer --> 
  <footer class="text-center text-white" style="background-color: #0a4275;"> 
    <!-- Grid container --> 
    <div class="container p-4 pb-0"> 
      <!-- Section: CTA --> 
      <section class=""> 
        <p class="d-flex justify-content-center align-items-center"> 
          <span class="me-3">Register for free</span> 
          <button type="button" class="btn btn-outline-light btn-rounded">             Sign up! 
          </button> 
        </p> 
      </section> 
      <!-- Section: CTA --> 
    </div> 
    <!-- Grid container --> 
    <!-- Copyright --> 
    <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">       © 2020 Copyright: 
      <a class="text-white" href="https://mdbootstrap.com/">MDBootstrap.com</a> 
    </div> 
    <!-- Copyright --> 
  </footer> 
  <!-- Footer --> 
</section> 
</body> 
</html> 
 
