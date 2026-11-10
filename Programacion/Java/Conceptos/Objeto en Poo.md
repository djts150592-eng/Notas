# Objetos
En [[Java]], un objeto es una instancia concreta de una clase que agrupa datos y comportamientos dentro de un [[Programacion|programa]]. Mientras que una clase funciona como un molde o plano, el objeto es la entidad real creada a partir de ese diseño.
Cada objeto ocupa un espacio en la memoria y permite modelar elementos del mundo real (como un auto, un usuario o una cuenta bancaria) o conceptos abstractos.

## Características de un objeto
Todo objeto en Java se define por tres elementos principales:
- **Estado (Atributos).** Son las características o datos que almacenan información sobre el objeto, representados mediante variables. Por ejemplo, en un objeto `Auto`, sus atributos serían `color`, `marca` y `velocidadActual`.
- **Comportamiento ([[Metodos]]).** Son las acciones que el objeto puede realizar o que se pueden ejecutar sobre él. Siguiendo el ejemplo del `Auto`, sus métodos serían `acelerar()`, `frenar()` o `encender()`.
- **Identidad.** Es el nombre o referencia única que distingue a un objeto de otro en la memoria, incluso si ambos tienen exactamente los mismos valores en sus atributos.

# Notas:
1. Un objeto en Java es parecido a una estructura ([[Struct |struct]]) en C, funcionando como una variable compleja que agrupa distintos [[Tipos de Datos en Java|tipos de datos]]. La diferencia es que, además de reservar memoria para guardar sus propios datos ([[Atributos|atributos]]), está vinculado a una clase que le permite ejecutar acciones (métodos).