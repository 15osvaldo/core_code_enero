#3core_code_enero
#3 Respueta de se segunda pregunta 
 Pregunta: Java language is compiled or interpreted?
 Answer:  java can be consedered both a compiler and interpreted languaje becuause its sourse code is firts compiled into a binary byte-code.
 
 ## respueta de la tercera pregunta
 Create an algorithm to calculate the equivalent of your local currencty to USD
 -saber el tipo de cambio
 -obtener la cantidad a calcular
 -realizar la operacion para tener la convercion
 -mostrar el equivalente 

##respuesta de la pregunta 5
pregunta: ¿Por qué es útil el pseudocódigo?
-Respuesta: es util para poder encontrar un mejor enfoque y poder dar la mejor solocion a un problema determinado.

## Respuesta a la pregunta 6
-- Crear un pseudocodigo calcular la edad aproximada de una base de usuarios en el año en que nació
-> se define una variable con el año en curso.
-> se crea un nuevo campo en el nombre de edad
-> se accede a la base de datos donde se encuentra la fecha del nacimiento de cada usuario.
-> se resta el año en que nacio cada usuario y se le asigna el valor al campo con nombre edad
-> se guardad la edad de cada usuario en el campo que corresponde.

## Respuesta a la pregunta 8
¿Por qué los diagramas de flujo son importantes para nosotros como desarrolladores?

->porque podemos plasmar una idea o problema que se necesite solucionar, y al hacer uso de diagramas de flujo podemos crear y llevar acabo o solucionar algun problema 
 y poder seguir el diagrama de flujo se puede hacer de manera mas sencilla.
 
# Miercoles
## Respuesta de la pregunta 2
-> Decimal  1993
-> binario 11111001001
-> hexadecimal 7c9
## respuesta de la pregunta 3
-> binario 1100101011111110
-> Decimla 51966
-> hexadecimal CAFE

## respuesta a la pregunta 5.1
-> 
.data
	number1: .asciiz "\nIngrese el primer numero: "
	number2: .asciiz "\nIngrese el segundo numero: "
	result_message: .asciiz "\nEl resultado es: "
	
.text
	main:
		li $v0, 4
		la $a0, number1
		syscall

		li $v0, 5
		syscall

		move $t0, $v0

		li $v0, 4
		la $a0, number2
		syscall

		li $v0, 5
		syscall

		move $t1, $v0
		
		
		add $t2, $t0, $t1
		
		li $v0, 4 
		la $a0 result_message
		syscall
		
		li $v0, 1
		move $a0, $t2
		syscall
  
  ## respuesta de la pregunta 5.2
 .data
	message: .asciiz "\nJosue Osvaldo Gonzalez Salazar \"
.text
	main: 
		li $v0, 4
		la $a0, message
		syscall
