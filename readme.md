- ¿Qué comando utilizaste en el paso 11? ¿Por qué? 
  Git reset --hard HEAD\~1
Este comando deshace tanto el commit anterior como los cambios del working copy. Vuelve el puntero HEAD al commit anterior.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué? 
Git reflog
Para comprobar el identificador del commit que quiero recuperar
Git reset --hard \<commit-id>
Para volver a mover el puntero HEAD

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? Aparece el mensaje: “Already up to date” al hacer el merge, que quiere decir que la rama que estoy intentando mercera ya es un padre.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 
Aparece un conflicto porque hemos modificado el mismo documento, en las mismas lineas en ambas ramas, al intentar mergearlas aparece la advertencia del conflicto.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 
Git checkout main
Para cambiar el puntero HEAD a la rama main
Git branch 
Para comprobar que estoy en la rama correcta
Git merge styled

- ¿Qué comando o comandos utilizaste en el paso 25? 
Git log --graph --branches --oneline

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
Git merge --no-ff title
Mergea las ramas forzando a que no sea fast forward. Sí podría ser fast forward porque la rama main ya es un padre de la rama title

- ¿Qué comando o comandos utilizaste en el paso 27? 
git reset HEAD\~1

- ¿Qué comando o comandos utilizaste en el paso 28? 
git restore git-nuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29? 
git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30? 
git reflog
git reset --hard \<commit-id>

- ¿Qué comando o comandos usaste en el paso 32? 
Git reflog
git checkout \<commit-id>

- ¿Qué comando o comandos usaste en el punto 33? 
Git reflog
git checkout \<commit-id>


*Nota:he añadido a los comandos el elemento (\) porque el texto aparecía tachado
