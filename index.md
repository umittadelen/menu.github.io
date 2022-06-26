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
body {
  text-align: center;
  font-family: Arial;
  background: #f8f8f8;
}

.buttons {
  margin-top: 160px;
  
  a {
    margin-right: 30px;
    width: 64px;
    height: 64px;
    font-size: 24px;
    display: inline-block;
    position: relative;
    line-height: 64px;
    background-color: #eaeaea;
    background-image: linear-gradient(to bottom, #f6f6f6, #eaeaea);
    border-radius: 32px;
    box-shadow: 0 1px 1px rgba(0, 0, 0, .25), 0 2px 3px rgba(0, 0, 0, .1);
    
    &:active {
      top: 1px;
      background-image: linear-gradient(to bottom, #eaeaea, #f6f6f6);
      
      &::before {
        top: -9px;
      }
    }
    
    &::before {
      content: '';
      position: absolute;
      z-index: -1;
      top: -8px; right: -8px; bottom: -8px; left: -8px;
      background-color: #eaeaea;
      border-radius: 140px;
      opacity: 0.5;
      
      :hover & {
        opacity: 1;
      }
    }
  }
  
  
}

.twitter:hover::before {
  background-color: #c6f0f8;
}

.facebook:hover::before {
  background-color: #dae1f0;
}

.youtube:hover::before {
  background-color: #fadae6;
}

.twitch:hover::before {
  background-color: #f8ebb6;
}

.footer {
  width: 600px;
  margin: auto;
  margin-top: 100px;
  font-size: 15px;
  font-weight: bold;
  color: #cdcdcd;
  text-shadow: 1px 2px 0 #fff;
}

.footer a {
    color: #bebebe;
    text-decoration: none;
}

.footer a:hover {
  color: #bebebe;
  text-decoration: none;
  border-bottom:1px dashed #cdcdcd;
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

<div class="buttons">
    <a class="twitter" href=""><i class="fa fa-twitter"></i></a>
    <a class="facebook" href=""><i class="fa fa-facebook"></i></a>
    <a class="youtube" href=""><i class="fa fa-youtube-play"></i></a>
    <a class="twitch" href=""><i class="fa fa-twitch"></i></a>
  </div>
  <div class="footer">
    CSS3 Circle Social Buttons by <a href="http://azmind.com">Azmind.com</a> - Follow me on <a href="https://www.facebook.com/pages/Azmindcom/196582707093191">Facebook</a> and <a href="https://twitter.com/anli_zaimi">Twitter</a>!
  </div>
  

  </body>
</html>
