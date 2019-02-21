# EjemploInicial
#Primer repositorio en Github
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<!--meta para que sea multiplataforma -->
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<!--fuente -->
	<link href="https://fonts.googleapis.com/css?family=Roboto+Condensed" rel="stylesheet">
	<link rel="stylesheet" href="./css/reset.css">	
	<!--contiente los nuevos estilos-->
	<link rel="stylesheet" href="./css/main.css">
	<title>Formulario</title>

</head>
<body>

<!--ESTRUCTURA DEL FORMULARIO-->
	<div class="container">
		<div class="form__top">

			<h2>Formulario de<span> Registro</span></h2>
			<br></br>

			
		<div class="form_espe">
			<h3>E S P E</h3>
			<br></br>

			<h3>DEPARTAMENTO DE CIENCIAS DE LA COMPUTACIÓN</h3>
			<br></br>

			<h3>Ingeniería en Tecnologías de la Información</h3>
		</div>
			<img src="img.png">
			<h2>DATOS GENERALES DEL  ESTUDIANTE</h2>
		</div>		
		

		<!--FORMULARIO-->
		<!--inicia con un caractér-->
		<form class="form__reg" action= "post.php" method="POST">

			<input class="input" type="text" name="nombres" placeholder="&#128100;  Nombre" required autofocus>
			<input class="input" type="text" name="apellidos" placeholder="&#128100; Apellido" required>
            <input class="input" type="email" name="email" placeholder="&#9993;  Email" required>
            <input class="input" type="text" name="telefono" placeholder="&#128222;  Telefono" required>
            <input class="input" type="text" name="direccion" placeholder="&#8962;  Dirección" required>
            <input class="input" type="date" name="fecha" placeholder="&#8962; Fecha de Nacimiento" required>
            <input class="input" type="text" name="provincia" placeholder="Provincia" list="provincia" required>
  <!-- Lista de opciones -->
				<datalist id="provincia">
				    <option value="Azuay"></option>
				    <option value="Bolivar"></option>
				    <option value="Cañar"></option>
				    <option value="Carchi"></option>
				    <option value="Chimborazo"></option>
				    <option value="Cotopaxi"></option>
				    <option value="El Oro"></option>
				    <option value="Esmeralda"></option>
				    <option value="Galapagos"></option>
				    <option value="Guayas"></option>
				    <option value="Imbabura"></option>
				    <option value="Loja"></option>
				    <option value="Los Rios"></option>
				    <option value="Manabi"></option>
				    <option value="Morona Santiago"></option>
				    <option value="Napo"></option>
				    <option value="Orellana"></option>
				    <option value="Pastaza"></option>
				    <option value="Pichincha"></option>
				    <option value="Santa Elena"></option>
				    <option value="Santo Domingo"></option>
				    <option value="Sucumbios"></option>
				    <option value="Tungurahua"></option>
				    <option value="Zamora Chinchipe"></option>
  				</datalist>

  				<font size="2">
  					<label>  -Género: </label>
  			<p><input class="radio" type="radio" name="genero" value="Masculino"> Masculino</p>
			<p><input class="radio" type="radio" name="genero" value="Femenino"> Femenino</p>
				</font>
			<input class="input" type="text" name="estado" list="estado" placeholder="&#8962; Estado Civil" required>
  <!-- Lista de opciones -->
				  <datalist id="estado">
				    <option value="Soltero"></option>
				    <option value="Casado"></option>
				    <option value="Divorciado"></option>
				    <option value="Viudo"></option>
				    <option value="Union Libre"></option>
				  </datalist>

			<input class="input" type="text" name="carrera" list="carrera" placeholder="&#8962; Carrera" required>
  <!-- Lista de opciones -->
				  <datalist id="carrera">
				    <option value="ITIN">Ingenieria en Tecnologias de la Informacion</option>
				    <option value="BIO">Ingenieria en Biotecnologia</option>
				    <option value="AGRO">Ingenieria Agropecuaria</option>
				  </datalist>
			<input class="input" type="text" name="nivel" list="nivel" placeholder="&#8962; Nivel" required>
  <!-- Lista de opciones -->
				  <datalist id="nivel">
				    <option value="1"></option>
				    <option value="2"></option>
				    <option value="3"></option>
				    <option value="4"></option>
				    <option value="5"></option>
				    <option value="6"></option>
				    <option value="7"></option>
				    <option value="8"></option>
				    <option value="9"></option>
				    <option value="10"></option>
				  </datalist>

            <div class="btn__form">
            	<input class="btn__submit" type="submit" value="REGISTRAR">
            	<input class="btn__reset" type="reset" value="LIMPIAR">	
            </div>
            <div class="descripcion">
            	<center>
            	<h2><span> <b>Presentación:</b> </span></h2>
            	<br>
            	<p>Mi nombre es Erick Montesdeoca, estudiante de la carrera de tecnologías de la información. Actualmente curso el 4to semestre...</p>
          		</center>
          
            </div>
		</form>
	</div>
	
</body>
</html>
