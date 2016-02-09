Product Backlog:
Se realiza una calculadora con varias funcinalidades, que será el producto final que desea el cliente.

Lo dividiremos en 3 historias de usuario que serán:
	-Sumar
	-Multiplicar
	-Restar

Cada história la dividimos en 3 tareas: 
	-Diseño de de las pruebas 
	-Pruebas(TDD)
	-Codificar el código bueno

La cuarta historia que nos pedía el enunciado del ejercicio la he resulto ya en las pruebas de la resta, ya que uno de los requisitos para que el resultado sea correcto y aparezca en pantalla es que este debe ser un número natural. 

Vamos a aplicar TDD, por lo que las historias son independientes y pueden ser desarrolladas a la vez por diferentes desarrolladores. Al unificar las diferentes historias en la rama master del proyecto voy a realizar una prueba de integración de las distintas historias. 

Hemos considerado que para poder desarrollar la funcionalidad de multiplicar debe probarse y funcionar la funcionalidad de suma, ya que sin saber  si funciona la suma no se puede multiplicar. La resta sin embargo la hemos hecho en paralelo ya que no hemos considerado que se puden desarrollar a la vez. 

El proyecto que entregamos con las 3 historias es lo que hemos desarrollado a lo largo de 1 Sprint, se ha estimado que la duración del sprint son 2 semanas, ya que se realizan pruebas individuales y se dedica tiempo a ello. 