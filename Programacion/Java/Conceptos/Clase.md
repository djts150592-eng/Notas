# Clase
Joyanes define una clase como un molde de gelatina, existen muchos tipos de gelatinas, pero todas reúnen los mismos [[Atributos|atributos]] y se comportan de manera similar. 
Una definición mas formal seria: 
	*Una **clase en Java** es una plantilla o un molde que define la estructura, los datos y el comportamiento que van a tener los **objetos** creados a partir de ella. Es la base de la **Programación Orientada a Objetos (POO)** en este lenguaje.*
## Componentes de una clase
Una clase se define usando la palabra reservada *class* y por lo general contiene los siguiente elementos:
- [[Atributos]]
- [[Constructor|Constructores]]
- [[Metodos]]

# Ejemplo de clase en java:
```Java
//1. Atributos
String color;
String modelo;

//2. Constructores
public Coche(String color, String modelo) { 
	this.color = color;
	this.modelo = modelo; 
}

// 3. Métodos 
public void acelerar() { 
	System.out.println("El coche está acelerando..."); 
}

```
