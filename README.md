# practica-git
Práctica de Git para Bootcamp Full Stack XV 2023


Preguntas práctica:
¿Qué comando usaste en el paso 11? ¿Por qué?
Un git reset --soft HEAD~1 para deshacer el commit peor dejando los cambios en el staging area.

¿Qué comando usaste en el paso 12? ¿Porqué?
Usando git reflog, comprobé el id del commit anterior e hize un git reset {número de commit} para volver a ese commit.

El merge del paso 13: ¿causó algún conflicto? ¿Porqué?
No creo que conflicto porque aunque ambas versiones del poema diferían, styled es un versión posterior, por lo que fue un merge "fast-forward".

El merge del paso 19, ¿causó algún conflicto? ¿Porqué?
Aquí fue un merge no fast forward porque al mergear una rama con la otra, siendo styled una versión anterior, como ésta absorve a htmlify, es un merge "no fast forward" y hubo que solucionar conflictos para completar el merge.

El merge del paso 21: ¿cuasó algún conflicto?
No porque fue fast forward también.

¿Qué comandos utlizaste en el paso 25? ¿Porqué?
Git graph

El merge del paso 26 ¿podría ser un fast forward? ¿porqué?
Si podría serlo porque ""title" solo añade el título sin alterar el resto del contenido.

¿Qué comando o comandos utliziaste en el paso 27?
Git reset --soft HEAD~

¿Qué comando usaste en el paso 28?
git restore

¿Qué comando o comandos usaste en el paso 29?
git branch -D title

¿Qué comando o comandos utliziaste en el paso 30?
Volver al commit anterior con git reset

¿Qué comando o comandos usaste en el paso 32?
Lo mismo, git reset al commit, en modo detached head, no a una rama

¿Qué comando o comandos usast e en el punto 33?
Fui a git reflog y mire el committ en el que puse: "add title" : ese el commit cuando lo creé. 




