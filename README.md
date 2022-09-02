# Primer dia con  Git/Github
 
 Comando para configurar el usuario y el correo

```bash
git config --global user.name "username"
```

* Sirve para poder empezar a usar el control de version en git
nuestra carpeta

* Esto solo se una vez por carpeta

```bash
git init
```

¨*para ver el estado de nuestros cambios

```bash
git status

```
 * Agrega los archivos a la memoria de la pc

 ```bash
 git add .
 ```

 *crear el registro de los cambios realizados

 ```bash
 git commit -m "comentario"
```

* Poder ver el historial de commits
[ ] Git log retorna un `id`  con este id vamos a poder ver el detalle de los cambios que se hicieron en este commit
```bash
git log
```


```bash
git  show id-de-commit
```