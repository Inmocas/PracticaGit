# PracticaGit
Práctica Git, Don Quijote de los Commits. Asignatura: elementos del diseño.
### Moral Castells, Indira

--

*1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?*

`git reset  --hard HEAD~1` 

Porque con esto se borraría lo último que hubiese sido añadido al Working Copy.

--

*2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?*

`git reflog`
`git reset --hard fae2bff` 

El primer comando para saber cuan sería la dirección donde queda lo que se ha reseteado, y 
el segundo para recuperarlo.

--

*3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?*


No, se ha hecho un merge utilizando la estrategia recursiva. 
Dice: Already up to date.

--

*4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?*


Si, dio conflicto porque se ha modificado el texto de don-quijote.md, y en esa rama no nos dejaría absorberlo.

--

*5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?*

No ha causado ningún conflicto, porque se ha hecho un merge utilizando estrategia recursiva. Ha sido un merge fast foward. La rama master tiene el mismo commit que la rama style, por lo que master absorbería todos los commits creados en la rama style y, al no haber ninguna ramificación, el único commit que debería copiar ya lo tenía. 

--

*6. ¿Qué comando o comandos utilizaste en el paso 25?*

`git graph` 

Para realizar el diagrama (gráfico).

--

*7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?*


 Si, porque al estar en la misma lista de ramas no cambiaría ningún commit de title al ser absorbido por master.

--

*8. ¿Qué comando o comandos utilizaste en el paso 27?*

`git reset HEAD~1` 

--

*9. ¿Qué comando o comandos utilizaste en el paso 28?*

`git checkout --don-quijote.md` 

--

*10. ¿Qué comando o comandos utilizaste en el paso 29?*

`git branch -D title`

--

*11. ¿Qué comando o comandos utilizaste en el paso 30?*

`git reflog`

`git reset --hard e0ad3bc`

--

*12. ¿Qué comando o comandos usaste en el paso 32?*

`git reflog`

`git reset --hard 49ad577`

--

*13. ¿Qué comando o comandos usaste en el punto 33?*

`git reflog`

`git reset --hard 45e2288`

--
