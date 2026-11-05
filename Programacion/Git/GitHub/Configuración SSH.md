1. Generar la llave SSH en tu computadora
- Abre la terminal y ejecuta el comando
```Bash
ssh-keygen -t ed25519 -C "tu_correo@ejemplo.com"
```

- Presionaste **Enter** en la primer pregunta que es para confirmar la ruta en la cual se crearan los archivos, ejemplo:  (`C:\Users\MadDog/.ssh/id_ed25519`).
- Te pide si quieres una contraseña para hacer la conexión, si quieres una escríbela, sino solo da **Enter** dejando en blanco la petición. Si pusiste contraseña, te pedirá confirmación, por lo tanto la tendrás que volver a escribir. 

2. Copiar y registrar la llave en GitHub

- Copia la clave generada en el archivo .pub (Este ejemplo es para windows, puedes abrir el archivo con el block de notas, o otro editor de textos, por ejemplo vim)
```Bash
clip < ~/.ssh/id_ed25519.pub
```

- Dirigete a **GitHub** -> **Settings** (en tu perfil global) -> **SSH and GPG Keys**.

- Añadiste una **New SSH Key** como llave de autenticación (_Authentication Key_) con permisos de escritura.

3. Vincular tu carpeta local con GitHub

- Como tu carpeta local ya tenía un enlace previo que daba error, lo corregiste y actualizaste la dirección SSH de tu nuevo repositorio con el comando:
```bash
    git remote set-url origin git@github.com:djts150592-eng/Notas.git   
```

4. Subir la información (Push)

- Finalmente, enviaste todos tus archivos locales a la plataforma ejecutando:
```Bash
git push -u origin main
```
- Confirmaste la autenticidad escribiendo `yes` la primera vez, ¡y tus notas quedaron guardadas exitosamente en la nube!

# Lasos
1. [[Git]]