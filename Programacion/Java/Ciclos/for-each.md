# for-each
Se utiliza para recorrer elementos de un **arreglo (array)** o una **colección** de forma sencilla, sin necesidad de usar un contador.
## Sintaxis
```Java
for (Tipo elemento : arreglo) {
    // Uso de elemento
}
```
## Ejemplos
```Java
String[] frutas = {"Manzana", "Banana", "Cereza"};
for (String fruta : frutas) {
    System.out.println(fruta);
}
// Salida esperada
	//Manzana
	//Banana
	//Cereza
```