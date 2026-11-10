# Constructor
Es un método especial que se llama de manera automática una vez que se crea un objeto para inicializar los valores de los atributos de la clase. 
## Caracteristicas:
1. Tiene el mismo nombre de la clase.
2. No retorna nada.
3. Solo existe uno.

## Ejemplos

### Constructor sin parametros
```Java
public class Cuenta{
	// Atributos
	private String nombre;
	private String cuenta;
	private double saldo;
	private double tipoInteres;
	
	//Metodos
	public Cuenta(){} // Constructor sin parametros
}
```
El constructor sin parámetros inicializa los valores de los atributos en sus valores predefinidos.
- **Tipos numéricos enteros** (`byte`, `short`, `int`, `long`): `0`
- **Tipos numéricos decimales** (`float`, `double`): `0.0`
- **Tipo carácter** (`char`): `\u0000` (el carácter nulo)
- **Tipo booleano** (`boolean`): `false`
- **Tipos de referencia** (objetos, cadenas `String`, arrays, etc.): `null`
### Constructor con parametros:
```Java
public class Cuenta{
	// Atributos
	private String nombre;
	private String cuenta;
	private double saldo;
	private double tipoInteres;
	
	//Metodos
	public Cuenta(){} // Constructor sin parametros (Queda omitido si se le mandan parametros al construir objetos)
	public Cuenta(String nom, String cue, double sal, double tipo){
		asiganarNombre(nom);
		asignarCuenta(cue);
		ingreso(sal);
		asignarTipoDeInteres(tipo);
	}
}
```
En este caso se hizo la asignación utilizando los [[Metodos| métodos]] de validación de datos de la [[Clase|clase]]. 
# Notas:
1. El constructor como tal solo existe uno, sino definimos uno se creara uno por defecto el cual inicializa los valores de los atributos en su valor por defecto.
2. Cuando definimos un constructor con parámetros este suplanta al constructor por defecto (omisión).
3. Cuando definimos un **constructor con parámetros** es necesario **definir explícitamente el constructor por defecto** . 

# Lasos:
1. [[Java]]