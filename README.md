# Codigo 13 - Develop

##Comando para GIT

```
git init
```

-Este comando solo se hace una vez por proyecto, sirve para inicializar nuestro proyecto con git.
-:eye: crea una carpeta  :file_folder: llamada 
.git

```
git status
```

-Poder listar y ver si los archivos estan listos para subir
-Ojo en caso los archivos no esten listos apareceran de color rojo y cuando esten seran de color verde

```
git add .
git add nombre_de_archivo
```

-Se encarga de agregar los archivos a la memoria de GIT, es decir los guarda en un stash

```
git commit -m "comentario"
```

-Crea un punto en la linea de tiempo de nuestros cambios y a estos se le es posible adjuntar un comentario.

- :eye: Los comentarios deben estar relacionados a los cambios que hice, esto es una recomendacíon

```
git push origin main
```

-Sirve para subir los cambios a nuestro repositorio en la nube, en este caso github

```
git pull origin main
```

-Sive para descargar los cambios de nuestro repositorio en la nube

```
git clon 
```
-Descarga toda la carpeta desde git.hub.com


```
git branch 
```
- Sirve para poder listar los branch que tengo localmente y me dice en cual me encuentro actualmente


```
git checkout -b nobre_de_branch
```
-Sirve para crear un branch nuevo y poder trabajar en el 

```
git checkout nobre_de_branch
```
-Sirve para pasar de un Branch a otro

