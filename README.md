# Guia GitHub
Comandos más esenciales de Git para trabajar en proyectos de desarrollo.
## 1. Crear repositorio
[Crear nuevo repositorio](https://github.com/new)
* ### Inicializar un repositorio
Crea un nuevo repositorio Git en el directorio actual. Este comando inicializa una carpeta oculta .git donde se almacena toda la información del repositorio.
```
git init
```
* ### Ver el estado del repositorio
Muestra el estado actual del repositorio, incluyendo archivos modificados, archivos en staging (preparados para commit) y archivos sin seguimiento.
```
git status
```
* ### Trabajar con repositorios remotos
Agrega un repositorio remoto (por ejemplo, en GitHub) con el nombre origin. Luego, puedes subir cambios con.
```
git remote add origin <url_del_repositorio>
```
## 2. Clonar repositorio
Descarga un repositorio remoto (por ejemplo, de GitHub, GitLab, etc.) en tu máquina local. Crea una copia completa del repositorio, incluyendo su historial.
```
git clone <url_del_repositorio>
```
## 2. Clonar repositorio
Descarga un repositorio remoto (por ejemplo, de GitHub, GitLab, etc.) en tu máquina local. Crea una copia completa del repositorio, incluyendo su historial.
```
git remote -v
```
## 3. Actualizar 
* ### Repositorio Github
Envía los commits locales a la rama especificada del repositorio remoto.
* ### Proyecto local
Descarga los cambios del repositorio remoto y los fusiona con tu rama local.