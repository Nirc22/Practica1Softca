# Practica1Softca
Repositorio de práctica semillero Softcaribbean.

Comandos utilizados hasta el momento:

>**git clone git@github.com:Nirc22/Practica1Softca.git**

Para clonar el repositorio en nuestro local.

>**code README.md**

Para abrir el archivo y modificarlo.

>**git add .**

>**git commit -am"Commit inicial"**

Agregamos el README.md al staging y realizamos el commit.

>**git pull**

>**git push**

Traemos todos los cambios del repositorio y hacemos push para subir los cambios que hemos realizado.

>**mkdir privada**

Creamos el archivo privado.txt y la carpeta privada.

Creado el archivo .gitignore colocamos dentro de este: 

>privado.txt

>privada

Para que sean ignorados el archivo privado.txt y la carpeta privada.
>**git add .**

>**git commit -am"gitignore y 1.txt"**

Hacemos commit de los cambios realizados.

>**git tag -a v0.1 -m"Primer tag"**

Creamos el primer tag y le agregamos un mensaje.

>**git push origin --tags**

Subimos el tag al repositorio remoto.

>**git branch v0.2**
>**git checkout v0.2**

Creamos la rama v0.2 y nos posicionamos en ella. 

Creamos el archivo 2.txt

>**git add .**
>**git commit -am"Archivo 2.txt"**
>**git push origin v0.2**

Hacemos commit y subimos los cambios al repositorio remoto.

>**git checkout main**
>**git merge v0.2**

Nos posicionamos en la rama main y hacemos merge con la rama v0.2.

Cambiamos los archivos 1.txt en la rama main y v0.2, provocando un conflicto.

>**git checkout main**
>**git merge v0.2**

Hacemos merge nuevamente, no arroja:

>Auto-merging 1.txt
>CONFLICT (content): Merge conflict in 1.txt
>Automatic merge failed; fix conflicts and then commit the result.

>**git branch --merged**
>**git branch --no-merged**

Mostramos las ramas que han tenido merge y las que no.

Resolvemos el conflicto.

>**git commit -am"Conflicto entre main y v0.2 solucionado, se deja el Hola"**

Agregamos el commit señalando que fue resuelto el conflicto.

>**git tag -a v0.2 -m"Segundo tag"**

Creamos el tag v0.2 con un mensaje.

>**git branch -d v0.2**

Borramos de nuestro local la rama v2.0.

>**git pull**
>**git push**
>**git push origin --tags**

Subimos los cambios al repositorio remoto.

>**git log --all --grahp**

Mostramos los commits con las distintas ramas y tags.
