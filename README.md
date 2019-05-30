
## Uso común de Git, GitHub y RStudio

Mauro Lepore

### Repositorio: **<http://bit.ly/git-comun>**

### Presentación: **<http://bit.ly/git-comun-presentacion>**

# 

Este trabajo usa la licencia Creative Commons Attribution-ShareAlike 4.0
International License disponible en:

<http://creativecommons.org/licenses/by-sa/4.0>

–

Muchas ideas e imágenes vienen de:

<https://jennybc.github.io/wtf-2019-rsc/>

## Aprender a colaborar

### Aprender:

  - **Por que es importante usar Git/GitHub?**
  - **Que es un “commit”?**
  - **Bifurcar un repositorio**
  - **Trabajar en un tiquete**
  - **Solicitar fusión**

## Referencias

### Uso de Git desde la terminal versus RStudio

### Operaciones comunes

## Por que Git/GitHub?

Como se siente trabajar con y sin Git.

<div class="columns-2">

<img src="https://i.imgur.com/MBv5IJQ.jpg" align="center" width=325/>

<img src="https://i.imgur.com/uORi6QZ.png" align="center" width=325/>

</div>

.

[Excuse me, do you have a moment to talk about version
control?](https://peerj.com/preprints/3159/) (Jenny Bryan; Ingles)

# Motivación

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

## Camino corto: Solicitar fusión

<img src="https://i.imgur.com/Ed8qevw.png" align="center" width=760/>

# Camino corto

[Demostrar](https://github.com/forestgeo/fgeo.plot/issues/57)

## Quieres practicar?

### [CODE\_OF\_CONDUCT user:forestgeo language:RMarkdown](https://github.com/search?q=CODE_OF_CONDUCT+user%3Aforestgeo+language%3ARMarkdown&type=Code)

<img src="https://i.imgur.com/gxCV2D0.png" align="center" width=760/>

## Quieres practicar?

### [Tiquetes abiertos](https://github.com/search?utf8=%E2%9C%93&q=org%3Aforestgeo+is%3Aopen+%22Add+full+URLs+to+the+website%22&type=Issues)

<img src="https://i.imgur.com/XsYdXmI.png" align="center" width=760/>

## Que es un “commit”?

<img src="https://i.imgur.com/fmrhQOQ.png" align="center" width=760/>

## Que es un “commit”?

<img src="https://i.imgur.com/zizuprp.png" align="center" width=760/>

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

## Camino Largo: Solicitar fusión

<img src="https://i.imgur.com/KEDeIvq.png" align="center" width=760/>

# Camino Largo

### [Demostrar](https://github.com/forestgeo/fgeo.plot/)

## Camino Largo

### 1\. Clonar localmente

### 2\. Clonar en rstudio.cloud

# Configuración

## *Tools \> Global options… Workspace*

<img src="https://i.imgur.com/EsYl7OG.png" align="center" width=500/>

## Hola Git, soy Mauro

<img src="https://i.imgur.com/EEIF9oY.png" align="center" width=760/>

``` bash
git config --global user.email "maurolepore@gmail.com"
git config --global user.name "maurolepore"
```

# Terminal versus RStudio

## Crear/checkear/sincronizar una rama

<img src="https://i.imgur.com/spQyR4r.png" align="center" width=760/>

``` bash
git checkout -b 57_add-full-url

git push -u origin 57_add-full-url
# Mejor aún:
git config --global push.default "current"
git push
```

## Hacer “commit”

<img src="https://i.imgur.com/lXTXDTB.png" align="center" width=760/>

``` bash
git add .
git commit -m "Add full URLs (closes #57)"
```

## Editar el mensaje del ultimo “commit”

<img src="https://i.imgur.com/FLT3de1.png" align="center" width=760/>

``` bash
git commit --amend -m "Agregar URLs completos (closes #57)"
```

## Descartar cambios en escena

<img src="https://i.imgur.com/b2Cvwmt.png" align="center" width=760/>

``` bash
git reset --hard
```

## Cambiar de rama

<img src="https://i.imgur.com/5Xs2YEy.png" align="center" width=760/>

``` bash
git checkout master
```

## Agregar el remoto “upstream”

<img src="https://i.imgur.com/3fW3rwe.png" align="center" width=760/>

``` bash
# Agregar el remoto "upstream"
git remote add upstream git@github.com:maurolepore/fgeo.plot.git
```

# Solo en la terminal

## Actualizar contra el repositorio original

``` bash
git fetch upstream
git checkout master
git rebase upstream/master
```

–

Lo que yo realmente hago esta explicado
en:

<https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow>

## Deshacer “commits”; guardar cambios

``` bash
# ~1 deshace ultimo "commit"
# ~2 deshace ultimos 2 "commits"
# ~n deshace ultimos n "commits"
git reset HEAD~1
```

## Contrarrestar un “commit”

``` bash
# ~1 contrarresta el ultimo "commit"
# --no-edit escribe un mensaje automatico
git revert HEAD~1 --no-edit

# Contrarresta el "commit" con SHA a867f483
git revert a867f483 --no-edit
```

## Manipular la historia interactivamente

``` bash
# ~3 manipular la historia de los ultimos 3 "commits"
git rebase -i HEAD~3
```

    # Commands:
    # p, pick = use commit
    # e, edit = use commit, but stop for amending
    # s, squash = use commit, but meld into previous commit
    # ...
    #
    # These lines can be re-ordered; they are executed from top to bottom.
    #
    # If you remove a line here THAT COMMIT WILL BE LOST.

(Traducción en la siguiente pagina)

–

<https://about.gitlab.com/2018/06/07/keeping-git-commit-history-clean/>

## Manipular la historia interactivamente

  - Abortar y dejar todo tal como estaba

<!-- end list -->

``` bash
git rebase --abort
```

  - s: Colapsar dos o mas “commits” contiguos

  - e: Editar el mensaje del “commit”

<!-- end list -->

``` bash
git commit --amend -m "Editar mensaje"
git rebase --continue
```

  - Re-ordenar linear para re-ordenar “commits”
  - Borrar una linea para eliminar un “commit”
(CUIDADO\!)

## Apéndice

### Instalación: Ver [Pre-workshop set-up](https://happygitwithr.com/workshops.html#pre-workshop-set-up) (Ingles)

# Preguntas

### <https://github.com/maurolepore>
