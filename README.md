# Apuntes_UF2_2

**Optimización**

**Hediondez del código:** También llamado “code smell” en inglés, es síntoma en el código fuente que indica posiblemente un problema más profundo. Usualmente no son bug de programación (errores): no son técnicamente incorrectos y en realidad no impiden que el programa funcione correctamente. Indica deficiencias en el diseño que puede ralentizar el desarrollo o aumentan el riesgo de errores o fallos en el futuro. Es un motivo importante para realizar refactorización.

**Análisis de código**
+ Análisis dinámico (unit tests)
+ Análisis estático (lint)

**Análisis estático de código**
+ Mediante analizadores estáticos (linters): lint (C), sonar (Java), JSLint (Javascript), etc.
+ Mediante sitios web para inspección de código (Continuous Inspection): Scrutinizer, SonarQube, etc.

**Refactorización:** Es el proceso de reestructurar un código fuente, alterando su estructura interna sin cambiar su comportamiento externo. Técnicas:
+ Renombrado de variables
+ Pasar código duplicado a funciones
+ Eliminación de código inalcanzable
+ Eliminación de código redundante
+ Eliminación de código muerto

**Documentación**
+ Documentación de código
+ Documentación técnica
+ Documentación de usuario

**Formatos de documentación**
+ HTML (p. ej. Javadoc)
+ Markdown (p. ej. Gitbook)
+ reStructuredText (p. ej. Readthedocs)
+ asciiDoc

**Control de versiones**

**Sistemas más conocidos**
+ CVS
+ Subversion
+ Mercurial
+ Git

**GIT**
+ **Características**
  + Moderno
  + Distribuido
  + Eficiente
+ **Coceptos**
  + Repository (local & remote)
  + Commit
  + Branch: Checkout, Merge (fast-forward, 3-way)
+ **Áreas**
![ScreenShot](http://jamj2000.github.io/entornosdesarrollo/4/assets/git-areas1.png)

![ScreenShot](http://jamj2000.github.io/entornosdesarrollo/4/assets/git-areas2.png)
+ **Ramas**
![ScreenShot](http://jamj2000.github.io/entornosdesarrollo/4/assets/git-branches.png)
+ **Comandos**
    + Configuración: config 
    + Repositorios: clone, remote add, remote rm
    + Básicos: init, status, log, add, rm, commit, push, pull
    + Ramas (branches): branch, branch -d, merge, checkout, stash
    + Otros: diff, tag, submodule
+ **Sitios que soportan GIT**
    + GitHub
    + Bitbucket
    + GitLab
    + Coding -en chino-

