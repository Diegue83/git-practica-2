# Respuestas - Taller Git

## ¿Qué sucede cuando hacemos un git add?

El comando `git add` agrega los archivos modificados al área de preparación (*staging area*). Esto significa que Git comenzará a rastrear esos cambios para incluirlos en el próximo commit.

---

## ¿Qué sucede cuando hacemos un git commit? ¿Dónde está ese commit?

El comando `git commit` guarda una instantánea de los cambios preparados en el historial local del repositorio.
Ese commit queda almacenado únicamente en la computadora local dentro del repositorio Git.

---

## ¿Por qué al hacer git commit todavía no está disponible ese commit en el repositorio remoto?

Porque `git commit` solo guarda los cambios de manera local.
Para enviar los cambios al repositorio remoto es necesario usar otro comando.

---

## ¿Qué hay que hacer para que veamos este commit en nuestro repositorio remoto de GitHub?

Debemos usar el comando:

```bash
git push
```

Este comando envía los commits locales al repositorio remoto de GitHub.

---

## ¿Qué diferencia hay entre hacer un fork o crear una nueva rama?

Un *fork* crea una copia completa de un repositorio en otra cuenta de GitHub.
Una rama (*branch*) crea una línea de trabajo separada dentro del mismo repositorio.

---

## ¿Qué comando se utiliza para crear una nueva rama sin cambiarte a ella?

```bash
git branch nombre-rama
```

---

## ¿Cuál es la diferencia entre los comandos git switch y git checkout al trabajar con ramas?

`git switch` se usa específicamente para cambiar entre ramas.
`git checkout` es un comando más antiguo y tiene múltiples funciones, como cambiar de rama o restaurar archivos.

---

## ¿Qué es una rama por defecto (como main o master) y por qué es importante?

Es la rama principal del repositorio donde normalmente se encuentra la versión más estable del proyecto.
Es importante porque sirve como base para el desarrollo y la colaboración.

---

## ¿Qué comando te permite ver la lista de todas las ramas locales de tu repositorio?

```bash
git branch
```

---

## En el contexto de Git, explica con tus propias palabras qué es una rama (branch) y cuál es su beneficio principal al trabajar en un proyecto de software

Una rama es una copia independiente de trabajo dentro del mismo proyecto.
Permite desarrollar nuevas funciones o realizar pruebas sin afectar el código principal.

---

## ¿Qué ha pasado con el contenido de la carpeta practica-taller-git? ¿Por qué no la podemos ver en nuestro repositorio remoto de GitHub?

La carpeta probablemente no fue agregada al repositorio usando `git add` o no se hizo `git push` después del commit.
Por eso los archivos todavía no aparecen en GitHub.

---