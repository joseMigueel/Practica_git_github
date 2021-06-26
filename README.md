 # Práctica del curso de git, gitHub y Sourcetree
 ## Autor: Jose Migue Marrero Marrero
 
 ####  ¿Qué comando utilizaste en el paso 11? ¿Por qué?
 `git reset --hard HEAD~1`
- *Se deshizo el ultimo commit que hicimos. Utilizamos el `git reset --hard HEAD~1` ya que queriamos deshacer lo que habia en el working copy de manera que todo quede como estaba antes.*
 
  
 #### ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
`git reflog` , `git reset --hard 0356ffc`
- *`git reflog` nos muestra todo lo que ha pasado en nuestro repositorio. De tal forma podemos ver que el commit que queremos recuperar es el `0356ffc`*
- *`git reset --hard 0356ffc`. Utilizamos este comando para recuperar el ultimo commit.*
 #### El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
 - *No hay conflicto y se actualizo perfectamente.* 
 #### El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
- *si. conflicto de fusion  en git-nuestro.md. git modifica los archivos en conflicto que son aquellos que tienen modificaciones en la misma linea o que de alguna forma no es capaz de resolverlo.*

 #### El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
 *No hay conflicto. Se resuelve por <strong><em>fast-forward<em></strong> porque master no se ha modificado*.

 #### ¿Qué comando o comandos utilizaste en el paso 25?
 `git log --graph` *o para conseguir un grafico mas detallado podemos añadir argumentos*  `git log --oneline --decorate --graph --all`
 #### El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
- *Si. El mismo comando sin la opcion `--no-ff` implicaria un fast-forward por defecto.*
 #### ¿Qué comando o comandos utilizaste en el paso 27?
`git reset HEAD git-nuestro.md`
 #### ¿Qué comando o comandos utilizaste en el paso 28?
`git restore git-nuestro.md`
 #### ¿Qué comando o comandos utilizaste en el paso 29?
`git branch -d title`. *Podemos utilizar la opción `-D` para que git no nos hicera la pregunta de seguridad.*
 #### ¿Qué comando o comandos utilizaste en el paso 30?
`git checkout 157b779` o `git branch title`
 #### ¿Qué comando o comandos usaste en el paso 32?
`git log`, `git checkout 99e497c92dfd083aa393829a00528a2e8b7d4201`

 #### ¿Qué comando o comandos usaste en el punto 33?
`git reflog` *nos mostrara lo que ha pasado en el repositorio. El commit que queremos recuperar es el f247539 `git reset --hard f247539` de modo que todo quede como estaba.*






