# Práctica GIT

### Reina Sáez, Adrián

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1`

Porque con este comando deshacemos el último commit realizado y eliminamos los cambios realizados en el área de trabajo.

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog`
`git reset --hard 8ed21b4`

Con el primer comando vemos el registro de todos los commits, resets, cambios de rama, etc... que hemos realizado.
Con el segundo comando reseteamos al punto donde se realizó el segundo commit que borramos previamente.

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

La rama styled ya contenía los commits de la rama master.

--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Sí, porque un archivo con el mismo nombre tiene contenidos distintos en cada una de las ramas.

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No.

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git graph`

--

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Sí, porque solo hay un commit de diferencia entre ellos. 

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1`

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout -- don-quijote.md`

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title`

--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog`
`git reset --hard 220466f`

--

**12. ¿Qué comando o comandos usaste en el paso 32?**

`git reflog`
`git reset --hard 1c70383`

--

**13. ¿Qué comando o comandos usaste en el punto 33?**

`git reflog`
`git reset --hard 220466f`
