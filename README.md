# Mi primer pull request

1. Ir al repositorio del ejercicio

2. Haz clic en "Fork"

3. Crea una carpeta Ironhack. Puedes organizalo por semanas y días:

   Week-1 -> day-1

4. Clona el repositorio forqueado en la carpeta correspondiente (day-1). Cuando haces git clone url, se crea ya una carpeta con el nombre del lab automáticamente

5. Ya puedes abrir la carpeta en vsc para empezar a trabajar (en tu consola code .) Si no te funciona el comando code en la terminal: https://stackoverflow.com/questions/29971053/how-to-open-visual-studio-code-from-the-command-line-on-osx

6. Empezamos a trabajar en nuestro código, siguiendo las indicaciones del README

7. Cuando estemos listos, vamos a guardar los cambios. En nuestra consola:

   - git status

     Sirve para ver los archivos en los que hemos realizado cambios

   - git add . 

     Añades todos los cambios para ser guardados en nuestro repositorio

   - git commit -m "Added"

     Guardas los cambios con un mensaje 

   - git push origin master

     Empujas los cambios de tu repositorio local a tu repositorio remoto, es decir, a la copia del repo del ejercicio, que has forqueado al principio

8. Hacemos un Pull Request, para que el repositorio original los reciba. Cuando cliquemos, nos aparece un formulario:

   En el título

   -  Daily:  [MAD DE] Nombre

   - Pair:  [MAD PP] Nombre1 & Nombre 2

   En los comentarios:

   - Hasta donde he llegado (Ej: Iteración 3)
   -  Dificultad
   - Comentario

   