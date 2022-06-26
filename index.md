<!doctype html>
<html lang="ar" dir="rtl">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" type="text/css" href="bootstrap.min.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.rtl.min.css" integrity="sha384-gXt9imSW0VcJVHezoNQsP+TNrjYXoGcrqBZJpry9zJt8PCQjobwmhMGaDHTASo9N" crossorigin="anonymous">

    <title>MENU</title>
    <script type="text/javascript" src="js/jquery-3.1.1.min.js"></script>
    <script src="https://kit.fontawesome.com/5ffd3c4e9b.js" crossorigin="anonymous"></script>
<script type="text/javascript" src="js/bootstrap.min.js"></script>


    <style>
      *{
        padding:0;
        margin:0;
    }
    
    body{
        background-color:#000;
    }
    .content-center{
        height:10vh;
        display:flex;
        justify-content:center;
        align-items:center;
    }
    
    ul{
        display:flex;
        list-style:none;
    }
    
    
    @media (max-width:800px) {
        ul {
            display: block
        }
    }
    
    ul li{
        margin:30px;
        height:60px;
        width:70px;
        display:flex;
        justify-content:center;
        align-items:center;
        border-radius:50%;
        cursor:pointer;
        position:relative;
        
    }
    
    ul li i{
        transition:all 0.3s linear;
    }
    
    
    ul li:hover i{
        color:#fff;
        font-size:40px;
    }
    
    ul li:hover::after{
        opacity:1;
        transform:scale(0.8);
       
    }
    
    ul li::after{
        content:"";
        position:absolute;
        height:inherit;
        width:inherit;
        border-radius:50%;
        opacity:0;
        z-index:-1;
        transition:all 0.2s linear;
        
    }
    
    ul li:nth-child(1){
        
        border:2px solid #3b5998;
        color:#3b5998;
    }
    
    ul li:nth-child(1)::after{
        
        background-color:#3b5998;
         color:#3b5998;
    }
    
    
    ul li:nth-child(2){
        
        border:2px solid #00aced;
        color:#00aced;
    }
    
    ul li:nth-child(2)::after{
        
        background-color:#00aced;
         color:#00aced;
    }
    
    
    ul li:nth-child(3){
        
        border:2px solid #b60000;
        color:#b60000;
    }
    
    ul li:nth-child(3)::after{
        
        background-color:#b60000;
         color:#b60000;
        
    }
    
    
    </style>
  </head>
  <body>
  <div class="container">
	<div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="menu/1.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/2.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/3.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/4.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/5.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/6.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/7.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/8.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/9.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/10.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/11.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/12.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/13.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/14.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/15.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/16.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="menu/17.jpg" class="d-block w-100" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    -->
    

  
</div>
<div class="content-center">
    
  <ul>
    <li onclick="location.href='https://www.facebook.com/istanbulwhitepalacevenue/'"><i class="fa fa-facebook fa-2x"></i></li>
    <li onclick="location.href='https://z-p15.www.instagram.com/istanbul_cafe_rest_lusaka/'"><i class="fa fa-instagram fa-2x"></i></li>
    <li onclick="location.href='mailto:lusakaistanbulcaferestaurant@gmail.com'"><i class="fa fa-envelope fa-2x"></i></li>
  </ul>
  
</div>
  </body>
</html>
