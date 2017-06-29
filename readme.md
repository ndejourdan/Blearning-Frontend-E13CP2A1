# Actividad Presencial 2 de la Semana 6

La siguiente actividad se compone de dos partes, la primera de un nivel sencillo y la segunda de un nivel más avanzado.
**Debes realizar al menos una de las actividades.**

Bonus si se realizan ambas actividades.


## Nivel 1

Se debe realizar un mini juego de Piedra Papel o Tijera
Para eso existirán 3 imágenes en la pantalla representativas de cada opción.

El usuario al hacer click en una de las imágenes se le debe agregar un texto abajo que indique que escogiste esa opción.

A través de un número generado al azar el computador escogerá otra opción, la opción escogida debe salir indicada abajo, Existe la opción que por azar ambos escojan la misma opción.

Comparando todas las posibilidades (piedra vs papel, piedra vs tijera, piedra vs piedra, etc...) determinar quien ganó o si hubo empate.

## Nivel 2
En esta actividad se debe utilizar como base el proyecto
entregado como prueba de la unidad de HTML y CSS

Dentro del proyecto se pide:

- Agregar Google Analytics.
- Crear un formulario para registrarse como interesado.
  Esto permitirá en el futuro recibir newsletters.
- Cada vez que se registre un nuevo usuario a través del formulario se debe generar una alerta que muestre que has sido registrado
	- hints para investigar
		- onsubmit: https://www.w3schools.com/jsref/event_onsubmit.asp)
		- addEventListener
		- preventDefault
- Eliminar la alerta pero aprovechar los eventos para guardar como **evento** dentro de google Analytics al usuario.
- Establecer como objetivo el registro de un usuario dentro de google analytics.
	- hint: https://developers.google.com/analytics/devguides/collection/analyticsjs/events
- Las personas suelen cometer errores al llenar el formulario, antes de enviar el evento validar que dentro del email el usuario no haya ingresado un email terminado en `@gmal.com`.
