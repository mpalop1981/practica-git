# practica-git
¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1
Con reset HEAD~1, me muevo al commit inmediatamente anterior. Se utilizo --hard para que working copy se quede con el codigo del commit anterior.

¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog
git reset --hard fdc4ce7
Busco con reflog el identificador del commit (fdc4ce7), uso --hard para que me mantenga el working copy de ese commit.

El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
La rama styled ya contiene los mismos cambios q la rama master con lo cual no hay conflictos.

El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
La rama styled y la rama htmlify han modificado el mismo fichero en las mismas lineas, por lo que al realizar el merge hay conflictos y hay q resolverlos usando el editor y quedandote con el codigo valido.

El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No hay conflicto porque solo la posicion de master se adelanta a la del commit de styled que esta justo por delante.

¿Qué comando o comandos utilizaste en el paso 25?
git log --graph --pretty=oneline

El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si, porque el commit de tittle esta justo un commit por delante de master. 

¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

¿Qué comando o comandos utilizaste en el paso 28?
git restore -- git-nuestro.md

¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

¿Qué comando o comandos utilizaste en el paso 30?
git reflog
git reset --hard 60a48fa

¿Qué comando o comandos usaste en el paso 32?
git reflog
git reset --hard fdc4ce7

¿Qué comando o comandos usaste en el punto 33?
git reflog
git reset --hard 750f6f0
