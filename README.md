# LM
## Estructura mínima de una web
<!DOCTYPE html>
	<html>
	<head>
		<title></title>
	</head>
	<body>
	
	</body>
	</html>
## Explica las 3 formas de usar CSS en HTML
Nosotros utilizamos estas tres formas:
CSS interno-
Dentro del 
	<head></head> 
utilizamos 
	type="text/css"
CSS externo-
	<html>
	<head>
    	<title>Título de la página</title>
    	<style type="text/css">
        	div {
            	background:#FFFFFF;
        	}
    	</style>
	</head>
CSS Embebido-
Con la etiqueta 
	<style></style>

## Crea una lista sin ordenar con 5 ingredientes de una receta de cocina
<!DOCTYPE html>
	<html>
	<head>
		<title></title>
	</head>
	<body>
		<ul>
		<li>Sal(10g)</li>
		<li>Pimienta(5g)</li>
		<li>Pasta(500g)</li>
		<li>Aceite(15ml)</li>
		<li>Atún(200g)</li>
		</ul>	
	</body>
	</html>	
	
## Como se puede incluir javascript en HTML
Se puede agregar mediante la etiqueta
<script></script>
dentro del head
## ¿Que diferencia hay entre una clase y una ID?
El elemento "ID" es único y por tanto no se podrá repetir dentro del documento HTML.
El elemento "clase" se puede repetir y eso es muy beneficioso cuando tenemos que aplicar los mismos estilos a diferentes elementos, puesto que permite reducir las líneas de código.

## Código para hacer un enlace a otra página y que esta se abra en una nueva ventana

<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
	<a href="https://www.marca.com/">Marca</a>
</body>
</html>

## ¿Qué son las pseudoclases? Pon ejemplos.

Una pseudoclase es una palabra clave que se añade a los selectores y que especifica un estado especial del elemento seleccionado.
Ejemplos:

:disabled
Representa a cualquier elemento deshabilitado, es decir, un elemento que no está activado.

:focus
Representa un elemento que ha sido enfocado, que se ha centrado en él y se activa cuando el usuario hace clic o toca un elemento.

:valid
Esta pseudoclase ayuda al usuario a resaltar los campos correctos.

:fullscreen
Este elemento se muestra cuando la pantalla está completa.

## Explica el modelo de caja de CSS (margin, border y padding)



