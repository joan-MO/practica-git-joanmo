# Práctica del curso de git, gitHub y Sourcetree

**¿Qué comando utilizaste en el paso 11? ¿Por qué?**
El comando que he utilizado es `git reset –hard HEAD~1` porquè con la opción --hard nos ahorramos poner dos comandos `git reset + git restore *` y a la vez hacemos que afecte en el working directory cosa que si lo hacemos sin la opción –hard evitamos que afecte al working directory pero si queremos que afecte entonces tendremos que poner `git reset + restore` y en este caso queremos que sea así por eso al final he utilizado esta opción --hard.

**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
El comando que he utilizado es `git reset –hard (hash-commit)` / `git reset –hard d838ecf` para así volver al commit donde modificacamos el contenido del archivo git-nuestro con la opción --hard para asi modificar nuestro working directory dejándolo como estaba en sese commit sin tener que poner git reset y luego git restore.

**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
Al hacer el merge no me causó ningún conflicto porque la rama en que me encuentro actualmente quiere absorber una rama en la cual ya tiene todas sus características y diciéndolo de otra forma todos sus commits o cambios.

**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
Si que hay conflicto ya que se encuentran en el mismo nivel de commits donde se modificó el archivo git-nuestro.md que en cada rama tiene un contenido diferente.

**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
No hubo conflicto ya que tanto la rama actual como la rama que queremos absorber no hay ningún commit al mismo nivel asi que cuando hacemos el merge este se queda con el commit donde se modificó el archivo de la rama styled en fin que nos quedamos con las características o commits que no teníamos en la actual rama.

**¿Qué comando o comandos utilizaste en el paso 25?**
El comando que he utilizado es `git graph` pero este comando es un alias creado anteriormente con el comando `git config --global alias.graph "log --graph --pretty=oneline"` y con opción –global para que afecte cualquier repositorio.

**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
El comando que he utilizado es `git merge –no-ff` y si que podría ser ya que están en la misma línea de tiempo o nivel de commit.

**¿Qué comando o comandos utilizaste en el paso 27?**
El comando que he utilizado es `git reset (hash-commit)` / `git reset aef3697`

**¿Qué comando o comandos utilizaste en el paso 28?**
El comando que he utilizado es `git restore file` / `gi restore git-nuestro.md`

**¿Qué comando o comandos utilizaste en el paso 29?**
El comando que he utilizado es `git branch –D title`

**¿Qué comando o comandos utilizaste en el paso 30?**
He utilizado el comando `git reset –hard a687898` para volver al commit donde absorbimos la rama title donde metimos un titulo.

**¿Qué comando o comandos usaste en el paso 32?**
He utilizado el comando `git reset --hard HEAD@{19}`

**¿Qué comando o comandos usaste en el punto 33?**
He utilizado el comando `git reset –hard a687898`
