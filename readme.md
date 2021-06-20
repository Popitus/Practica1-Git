# Practica 1

Qué comando utilizaste en el paso 11? ¿Por qué?
      * git reset --hard HEAD~1.
      "Con el reset bajamos al commit anterior y con el hard lo que habia en el working copy, de manera que queda todo como estaba antes, vaciando 
        nuestro staging area"
        
¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
      * git reflog
      "Buscamos el codigo del commit que anteriormente hemos desecho"
      * git reset 46298f3
      "Nos movemos (HEAD) al commit anteriormente deshecho.
      * git restore git-nuestro.md
      "Restauramos el archivo.
      
El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
      "Mensaje por terminal: Already up to date"
      "No hace nada ya que intenta fusionar con su rama actual, está en la misma linea.
      
El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
      "Si causó un conflicto entre los cambios realizados en git-nuestro.md, ya que ha comparado ambos archivos y ha comprobar que hay diferencias.
      Nosotros tenemos que indicarle despues que hemos hecho cambios ya que git no entiende de códigos, solo de cambios."
      
El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
      "Sin conflicto, realiza un merge fast-forward, dejando el puntero en el mismo commit que styled. Anteriormente se ha creado una "bifurcación" hacia
      la rama htmlify. Por lo que ahora master puede "ver" los commits de styled hacia htmlify y desde styled hacia abajo.
      
¿Qué comando o comandos utilizaste en el paso 25?
      * git log --graph
  
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
- ¿Qué comando o comandos utilizaste en el paso 27?
- ¿Qué comando o comandos utilizaste en el paso 28?
- ¿Qué comando o comandos utilizaste en el paso 29?
- ¿Qué comando o comandos utilizaste en el paso 30?
- ¿Qué comando o comandos usaste en el paso 32?
- ¿Qué comando o comandos usaste en el punto 33?
