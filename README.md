# Lección 13 - Git y Github
## Branching Model

**Paso 1** 

* Se crea archivo hello.txt
* Se añade contenido a hello.txt
* Se agrega el archivo a git
* Commit "mi primer file"
* Push a branch master
![Alt-Text](docs/paso1.jpg)

**Paso 2**

* Se crea otro archivo otroFile.txt
* Se añade contenido a otroFile.txt
* Se agrega el archivo a git
* Commit "agregando un segundo file"
* Push a branch master
![Alt-Text](docs/paso2.jpg)

**Paso 3** 

* Se crea un nuevo branch nuevo-branch
* Se añade contenido a hello.txt en branch nuevo-branch
* Commit "nuevo texto para hello branch"
* Push a nuevo-branch
![Alt-Text](docs/paso3.jpg)

**Paso 4**

* Regresar a master
* Se valida que hello.txt no tiene el texto que se agregó en el branch
* Agregar nuevo contenido a hello.txt
* Commit "cambios en el master"
* Push a master
![Alt-Text](docs/paso4.jpg)

**Paso 5**

* Hacer merge de nuevo-branch a master
* Resolver conflictos
* Una vez resueltos hacer commit
* Commit "resolviendo conflictos"
* Push a master
![Alt-Text](docs/paso5.jpg)


Créditos imágenes: [Laboratoria](http://capitan-dev.laboratoria.la/tracks/2/courses/14/units/34/lessons/113/pages/764)
