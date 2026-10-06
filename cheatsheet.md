### ¿Qué hace cada comando de Git?

* **`git status`**
  Sirve para revisar cómo está nuestro proyecto. Nos muestra qué archivos tienen cambios, cuáles están preparados para guardar en un commit y cuáles todavía no hemos agregado.

* **`git add`**
  Se utiliza para seleccionar los archivos o cambios que queremos incluir en el siguiente commit. Es como decirle a Git: “estos cambios sí quiero guardarlos”.

* **`git commit`**
  Guarda de manera permanente los cambios que previamente agregamos con `git add`. También permite escribir un mensaje para indicar qué se modificó en ese momento.

* **`git push`**
  Envía los commits que tenemos guardados localmente hacia GitHub. De esta manera, los cambios que hicimos en nuestra computadora también quedan disponibles en el repositorio remoto.

* **`git pull`**
  Hace lo contrario de `git push`: trae los cambios que existen en el repositorio de GitHub y que todavía no tenemos en nuestra computadora. Es útil cuando otras personas modificaron el proyecto o cuando trabajamos desde otro equipo.

* **`git log`**
  Muestra el historial de commits del proyecto. Podemos ver qué cambios se han guardado, quién los hizo, cuándo se hicieron y el mensaje que se escribió en cada commit.

* **`git diff`**
  Permite comparar los cambios que hemos hecho en los archivos con la última versión registrada. Es útil para revisar exactamente qué líneas modificamos antes de hacer un commit.

* **`git restore`**
  Sirve para deshacer cambios que todavía no hemos guardado en un commit. Por ejemplo, si modificamos un archivo y nos arrepentimos, podemos regresar el archivo a su versión anterior.

* **`git restore --staged`**
  Se utiliza cuando agregamos un archivo con `git add`, pero después decidimos que no queremos incluirlo en el próximo commit. Lo saca del área de preparación, pero **no elimina los cambios que hicimos en el archivo**.

