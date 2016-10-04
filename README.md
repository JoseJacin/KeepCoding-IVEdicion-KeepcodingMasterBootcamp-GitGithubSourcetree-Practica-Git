# KeepCoding_IVEdicion-KeepcodingMasterBootcamp-GitGithubSourcetree-PracticaGit
KeepCoding - IV Edición - KEEPCODING MASTER BOOTCAMP - git, github &amp; SourceTree

**Pregunta 1: ¿Qué comando utilizaste en el paso 11? ¿Por qué?:** <br />
**Respuesta 1:** <br />
<code>git reset --hard HEAD~1</code>. Ya que en el paso se especificaba que se tienen que perder los cambios del working copy.
<br /><br />

**Pregunta 2: ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?:** <br />
**Respuesta 2:** <br />
<code>git reflog</code> Para mostrar todo lo que ha pasado en el repositorio.<br />
<code>git reset --hard 5cb2e26</code> Para rehacer el último commit.
<br /><br />

**Pregunta 3: El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?** <br />
**Respuesta 3:** <br />
No. Por que la rama **styled** ya contiene a la rama master, mostrando el mensaje "*Already up-to-date*" al realizar el merge.
<br /><br />

**Pregunta 4: El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?** <br />
**Respuesta 4:** <br />
Si. Ya que en la rama **htmlify** se ha modificado el fichero *git-nuestro.md* en los mismos números de línea que en la rama **styled**.
<br /><br />

**Pregunta 5: El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?** <br />
**Respuesta 5:** <br />
No, puesto que se realiza un *Fast-forward* moviendo la rama **styled** al mismo commit donde está apuntando la rama **master**
<br /><br />

**Pregunta 6: ¿Qué comando o comandos utilizaste en el paso 25?** <br />
**Respuesta 6:** He usado el siguiente:<br />
<code>git log --graph --decorate --pretty=oneline</code><br />
Aunque durante toda la práctica he usado <code>git lg</code> Que contiene el siguiente alias:<br />
<code>log --color --graph --pretty=format:'%C(bold white)%h%Creset -%C(bold green)%d%Creset %s %C(bold green)(%cr)%Creset %C(bold blue)&lt;%an&gt;%Creset' --abbrev-commit --date=relative</code>
<br /><br />

**Pregunta 7: El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?** <br />
**Respuesta 7:** <br />
Si, puesto que desde la rama **master** se crea la rama **title** (en la que se realiza un *commit*), por lo que la rama **master** es la padre de la rama **title**.
<br /><br />

**Pregunta 8: ¿Qué comando o comandos utilizaste en el paso 27?** <br />
**Respuesta 8:** <br />
<code>git reset HEAD~1</code>. Ya que en el paso se especificaba que se tienen que mantener los cambios del *Working Copy*.
<br /><br />

**Pregunta 9: ¿Qué comando o comandos utilizaste en el paso 28?** <br />
**Respuesta 9:** <br />
<code>git checkout -- git-nuestro.md</code>. Ya que en el paso se especificaba que se tienen que descartar los cambios realizados en el fichero.
<br /><br />

**Pregunta 10: ¿Qué comando o comandos utilizaste en el paso 29?** <br />
**Respuesta 10:** <br />
<code>git branch -D title</code>. Ya que en el paso se especificaba que se tiene que eliminar la rama title. Se ha utilizado el parámetro *-D* ya que con *-d* aparecía el siguiente mensaje <code>The branch 'title' is not fully merged.</code> al no encontrarse "mergeado" completamente.
<br /><br />

**Pregunta 11: ¿Qué comando o comandos utilizaste en el paso 30?** <br />
**Respuesta 11:** <br />
<code>git reflog</code> Para mostrar todo lo que ha pasado en el repositorio.<br />
<code>git reset --hard 0fc9374</code> Para rehacer el merge deshecho en el paso anterior.
<br /><br />

**Pregunta 12: ¿Qué comando o comandos utilizaste en el paso 32?** <br />
**Respuesta 12:** <br />
<code>git reflog</code> Para mostrar todo lo que ha pasado en el repositorio.<br />
<code> git checkout 0fc9374</code> Para ir al commit inicial cuando se creó el poema en el paso 4.
<br /><br />

**Pregunta 13: ¿Qué comando o comandos utilizaste en el paso 33?** <br />
**Respuesta 13:** <br />
<code>git reflog</code> Para mostrar todo lo que ha pasado en el repositorio.<br />
<code>git checkout 72715bc</code> Para ir al commit final cuando se ha puesto el título al poema en el paso 23.
<br /><br />
