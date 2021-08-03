# portafolio-johan
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<link href="https://fonts.googleapis.com/css?family=Open+Sans:400,700&display=swap" rel="stylesheet">
	<script src="https://kit.fontawesome.com/2c36e9b7b1.js"></script>
	<link rel="stylesheet" href="estilos.css">
	<title>Portafolio Johan Camacho</title>
</head>
<body>
	
	<div class="contenedor">
		<header>
			<div class="logo">
				<h1>Johan Camacho</h1>
				<p>Productor Multimedia</p>
			</div>
			<form action="">
				<input type="text" class="barra-busqueda" id="barra-busqueda" placeholder="Buscar">
			</form>
			<div class="categorias" id="categorias">
				<a href="#" class="activo">Todos</a>
			
			</div>
		</header>

		<section class="grid" id="grid">
			<div class="item" 
				 data-categoria="ciudades"
				 data-etiquetas="ciudades autos carros calles"
				 data-descripcion="1.- Lorem ipsum dolor sit amet consectetur."
			>
				<div class="item-contenido">
					<img src="img/foto5.jpg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="personas"
				 data-etiquetas="personas mujeres"
				 data-descripcion="2.- Lorem ipsum dolor sit amet consectetur."
			>
				<div class="item-contenido">
					<img src="img/foto4.jpg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="paisajes"
				 data-etiquetas="paisajes montañas mar playas"
				 data-descripcion="3.- Lorem ipsum dolor sit amet consectetur."
			>
			<div class="item-contenido">
					<img src="img/foto11.jpeg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="paisajes"
				 data-etiquetas="paisajes montañas mar playas"
				 data-descripcion="3.- Lorem ipsum dolor sit amet consectetur."
			>
			<div class="item-contenido">
					<img src="img/foto8.jpg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="paisajes"
				 data-etiquetas="paisajes montañas mar playas"
				 data-descripcion="3.- Lorem ipsum dolor sit amet consectetur."
			>
			<div class="item-contenido">
					<img src="img/foto7.jpg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="paisajes"
				 data-etiquetas="paisajes montañas mar playas"
				 data-descripcion="3.- Lorem ipsum dolor sit amet consectetur."
			>
				<div class="item-contenido">
					<img src="img/foto9.jpg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="animales"
				 data-etiquetas="animales leones"
				 data-descripcion="4.- Lorem ipsum dolor sit amet consectetur."
			>
			<div class="item-contenido">
					<img src="img/foto10.jpeg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="personas"
				 data-etiquetas="personas mujeres"
				 data-descripcion="6.- Lorem ipsum dolor sit amet consectetur."
			>
			<div class="item-contenido">
					<img src="img/foto6.jpg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="personas"
				 data-etiquetas="personas mujeres"
				 data-descripcion="6.- Lorem ipsum dolor sit amet consectetur."
			>
			<div class="item-contenido">
					<img src="img/foto12.jpg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="personas"
				 data-etiquetas="personas mujeres"
				 data-descripcion="6.- Lorem ipsum dolor sit amet consectetur."
			>
				<div class="item-contenido">
					<img src="img/foto3.jpg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="animales"
				 data-etiquetas="animales pandas"
				 data-descripcion="5.- Lorem ipsum dolor sit amet consectetur."
			>
				<div class="item-contenido">
					<img src="img/foto2.jpg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="personas"
				 data-etiquetas="personas mujeres"
				 data-descripcion="6.- Lorem ipsum dolor sit amet consectetur."
			>
				<div class="item-contenido">
					<img src="img/foto1.jpg" alt="">
				</div>
			</div>
			</div>
		</section>

		<section class="overlay" id="overlay">
			<div class="contenedor-img">
				<button id="btn-cerrar-popup"><i class="fas fa-times"></i></button>
				<img src="" alt="">
			</div>
			<p class="descripcion"></p>
		</section>

		<footer class="contenedor">
			<div class="redes-sociales">
				<div class="contenedor-icono">
					<a href="" target="_blank" class="twitter">
						<i class="fab fa-twitter"></i>
					</a>
				</div>
				<div class="contenedor-icono">
					<a href="" target="_blank" class="facebook">
						<i class="fab fa-facebook-f"></i>
					</a>
				</div>
				<div class="contenedor-icono">
					<a href="" target="_blank" class="instagram">
						<i class="fab fa-instagram"></i>
					</a>
				</div>
			</div>
			<div class="creado-por">
				<p>Sitio diseñado por <a href="#">Johan Camacho</a>
			</div>
		</footer>
	</div>

	<script src="https://unpkg.com/web-animations-js@2.3.2/web-animations.min.js"></script>
	<script src="https://unpkg.com/muuri@0.8.0/dist/muuri.min.js"></script>
	<script src="main.js"></script>
</body>
</html>
