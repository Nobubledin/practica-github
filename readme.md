1. git reset --hard HEAD~1 para volver al commit anterior. El modificador --hard se usa para borrar también el working copy.

2. git reflog para averiguar el hash del commit al que queremos volver. Y git reset con el hash del commit. Después git restore con el nombre del archivo para devolver su estado al del último commit.

3. No causó ningún conflicto porque la rama main no ha habido ningún cambio que la rama styled pueda absorber.

4. Hubo un conflicto porque en ambas ramas había un archivo con el mismo nombre pero diferente contenido.

5. No se produce ningún conflicto porque realizó un fast forward, moviendo la rama main al commit donde se encuentra la rama styled, de esta manera ambas ramas tienen acceso a la misma información.

6. git log --graph

7. No porque con el parámetro --no-ff especificamos que el merge no sea fast forward.

8. git reset HEAD~1

9. git restore git-nuestro.md

10. git branch -D title

11. git reset --hard con el hash del commit donde realizamos el merge.

12. git reset --hard con el hash del primer coomit realizado cuando creamos el poema.

13. git reset --hard con el hash del último commit.