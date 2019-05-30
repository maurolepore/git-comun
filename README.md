
## Uso común de Git, GitHub y RStudio

Mauro Lepore

### Repositorio: **<http://bit.ly/git-comun>**

### Presentacion: **<http://bit.ly/git-comun-presentacion>**

# 

Este trabajo usa la licencia Creative Commons Attribution-ShareAlike 4.0
International License disponible en:

<http://creativecommons.org/licenses/by-sa/4.0>

–

Muchas ideas e imagenes vienen de:

<https://jennybc.github.io/wtf-2019-rsc/>

## Aprender a colaborar

### Aprender:

  - **Por que es importante usar Git/GitHub?**
  - **Que es un “commit”?**
  - **Bifurcar un repositorio**
  - **Trabajar en un tiquete**
  - **Solicitar fusión**

## Por que Git/GitHub?

Como se siente trabajar con y sin Git.

<div class="columns-2">

<img src="https://i.imgur.com/MBv5IJQ.jpg" align="center" width=325/>

<img src="https://i.imgur.com/uORi6QZ.png" align="center" width=325/>

</div>

.

[Excuse me, do you have a moment to talk about version
control?](https://peerj.com/preprints/3159/) (Jenny Bryan; Ingles)

# Motivacion

### Arreglar URLs en README.Rmd

[Tiquete modelo](https://github.com/forestgeo/fgeo.plot/issues/57)

## Camino corto

  - **Bifurcar un repositorio**

<img src="https://i.imgur.com/lVc3GFU.png" align="center" width=500/>

  - **Trabajar en un tiquete**

  - **Solicitar fusión**

<img src="https://i.imgur.com/6HhDogh.png" align="center" width=500/>

## Camino corto: Auto-bifurcar

*“You’re editing a file in a project you don’t have write access to.
Submitting a change to this file will write it to a new branch in your
fork fgeocomm/fgeo.plot, so you can send a pull
request.”*

<img src="https://i.imgur.com/Kkll2w8.png" align="center" width=760/>

## Camino corto: Trabajar en un tiquete

<img src="https://i.imgur.com/nMUKXdE.png" align="center" width=760/>

## Camino corto: Solicitar fusion

<img src="https://i.imgur.com/Ed8qevw.png" align="center" width=760/>

# Camino corto

[Demostrar](https://github.com/forestgeo/fgeo.plot/issues/57)

## Quieres practicar?

### [Tiquetes abiertos](https://github.com/search?utf8=%E2%9C%93&q=org%3Aforestgeo+is%3Aopen+%22Add+full+URLs+to+the+website%22&type=Issues)

<img src="https://i.imgur.com/XsYdXmI.png" align="center" width=760/>

## Que es un “commit”?

<img src="https://i.imgur.com/fmrhQOQ.png" align="center" width=760/>

## Que es un “commit”?

<img src="https://i.imgur.com/gadNgaY.png" align="center" width=760/>

## Que es un “commit”?

<img src="https://i.imgur.com/5MiM5RC.png" align="center" width=760/>

## Que es un “commit”?

<img src="https://i.imgur.com/m230nzj.png" align="center" width=760/>

## Que es un “commit”?

<img src="https://i.imgur.com/ZKksnVi.png" align="center" width=760/>

## Que es un “commit”?

<img src="https://i.imgur.com/PAgI3mX.png" align="center" width=760/>

## Que es un “commit”?

<img src="https://i.imgur.com/1nOkjOu.png" align="center" width=760/>

## Que es un “commit”?

<img src="https://i.imgur.com/AoxcNpK.png" align="center" width=760/>

## Que es un “commit”?

<img src="https://i.imgur.com/Gcv7fZU.png" align="center" width=760/>

## Que es un “commit”?

<img src="https://i.imgur.com/HS2tUli.png" align="center" width=760/>

## Que es un “commit”?

<img src="https://i.imgur.com/OPuzdBA.png" align="center" width=760/>

## Camino Largo

<img src="https://i.imgur.com/02ANh0I.png" align="center" width=760/>

## Camino Largo: Bifurcar

<img src="https://i.imgur.com/GKEbEAi.png" align="center" width=760/>

## Camino Largo: Clonar (GitHub)

<img src="https://i.imgur.com/A1sXnz8.png" align="center" width=760/>

## Camino Largo: Clonar (RStudio)

<img src="https://i.imgur.com/D5VwX1U.png" align="center" width=760/>

## Camino Largo: Trabajar en un tiquete

<img src="https://i.imgur.com/WF5xwcV.png" align="center" width=760/>

## Camino Largo: Hacer “Push”

<img src="https://i.imgur.com/6gUJuwy.png" align="center" width=760/>

## Camino Largo: Solicitar fusion

<img src="https://i.imgur.com/KEDeIvq.png" align="center" width=760/>

# Camino Largo

### [Demostrar](https://github.com/forestgeo/fgeo.plot/)

Clonar localmente

Clonar en rstudio.cloud:

  - Configurar *Tools \> Global options… Workspace*
  - Intentar primer “commit”
  - Introducirme a Git:

<!-- end list -->

``` bash
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

  - Hacer “commit”

<!-- end list -->

``` bash
git add .
git commit -m "Add full URLs (closes #57)"
```

  - Deshacer el ultimo commit (preservando los cambios)

<!-- end list -->

``` bash
git reset HEAD~1
```

  - Contrarestar el ultimo commit (preservando el commit)

<!-- end list -->

``` bash
git revert HEAD~1 --no-edit
```

  - Mas
poder

<!-- end list -->

``` bash
git rebase -i HEAD~3
```

## Extras (si hay tiempo)

### Instalacion: Ver [Pre-workshop set-up](https://happygitwithr.com/workshops.html#pre-workshop-set-up) (Ingles)

### Configuración: Demostrar `git config --global -l`

### Cambiar la historia: Demostrar `reset`, `revert`, `rebase -i`
