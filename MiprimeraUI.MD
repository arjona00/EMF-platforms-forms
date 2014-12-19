# Mi primera UI

En esta sección, recorreremos EMF Forms para generar nuestro primer formulario de ejemplo.


## Cargando el modelo de ejemplo

Para este tutorial, usaremos el modelo de ejemplo llamado "Make it happen". Modela un sencillo sistema de gestión de tareas e incluye las entidades "User", "UserGroup" y "Task". Sobre la ventana de proyectos pulsamos botón derecho "New -> Example"

![Figura 1 -Mi primera UI](http://i.imgur.com/7JSnmZt.png)

Selecciona "Make it happen: example model". En la siguiente ventana muestra los proyectos que serán importados a su ventana de trabajo. Estos son, el modelo y el bundle de edición.

![Figura 2 -Mi primera UI](http://i.imgur.com/QVAnve7.png)


## Creando la vista del modelo

La vista del modelo describe la UI como un formulario de un tipo de entidad. EMF Forms proporciona un asistente para generar nuevas vistas del modelo a partir de un fichero de modelo Ecore (.ecore).

Para arrancar el asistente, hacemos click derecho sobre el fichero "task.ecore" del modelo, "New -> EMF Forms -> Create View Model Project".

![Figura 3 -Mi primera UI](http://i.imgur.com/M1mdlhJ.png)

El asistente mostrará el formulario donde introduciremos el nombre de nuestro proyecto para la vista del modelo.

![Figura 4 -Mi primera UI](http://i.imgur.com/DA5YjKL.png)

En la siguiente ventana del asistente, muestra las entidades de nuestro modelo. Seleccione la entidad "User" y pulse siguiente.

Una vez finalizado, podremos ver el proyecto generado que contiene las vistas del modelo, y la vista generada "User.view".

## El Editor de la vista del modelo
