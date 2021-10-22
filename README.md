# Formulario
<!DOCTYPE html>
<html>
<head>
<title>Formulario</title>
</head>
<body>
<form method="POST" action="http://formadorestic.com/alumnosdaw/procesaformulario.php">
	<label for="nombre">Nombre: </label>
	<input type="text" id="nombre" name="nombre" placeholder="Introduzca su nombre">
	<br>
	<label for="edad">Edad: </label>
	<input type="number" id="edad" name="edad" placeholder="Introduzca su edad">
	<br>
	<label for="email">Email:</label>
	<input type="email" id="email" name="email" placeholder="Introduzca su email">
	<br>
	<p>Eres:
		<br>
	<input id="mayor" type="radio" name="mayormenor" value="mayor de edad">
	<label for="mayor">mayor de edad</label>
	<br>
	<input id="menor" type="radio" name="mayormenor" value="menor de edad">
	<label for="menor">menor de edad</label>
	</p>
	<p>
	<input type="submit" value="ENVIAR"></p>
</form>
</body>
</html>
