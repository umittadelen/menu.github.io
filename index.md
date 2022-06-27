<html lang="tr">
<meta charset="utf-8">
<head>
	<link rel="icon" type="image/png" href="menu/icn.png" />
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
	<script type="text/javascript" src="js/jquery-3.1.1.min.js"></script>
	<script src="https://kit.fontawesome.com/5ffd3c4e9b.js" crossorigin="anonymous"></script>
	<script type="text/javascript" src="js/bootstrap.min.js"></script>
	<style>
		.carousel-control-prev-icon {
    			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='red' viewBox='0 0 8 8'%3E%3Cpath d='M5.25 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3E%3C/svg%3E");
		}
		.carousel-control-next-icon {
    			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='red' viewBox='0 0 8 8'%3E%3Cpath d='M2.75 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3E%3C/svg%3E");
		}
		@import "compass/css3";

//vars
$fg:#ff4081;
$bg:#3f51b5;
$pi:3.14;

//config
$menu-items:5;
$open-distance:115px;
$opening-angle:$pi - .2;

body{
  background:$bg;
  color:white;
  text-align:center;
}
a{
  color:inherit;
}
h1, h2, h3, h4{
  margin:0;
  margin-bottom:10px;
  margin-top:10px;
}
h1{
  font-size:3em;
}
%goo{
  filter:url('#shadowed-goo');
  // debug 
  // background:rgba(255,0,0,0.2);
}
%ball{
  background:$fg;
  border-radius:100%;
  width:80px;
  height:80px;
  margin-left:-40px;
  position:absolute;
  top:20px;
  color:white;
  text-align:center;
  line-height:80px;
  transform:translate3d(0,0,0);
  transition:transform ease-out 200ms;
}
.menu-open{
  display:none;
}
.menu-item{
  @extend %ball;
}
.hamburger{
  $width:25px;
  $height:3px;
  width:$width;
  height:$height;
  background:white;
  display:block;
  position:absolute;
  top:50%;
  left:50%;
  margin-left:-$width/2;
  margin-top:-$height/2;
  transition:transform 200ms;
}
$hamburger-spacing:8px;
.hamburger-1{
  transform:translate3d(0,-$hamburger-spacing,0);
}
.hamburger-2{
  transform:translate3d(0,0,0);
}
.hamburger-3{
  transform:translate3d(0,$hamburger-spacing,0);
}
.menu-open:checked+.menu-open-button{
  .hamburger-1{
    transform:translate3d(0,0,0) rotate(45deg); 
  }
  .hamburger-2{
    transform:translate3d(0,0,0) scale(0.1,1);
  }
  .hamburger-3{
    transform:translate3d(0,0,0) rotate(-45deg); 
  }
}
.menu{
  @extend %goo;
  $width:380px;
  $height:250px;
  position:absolute;
  left:50%;
  margin-left:-$width/2;
  padding-top:20px;
  padding-left:$width/2;
  width:$width;
  height:$height;
  box-sizing:border-box;
  font-size:20px;
  text-align:left;
}


.menu-item{
  &:hover{
    background:white;
    color:$fg;
  }
  @for $i from 1 through $menu-items{
    &:nth-child(#{$i+2}){
      transition-duration:10ms+(60ms*($i));
    }
  }
}

.menu-open-button{
  @extend %ball;
  z-index:2;
  transition-timing-function:cubic-bezier(0.175, 0.885, 0.320, 1.275);
  transition-duration:400ms;
  transform:scale(1.1,1.1) translate3d(0,0,0);
  cursor:pointer;
}
.menu-open-button:hover{
  transform:scale(1.2,1.2) translate3d(0,0,0);
}
.menu-open:checked+.menu-open-button{
  transition-timing-function:linear;
  transition-duration:200ms;
  transform:scale(0.8,0.8) translate3d(0,0,0);
}

.menu-open:checked~.menu-item{
  transition-timing-function:cubic-bezier(0.935, 0.000, 0.340, 1.330);
  @for $i from 1 through $menu-items{
    $angle:(($pi - $opening-angle)/2)+(($opening-angle/($menu-items - 1))*($i - 1));
    
    &:nth-child(#{$i+2}){
      transition-duration:80ms+(80ms*$i);
      transform:translate3d(cos($angle)*$open-distance,sin($angle)*$open-distance,0);
    }
  }
}
	</style>
