# EJERICIO 1
1. Ejercicios
   1. Al crear el directorio iniciamos un nuevo repositorio (local) con `git init`.
   2. --
   3. Al no haberlo añadido al repositorio con `git add .` estará ***unmodified***, en cambio después de añadirlo y hacer `git commit -m `"*mensaje*"` pasará a estar ***modificado***.
   4. No somos capaces de hacer push porque aún no hemos creado ni asociado el repositorio local con él repositorio remoto.
   5. Como dije anteriormente no hemos creado los branch
   6. Vamos en **github** en este caso y desde allí creamos un repositorio público.
   Para asociarlo con nuestro repositorio local en nuestra terminal añadimos los siguientes comandos:
      * `git remote add origin https://github/turepositorio`
      * `git branch -M main` 
    7. Despés de haber hecho push se nos muestra las conexiones con el repositorio
    8. Para ello únicamente usaremos:
       * `git push -u origin main`
    9. Veremos que los cambios de la snapshot están subidos en nuestro repositorio remoto [Visita mi repositorio](https://github.com/imvibbin/repo01).