# Creación de un proyecto Java con VSCode
## Primer paso
Si ya tienes VS Code y el JDK instalados, solo necesitas instalar el paquete de extensiones en VS Code:
1. Abre el panel de extensiones (el icono de bloques a la izquierda).
2. Busca **`Extension Pack for Java`** (publicado por Microsoft) y haz clic en instalar. Este paquete incluye soporte de lenguaje, depuración, Maven, gestión de proyectos y otras herramientas esenciales .
## Segundo paso
Una vez instaladas las extensiones, tienes dos formas de crear un proyecto:

**Método 1: Usar la paleta de comandos (recomendado)**
1. Presiona `Ctrl+Shift+P` (Mac es `Cmd+Shift+P`) para abrir la paleta de comandos.
2. Escribe **`Java: Create Java Project...`** y selecciónalo .
3. A continuación, VS Code te preguntará qué tipo de proyecto deseas crear. Las opciones comunes incluyen:
    - **No build tools**: proyecto Java simple, adecuado para principiantes o programas pequeños de un solo archivo.
    - **Maven**: proyecto estándar de Maven, adecuado para la mayoría de proyectos formales.
    - **Gradle**: proyecto estándar de Gradle.
4. Selecciona la carpeta de almacenamiento, ingresa el nombre del proyecto y presiona Enter para completar la creación.
**Método 2: Usar la vista de Java**  
En la barra lateral izquierda, ve a la vista "Java Projects" (si no la ves, puedes encontrarla en el explorador), haz clic en el botón **`+`** de la parte superior y también podrás iniciar la creación de un proyecto .

# Notas:
- **Acerca del JDK**: Si VS Code indica que no se encuentra el JDK, puedes buscar y ejecutar el comando **`Java: Configure Java Runtime`** en la paleta de comandos, donde podrás descargar e instalar un JDK directamente o especificar la ruta de uno ya instalado .[](https://code.visualstudio.com/learn/java-spring-boot/1-build-and-run.md)
    
- **Proyectos existentes**: Si ya tienes una carpeta de proyecto Maven o Gradle, simplemente usa "Archivo > Abrir carpeta" en VS Code para abrirla, y las extensiones la reconocerán e importarán automáticamente .

# Lasos:
1. [[Java]]
2. [[Estructura de un Proyecto en Java]]