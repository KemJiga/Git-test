Comandos de Git
============

### Comandos básicos

| Comando | Descripción |
| ------- | ----------- |
| `git status` | Comprobar el status actual |
| `git add [nombre-del-archivo.txt]` | Añade un archivo a la zona de subir cambios |
| `git add .` | Añade todos los archivos del repositorio a la zona de subir cambios |
| `git reset [nombre-del-archivo.txt]` | Elimina un archivo a la zona de subir cambios |
| `git reset .` | Elimina todos los archivos del repositorio a la zona de subir cambios |
| `git commit -m "[Mensaje del commit]"` | Crea un mensaje explicativo de los cambios |
| `git rm -r [nombre-del-archivo.txt]` | Elimina un archivo (o carpeta) |

### Compartir y actualizar proyectos

| Comando | Descripción |
| ------- | ----------- |
| `git push origin [nombre de la rama]` | Envía una rama local al repositorio remoto |
| `git push` | Envía cambios al repositorio remoto (en la rama actual) |
| `git pull` | Actualiza el repositorio local al último commit enviado |
