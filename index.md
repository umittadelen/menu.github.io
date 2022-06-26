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
     $basic-dark-color: #212121;
$basic-light-color: #fff;
$fb-color: #3b5998;
$tw-color: #00aced;
$g-plus: #dd4b39;
$dribbble: #ea4c89;
$pinterest: #cb2027;
$insta: #bc2a8d;
$in: #007bb6;
$vimeo: #1ab7ea;
$border-radius: 10px;
$font-size: 25px;

/*common styles !!!YOU DON'T NEED THEM */
.container {
  margin: 60px auto 0px auto;
  text-align: center;
  
  h1 {
    font: {
      family: 'Roboto', sans-serif;
      weight: 900;
      size: 30px;
    }
    text-transform: uppercase;
    color: $basic-dark-color;
    letter-spacing: 3px;
    
    span {
      display: inline-block;
      
      &:before,
      &:after {
        content: "";
        display: block;
        width: 34px;
        height: 2px;
        background-color: $basic-dark-color;
        margin: 0px 0px 0px 2px;
      }
    }
  }
}

.effect {
  width: 100%;
  padding: 50px 0px 70px 0px;
  background-color: $basic-dark-color;
  
  h2 {
    color: $basic-light-color;
    font: {
      family: 'Playfair Display', serif;
      weight: 400;
      size: 25px;
    }
    letter-spacing: 3px;
  }
  
  &:nth-child(2) {
    margin-top: 50px;
  }
  
  &:nth-child(2n+1) {
    background-color: $basic-light-color;
    
    h2 {
      color: $basic-dark-color;
    }
  }
  
  .buttons {
    margin-top: 50px;
    display: flex;
    justify-content: center;
  }
  
  a {
    
    &:last-child {
      margin-right: 0px;
    }
  }
}

/*common link styles !!!YOU NEED THEM*/
.effect {
  /*display: flex; !!!uncomment this line !!!*/
  
  a {
    text-decoration: none !important;
    color: $basic-light-color;
    width: 60px;
    height: 60px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: $border-radius;
    margin-right: 20px;
    font-size: $font-size;
    overflow: hidden;
    position: relative;
    
    i {
      position: relative;
      z-index: 3;
    }
    
    &.fb {
      background-color: $fb-color;
    }
    
    &.tw {
      background-color: $tw-color;
    }
    
    &.g-plus {
      background-color: $g-plus;
    }
    
    &.dribbble {
      background-color: $dribbble;
    }
    
    &.pinterest {
      background-color: $pinterest;
    }
    
    &.insta {
      background-color: $insta;
    }
    
    &.in {
      background-color: $in;
    }
    
    &.vimeo {
      background-color: $vimeo;
    }
  }
}

/* aeneas effect */

.effect.aeneas {
  
  a {
    transition: transform 0.4s linear 0s, border-top-left-radius 0.1s linear 0s, border-top-right-radius 0.1s linear 0.1s, border-bottom-right-radius 0.1s linear 0.2s, border-bottom-left-radius 0.1s linear 0.3s;
    
    i {
      transition: transform 0.4s linear 0s;
    }
    
    &:hover {
      transform: rotate(360deg);
      border-radius: 50%;
      
      i {
        transform: rotate(-360deg);
      }
    }
  }
}

/* jaques effect */
.effect.jaques {
  
  a {
    transition: border-top-left-radius 0.1s linear 0s, border-top-right-radius 0.1s linear 0.1s, border-bottom-right-radius 0.1s linear 0.2s, border-bottom-left-radius 0.1s linear 0.3s;
    
    &:hover {
      border-radius: 50%;
    }
  }
}

/* egeon effect */
.effect.egeon {
  
  a {
    transition: transform 0.2s linear 0s, border-radius 0.2s linear 0.2s;
    
    i {
      transition: transform 0.2s linear 0s;
    }
    
    &:hover {
      transform: rotate(-90deg);
      border-top-left-radius: 50%;
      border-top-right-radius: 50%;
      border-bottom-left-radius: 50%;
      
      i {
        transform: rotate(90deg);
      }
    }
  }
}

/* claudio effect */

.effect.claudio {
  
  a { 
    transition: transform 0.2s linear 0s, border-radius 0.2s linear 0s;
    
    &:hover {
      transform: scale(1.2);
      border-bottom-left-radius: 50%;
      border-top-right-radius: 50%;
    }
  }
}

/* laertes effect */

.effect.laertes {
  
  a {
    transition: all 0.2s linear 0s;
    
    i {
      transition: all 0.2s linear 0s;
    }
   
    &:hover {
      border-radius: 50%/20%;
      
      i {
        transform: scale(1.1);
        text-shadow: 0 0 12px rgba($basic-dark-color, 0.6);
      }
    }
  }
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
  <div class="effect aeneas">
    <h2>Aeneas</h2>
    <div class="buttons">
      <a onclick="location.href='https://www.facebook.com/istanbulwhitepalacevenue/'" href="#" class="fb" title="Join us on Facebook"><i class="fa fa-facebook" aria-hidden="true"></i></a>
      <a onclick="location.href='mailto:lusakaistanbulcaferestaurant@gmail.com'" href="#" class="tw" title="Join us on Twitter"><i class="fa fa-envelope" aria-hidden="true"></i></a>
      <a onclick="location.href='https://z-p15.www.instagram.com/istanbul_cafe_rest_lusaka/'" href="#" class="insta" title="Join us on Instagram"><i class="fa fa-instagram" aria-hidden="true"></i></a>
    </div>
	</div>
</div>
  </body>
</html>
