
# Convierte los siguientes ejercicios realizado durante el taller a pseudocodigo.

### 1. Realizar un algoritmo y diagrama de flujo de un programa que solicite un número y lo multiplique por 9, mostrando su resultado.

Algoritmo uno
	
	Escribir "Ingresa un numero"
	Leer num1
	res<-num1*9
	Escribir "El resultado es ",res
FinAlgoritmo

![image](https://user-images.githubusercontent.com/101203621/159966926-ea0c1d69-dc47-4e00-8408-18a124c31004.png)


### 2. Realiza un diagrama de flujo para obtener la suma de diez cantidades, que se soliciten al usuario, mediante la utilización de un ciclo “Mientras”.

Algoritmo suma_10_cantidades
	Escribir "Ingresa 10 cantidades"
	suma<-0
	cont<-1
	Mientras cont<=10 Hacer
		Leer Cantidad
		suma=suma+Cantidad
		cont=cont+1
	Fin Mientras
	Escribir suma
FinAlgoritmo

![sin_titulo](https://user-images.githubusercontent.com/101203621/159970997-6b395afc-9322-469b-9b42-5a01e0097531.png)


### 3. Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6, y se le informe ha reprobado a quien obtenga una calificacion menor a 6.

Algoritmo calificaciones
	Escribir "Ingresa la calificacion del primer periodo"
	Leer a
	Escribir "Ingresa la calificacion del segundo periodo"
	Leer b
	Escribir "Ingresa la calificacion del tercer periodo"
	Leer c
	Escribir "Ingresa la calificacion del cuarto periodo"
	Leer d
	res<-(a+b+c+d)/4
	Si res>=6 Entonces
		Escribir "Felicidades, aprobaste!"
	SiNo
		Escribir "Lo siento, has reprobado :c"
	Fin Si
FinAlgoritmo


![image](https://user-images.githubusercontent.com/101203621/159972916-8571c8cf-5664-4025-bb2c-cf38662ec08d.png)

  

### 4. Realizar un algoritmo y diagrama de flujo para un programa que solicite un número e indique si es par o impar.

Algoritmo Par_e_impar
	Escribir "Ingresa un numero"
	Leer a
	Si a % 2 == 0 Entonces
		Escribir "El numeor es par"
	SiNo
		Escribir "El numero es impar"
	Fin Si
FinAlgoritmo

![image](https://user-images.githubusercontent.com/101203621/159973828-c321e7d8-61f0-4feb-960c-a8b382e8c044.png)


### 5. Un programa que pida una letra y detecte si es una vocal.

6. Programa que pida 3 números y los muestre en pantalla de menor a mayor.
7. Realizar un algoritmo y diagrama de flujo para un programa que permita ingresar un nombre y una cantidad numérica para que así después el programa escriba este nombre tantas veces como su cantidad ingresada.
8. Realiza un algoritmo y diagrama de flujo de un programa que solicita números al usuario y haga la suma de todos ellos. El algoritmo debe solicitar números siempre y cuando el número ingresado sea positivo, si el usuario ingresa un número no positivo el algoritmo debe terminar e imprimir la suma de los números positivos.
