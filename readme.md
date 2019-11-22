- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
  He utilizado git reset --hard HEAD~1 porque este elimina los cambio realizado en el working copy
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
  git reflog para ver que ha pasado y buscar el commit. DEspués he usado git reset --hard al número para recuperar
- El merge del paso 13, ¿Causó algún con?icto? ¿Por qué?
  No, todo correcto.
- El merge del paso 19, ¿Causó algún con?icto? ¿Por qué?
  Si que creó conflicto porque los archivos eran diferentes.
- El merge del paso 21, ¿Causó algún con?icto? ¿Por qué?
  No
- ¿Qué comando o comandos utilizaste en el paso 25?
  He usado git log --graph
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
  Si, podría haber sido, había un archivo y no habría dado conflicto
- ¿Qué comando o comandos utilizaste en el paso 27?
  git log para situarme, y git reset HEAD~1 para deshacer el ultimo commit que crea el merge no fast forward
- ¿Qué comando o comandos utilizaste en el paso 28?
  He utilizado git restore git-nuestro.md
- ¿Qué comando o comandos utilizaste en el paso 29?
  git checkout master para asegurarme que no estaba en la rama y git branch -D title
- ¿Qué comando o comandos utilizaste en el paso 30?
  git log y git reset al número del commit
- ¿Qué comando o comandos usaste en el paso 32?
  git reflog y git checkout al numero del primer commit
- ¿Qué comando o comandos usaste en el punto 33?
  git reflog y git checkout al numero del commit donde puse el titulo
