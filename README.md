# Clase 01

## Markdown

# H1
## H2
### H3
#### H4
##### H5
###### H6

** Texto en negrita **

### Listas ordenadas
1. Item
2. Item
3. Item

### Lista desordenada
* Item
* Item
* Item

---
    git --version
---

```py
print("La suma de 2 + 2 es:", 2+2)
```
## GIT
    git --version

## Hacer la configuración global de GIT

    git config --global user.name "Marcelo Sidoruk"
    git config --global user.email "msidoruk@gmail.com"

## Para visualizar las configuraciones
    git config --get-regexp user
## COMANDOS CONSOLA
* touch: creo archivos vacios
* mkdir: creo directorios

## CREAR UN REPOSITORIO DE GIT (LOCAL REPO)
    git init

## Areas en GIT
* Working Directory (WD): Vamos a tener todos los archivos de proyecto
* Staging Area (SA): Area intermedia de confirmación de cambios.
* Local Repo (Cajita de Fotos - Commits): Los commits que voy haciendo

 ## Para saber el estado de los archivos de WD
    git status

## Agregar 
    git add .

## Pasar a Local Repo
    git commit -m "Primer commit"
    git commit -m "Agregue info en Readme"

## Para ver las diferencias entre el WD y Local Repo
    git diff

1) git add .
2) git status
3) git commit -m "Agrego info sobre commit y diff"

## Historial para ver las fotos o commits del Repositorio
    git log
    git log --oneline

## Vincula Repo Local a Repo Remoto
    git remote add origin https://github.com/marcelos27/sabado-clase01.git

## Subir los cambios al Repo Remoto
    git push -u origin master

## Para verificar si tengo el remoto configurado
    git remote
    git remote -v

## Subir al repo remoto mis archivos
    git push -u <repo-remoto> <repo-local>
    git push -u origin master

#