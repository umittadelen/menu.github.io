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
@import url('//netdna.bootstrapcdn.com/font-awesome/3.2.1/css/font-awesome.min.css');

.button-wrap {
  width: 150px;
  height: 150px;
  position: relative;
  display: inline-block;
  margin: 25px 50px 0;
  cursor: pointer;
  border-radius: 100%;
  box-shadow: inset 0 0 15px rgba(0, 0, 0, 0.3);
  
  &.facebook {
    background-color: #3B5998;
    i.active { color: #3B5998; }
  }
  
  &.twitter {
    background-color: #0AC;
    i.active { color: #0AC; }
  }
  
  &.pinterest {
    background-color: #CD2129;
    i.active { color: #CD2129; }
  }
  
  &.dribbble {
    background-color: #F26798;
    i.active { color: #F26798; }
  }
  
  &:hover {
    .button-inner-wrap {
      width: 115px;
      height: 115px;
      
      i.inactive { transform: translate(100px, -50%); }
      i.active { transform: translate(-50%, -50%); }
    }
  }
}

.button-inner-wrap {
  width: 150px;
  height: 150px;
  border: 1px solid #DDD;
  position: absolute;
  left: 50%;
  top: 50%;
  overflow: hidden;
  background-color: #FFF;
  border-radius: 100%;
  transform: translate(-50%, -50%);
  transition: all 0.3s ease;
  
  i {
    position: absolute;
    left: 50%;
    top: 50%;
    font-size: 50px;
    transition: all 0.3s ease;
    
    &.inactive {
      color: #CCC;
      transform: translate(-50%, -50%);
    }
    
    &.active { transform: translate(-150px, -50%); }
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

<div class="content-center"> 
	<div onclick="location.href='https://www.facebook.com/istanbulwhitepalacevenue/'" class="button-wrap facebook">
  		<div class="button-inner-wrap">
    		<i class="icon-facebook inactive"></i>
    		<i class="icon-facebook active"></i>
  	</div>
</div>
    <div class="buttons">
      <a  href="#" class="fb" title="Join us on Facebook"><i class="fa fa-facebook" aria-hidden="true"></i></a>
      <a onclick="location.href='mailto:lusakaistanbulcaferestaurant@gmail.com'" href="#" class="tw" title="Join us on Twitter"><i class="fa fa-envelope" aria-hidden="true"></i></a>
      <a onclick="location.href='https://z-p15.www.instagram.com/istanbul_cafe_rest_lusaka/'" href="#" class="insta" title="Join us on Instagram"><i class="fa fa-instagram" aria-hidden="true"></i></a>
</div>
  
</div>

  </body>
</html>