</head>
	
<body>
	<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
	<div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
		<div class="carousel-indicators">
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3" aria-label="Slide 4"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="4" aria-label="Slide 5"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="5" aria-label="Slide 6"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="6" aria-label="Slide 7"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="7" aria-label="Slide 8"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="8" aria-label="Slide 9"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="9" aria-label="Slide 10"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="10" aria-label="Slide 11"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="11" aria-label="Slide 12"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="12" aria-label="Slide 13"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="13" aria-label="Slide 14"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="14" aria-label="Slide 15"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="15" aria-label="Slide 16"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="16" aria-label="Slide 17"></button>
		</div>
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
		<button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
			<span class="carousel-control-prev-icon" aria-hidden="true"></span>
		  	<span class="visually-hidden">Previous</span>
		</button>
		<button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
		  	<span class="carousel-control-next-icon" aria-hidden="true"></span>
		  	<span class="visually-hidden">Next</span>
		</button>
	</div>
	<div class="container">
		<a href="https://www.facebook.com/istanbulwhitepalacevenue/" class="btn btn-primary  btn-lg btn-block"><i class="fa-brands fa-facebook"></i></a>
		<a href="https://www.instagram.com/istanbul_cafe_rest_lusaka/" class="btn btn-warning  btn-lg btn-block" ><i class="fa-brands fa-instagram-square"></i></a>
		<a href="mailto:lusakaistanbulcaferestaurant@gmail.com" class="btn btn-danger  btn-lg btn-block"><i class="fa fa-envelope"></i></a>
		<a href="https://wa.me/+260973183717/" class="btn btn-success  btn-lg btn-block"><i class="fa-brands fa-whatsapp-square"></i></a>
		<a href="https://g.page/istanbulwhitepalacevenue?share" class="btn btn-info  btn-lg btn-block"><i class="fa-solid fa-location-dot"></i></a>
		<nav class="menu">
  <input type="checkbox" href="#" class="menu-open" name="menu-open" id="menu-open"/>
  <label class="menu-open-button" for="menu-open">
    <span class="hamburger hamburger-1"></span>
    <span class="hamburger hamburger-2"></span>
    <span class="hamburger hamburger-3"></span>
  </label>
  
  <a href="#" class="menu-item"> <i class="fa fa-bar-chart"></i> </a>
  <a href="#" class="menu-item"> <i class="fa fa-plus"></i> </a>
  <a href="#" class="menu-item"> <i class="fa fa-heart"></i> </a>
  <a href="#" class="menu-item"> <i class="fa fa-envelope"></i> </a>
  <a href="#" class="menu-item"> <i class="fa fa-cog"></i> </a>

</nav>


<!-- filters -->
<svg xmlns="http://www.w3.org/2000/svg" version="1.1">
    <defs>
      <filter id="shadowed-goo">
          
          <feGaussianBlur in="SourceGraphic" result="blur" stdDeviation="10" />
          <feColorMatrix in="blur" mode="matrix" values="1 0 0 0 0  0 1 0 0 0  0 0 1 0 0  0 0 0 18 -7" result="goo" />
          <feGaussianBlur in="goo" stdDeviation="3" result="shadow" />
          <feColorMatrix in="shadow" mode="matrix" values="0 0 0 0 0  0 0 0 0 0  0 0 0 0 0  0 0 0 1 -0.2" result="shadow" />
          <feOffset in="shadow" dx="1" dy="1" result="shadow" />
          <feBlend in2="shadow" in="goo" result="goo" />
          <feBlend in2="goo" in="SourceGraphic" result="mix" />
      </filter>
      <filter id="goo">
          <feGaussianBlur in="SourceGraphic" result="blur" stdDeviation="10" />
          <feColorMatrix in="blur" mode="matrix" values="1 0 0 0 0  0 1 0 0 0  0 0 1 0 0  0 0 0 18 -7" result="goo" />
          <feBlend in2="goo" in="SourceGraphic" result="mix" />
      </filter>
    </defs>
</svg>
	</div>
</body>
</html>
