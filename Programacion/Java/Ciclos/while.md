# while
Este ciclo se utiliza cuando desconocemos el numero de repeticiones que vamos a usar. Lo que hace es evaluar una condición antes de de ejecutar el bloque de código, si la condición no es verdadera, no se ejecutara el código. 
## Sintaxis
```Java 
while (condición) { 
	// Instrucciones a repetir 
}
```
## Ejemplos
```Java
int i = 0;
while (i <= 5) {
    System.out.println("Número: " + i);
    i++;
}
// Salida esperada
	//Numero: 0
	//Numero: 1
	//Numero: 2
	//Numero: 3
	//Numero: 4
	//Numero: 5
```
En el ejemplo anterior se utiliza el ciclo for para hacer un conteo del 0 al 5 he imprimir cada aumento en pantalla.

