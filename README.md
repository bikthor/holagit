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

* Añadimos al stage los cambios:
```bash
git add .
```
* Confirmamos los cambios y los guardamos en nuestra DB local:
```bash
git commit -m "Cambios en el README"
```
* Subimos los cambios al repositorio remoto:
```bash
git push
```