# Recordar 1
en Git se manjan 3 estatus
1. Lo local: lo que se encuentra en la computadora lical
2. El ecenario: es la ecena que sera pasada al repositorio al realizar un comit
3. El repositorio: es el lugar donde se guardan los commits o instantanias que le pasamps de la ecena


comando para establecer el nombre
```sh
git config --global user.name 'munmmra'
```
comando para establecer el correo 
```sh
git config --global user.email 'munmmra@gmail.com'
```
comando para cambier el nombre del repositorio principal 
```sh
git config --global init.defaultBranch main
```
comando para inicializar el repositorio
```sh
git init
```
comando para ver el estatus de la ecena
```sh
git status
```
comando para agregar un archivo o carpeta a la ecena
```sh
git status
```
comando para pasar la esena al repositorio 
```sh
 git commit -m 'Add readme.md file'
```
comando para agregar todos los archivos y carpetas a la ecena
```sh
git status
```
comando para ver el historial de commits
```sh
git status
```
comando para regresar a un commit diferente esto te desconecta de la cabeza la -f es para
forzar la ejecución del comando
```sh
git checkout -f 3c8b1981b83d4dc9ae123565acd0531eb99d4d68
```
comando para regresar regrsar a la cabeza
```sh
git checkout -f 3c8b1981b83d4dc9ae123565acd0531eb99d4d68
```
# cargar agithube 
crear el repositorio en gihube.com y obtener la liga

comando para cambiar a la cabeza
```sh
git branch -M main
```
comando para establecer el repositorio remoto 
```sh
git remote add origin https://github.com/munmmra/mastering_git.git
```
comando para cargar el repositorio local al repositorio remoto 
```sh
git push -u origin main
```
