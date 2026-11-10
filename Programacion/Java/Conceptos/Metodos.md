# Metodos
En java los métodos son bloques de código reutilizable los cuales realizan una tarea especifica. En la porgramacion orientada a objetos, los metodos determinan el comportamiento o acciones que puede ejecutar un objeto.

## Partes de un metodo
1. Modificador: Define la accesibilidad de un metodo, este puede tener acceso publico, es decir, es la parte que interactua con el objeto, o privado, que es la parte que solamente tiene acceso la clase. 
2. Tipo de retorno: Indica el [[Tipos de Datos en Java | tipo de dato]] que devuelve al terminar su ejecución. Sino devuelve nada, entonces se usa la palabra reservada void. 
3. Nombre del método: Es el identificador único para llamarlo después. Por convención, se escribe en formato _camelCase_ (por ejemplo, `calcularSuma`).
4. Parametos: Es el conjunto de variables que utiliza el metodo para trabajar. Puede o no recibir parametros. 
5. Cuerpo del método: Es el conjunto de instrucciones que realizara, este va encerrado entre llaves {}. 
# Ejemplos: 
```Java
public class Calculadora { 
	// Declaración del método 
	//public static(modificador de acceso) int(retorno) sumar(nombre del metodo) (lista de parametros){cuerpo} 
	public static int sumar(int a, int b) { 
		int resultado = a + b; return resultado; 
	}
	// Método principal donde inicia el programa 
	 public static void main(String[] args) { 
	 // Llamada o invocación del método 
		 int total = sumar(5, 3); 
		 System.out.println("La suma es: " + total); 
	}
}
 // Imprime: La suma es: 8 
```
