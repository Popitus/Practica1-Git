# Practica 1

-Qué comando utilizaste en el paso 11? ¿Por qué?
      * git reset --hard HEAD~1.
      "Con el reset bajamos al commit anterior y con el hard lo que habia en el working copy, de manera que queda todo como estaba antes, vaciando 
        nuestro staging area"
        
-¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
      * git reflog
      "Buscamos el codigo del commit que anteriormente hemos desecho"
      * git reset 46298f3
      "Nos movemos (HEAD) al commit anteriormente deshecho.
      * git restore git-nuestro.md
      "Restauramos el archivo.
      
-El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
      "Mensaje por terminal: Already up to date"
      "No hace nada ya que intenta fusionar con su padre. Al reves si se podria hacer"
      
-El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
      "Si causó un conflicto entre los cambios realizados en git-nuestro.md, ya que ha comparado ambos archivos y ha comprobar que hay diferencias.
      Nosotros tenemos que indicarle despues que hemos hecho cambios ya que git no entiende de códigos, solo de cambios."
      
-El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
      "Sin conflicto, realiza un merge fast-forward, dejando el puntero en el mismo commit que styled. Anteriormente se ha creado una "bifurcación" hacia
      la rama htmlify. Por lo que ahora master puede "ver" los commits de styled hacia htmlify y desde styled hacia abajo.
      
-¿Qué comando o comandos utilizaste en el paso 25?
      * git log --graph
      
-El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
      "Si, no habria problema. El puntero master se situaria a la misma altura que title."

-¿Qué comando o comandos utilizaste en el paso 27?
      * git reset styled
      
- ¿Qué comando o comandos utilizaste en el paso 28?
      * git restore git-nuestro.md
      
- ¿Qué comando o comandos utilizaste en el paso 29?
      * git branch -D title
      
- ¿Qué comando o comandos utilizaste en el paso 30?
      * git reflog
      "Para buscar el codigo de commit para volver al commit donde esta hecho el merge"
      * git reset b9c0247
      
- ¿Qué comando o comandos usaste en el paso 32?
      * git reflog
      * git reset f50bef7
      * git restore git-nuestro.md 
      
- ¿Qué comando o comandos usaste en el punto 33?
      * git reflog
      * git reset b9c0247
      * git restore git-nuestro.md 
