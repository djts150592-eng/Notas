# for
Este ciclo se utiliza cuando se conoce de antemano cuantas iteraciones se van a realizar
## Sintaxis
```Java
for (inicializacion; condicion; aumento(actualizacion)){
	//Instrucciones a repetir
	
}
```

## Ejemplo
```Java
for (int i=0; i<=5; i++){
	System.out.print("Numero: " + i);
}

// Salida esperada
	//Numero: 0
	//Numero: 1
	//Numero: 2
	//Numero: 3
	//Numero: 4
	//Numero: 5
```

En el ejemplo anterior se utiliza el ciclo for para hacer un conteo del 0 al 5 he imprimir cada aumento en pantalla