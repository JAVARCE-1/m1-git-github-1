
# Comando y configuracion Git y Github
## Crear un nuevo repositorio
- crear un repositorio en su cuenta de github
- crea un archivo llamado (README.md) en su proyecto local
- crear un archivo (.gitignore) en su proyecto local "para ignorar los archivos y carpetas"

## Inicializar un nuevo repositorio Git

- para inicializar un nuevo repositorio de manera Local, ejecutar el siguiente comando:

```
git init
```

## Referencia del repositorio local al repositorio remoto de (GITHUB)
```
git remote add origin https://github.com/JAVARCE-1/m1-git-github-1.git
```
- para verificar: ejecutar los siguiente comandos

```
git remote
git remote -v
```

## Finalizando
```
git add .
git commit -m "configuracion incial de git"
git push origin master
```