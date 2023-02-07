# Primer día con Git y Github

Lista de comandos de Git

* Para poder ver la version de git ejecutamos en nuestro terminal:

```bash
git --version
git -v
```

* Para configurar el correo y nombre (solo la primera vez en mi maquina)


```bash
git config --global user.email "antonywilfor0129@gmail.com"
git config --global user.name "TonyWMR"
```

* Para ver la configuracion git
```bash
git config --list
```

* Para inicializar nuestro repositorio en Git:
```bash
git init
```

* Para ver el estado de nuestros cambios:


```bash
git status
```

* Para preparar nuestros archivos para la zona stage (prepararlos para commit)

```bash
git add .
git add nombredelarchivo.extension


* Crear el regisgtro de los cambios realizados:
```bash
git commit -m "comentario corto y conciso"
```


* Para ver una linea de tiempo de los commits que hemos realizado:


```bash
git log
```

* Para poder ver el detalle de un commit especifico:


```bash
git show id-de-commit
```