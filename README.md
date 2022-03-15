# Laboratorio Git 101

## Comandos git:

* Inicializamos el repositorio local:
```bash
git init
```
* Añadimos el repositorio remoto:
```bash
git remote add origin git@github.com:bikthor/holagit
```
* Hacemos un push a la rama master de nuestro repositorio remoto (upstream):
```bash
git push -u origin master
```

## En caso de hacer cambios:

* Añadimos al repositorio local los datos del proyecto (cambios):
```bash
git add .
```
* Hacemos un commit (confirmamos los cambios):
```bash
git commit -m "Cambios en el README"
```
* Hacemos un push de los cambios (los subimos al repositorio remoto):
```bash
git push
```