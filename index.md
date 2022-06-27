<html lang="tr">
<meta charset="utf-8">
<head>
	<meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

	<title>MENU</title>
	<script type="text/javascript" src="js/jquery-3.1.1.min.js"></script>
	<script src="https://kit.fontawesome.com/5ffd3c4e9b.js" crossorigin="anonymous"></script>
	<script type="text/javascript" src="js/bootstrap.min.js"></script>
	<style>
		.carousel-control-prev-icon {
    			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='blue' viewBox='0 0 8 8'%3E%3Cpath d='M5.25 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3E%3C/svg%3E");
		}
		.carousel-control-next-icon {
    			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='blue' viewBox='0 0 8 8'%3E%3Cpath d='M2.75 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3E%3C/svg%3E");
		}
		body{
            		margin-top: 100px !important;
        	}
        	.btn {
            		background-color: #F48224;
            		color: #000;
            		font-size: 20px;
            		font-weight: 800;
            		text-transform: uppercase;
            		position: relative;
            		border-radius: 0 !important;
            		border: none;
            		transition:all 0.3s ease 0s;
			top: 30px;
		}
        	.btn:hover,
        	.btn.active:hover{
            		color: #ffffff;
		}
        	.btn:before{
            		content: "";
            		position: absolute;
            		top: -7px;
            		left: 0;
            		background-color:#2E0014;
            		width: 30%;
            		height: 4px;
            		transition:all 0.3s ease 0s;
        	}
        	.btn:after{
            		content: "";
            		position: absolute;
            		bottom: -7px;
            		right: 0;
		 	background-color:#2E0014;
            		width: 30%;
            		height: 4px;
			transition:all 0.3s ease 0s;
        	}
		.btn:hover:before,
        	.btn:hover:after,
        	.btn.active:before,
        	.btn.active:after{
        		width: 100%;
		}

        	@media screen and (max-width: 575px){
            		.btn{
                		margin-bottom: 50px !important;
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
		<a href="https://www.facebook.com/istanbulwhitepalacevenue/" class="btn btn-primary  btn-lg btn-block">facebbook <i class="fa-brands fa-facebook"></i></a>
		<a href="https://www.instagram.com/istanbul_cafe_rest_lusaka/" class="btn btn-warning  btn-lg btn-block" >instagram <i class="fa-brands fa-instagram-square"></i></a>
		<a href="https://mailto:lusakaistanbulcaferestaurant@gmail.com" class="btn btn-danger  btn-lg btn-block">mail <i class="fa fa-envelope"></i></a>
	</div>
</body>
</html>
