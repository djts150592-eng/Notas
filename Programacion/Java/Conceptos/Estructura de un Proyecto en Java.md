# Estructura de Directorios Estándar de Maven/Gradle
La estructura de un proyecto en java se rije por **Estructura de Directorios Estándar de Maven/Gradle** (Standard Directory Layout).

## Esqueleto de carpetas del proyecto
Cada carpeta y archivo tiene un propósito muy específico:
- **`src` (Source (Fuente)):** Aquí es donde **tú escribes tu código**. Es la única carpeta que te importa realmente al programar. Dentro de ella está tu `App.java`. (Si tuvieras paquetes como `com.miempresa`, se crearían subcarpetas aquí dentro).
- **`bin` (Binary (Binario)):** Aquí es donde el compilador de Java (el `javac`) guarda los archivos **`.class`** (como tu `App.class`). Estos son los archivos que la Máquina Virtual de Java (JVM) ejecuta. **Nunca debes editar ni programar en esta carpeta.** Es el resultado de compilar lo que hay en `src`.
- **`lib` (Libraries (Librerías)):** Si tu proyecto necesita usar código de terceros (por ejemplo, un archivo `.jar` para conectarte a una base de datos), lo pones aquí. La extensión de Java le dirá al compilador que busque dependencias en esta carpeta.
- **`.vscode`:** Es una carpeta oculta (por eso empieza con punto) generada por VS Code. Contiene el archivo `settings.json`, que guarda configuraciones específicas de _este_ proyecto para _tu_ editor (por ejemplo, la versión de Java que estás usando o la codificación de caracteres).
- **`README.md`:** Un archivo de texto (en formato Markdown) para que escribas de qué trata el proyecto, cómo instalarlo, etc. Es una buena práctica de documentación.
## Nombre del archivo de arranque (Donde va el main)
En la antigüedad el nombre del archivo donde se encontraba el método main se llamaba CTest.java, en la actualidad el nombre cambio por convención a App.java. 

	Ctest -> App
## Flujo de trabajo seguro
Gracias a esta separación, tu flujo de trabajo es seguro:
1. Escribes y modificas `App.java` en `src`.
2. Guardas el archivo (VS Code lo compilará automáticamente y actualizará `App.class` en `bin`).
3. Al ejecutar, la JVM lee `bin/App.class`.

# Notas:
1. Si usas Git o subes tu proyecto a GitHub, la regla es **ignorar las carpetas `bin` y `.vscode`** (usando un archivo `.gitignore`), ya que `bin` se puede regenerar compilando, y `.vscode` depende de la máquina de cada desarrollador. Solo debes subir `src`, `lib` (si usas librerías locales) y el `README.md`.
# Lasos
1. [[Java]]