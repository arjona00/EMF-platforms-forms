# La primera UI

En esta sección, comenzamos a usar EMF Forms para generar nuestro primer formulario básico de ejemplo.


## Creando la vista del modelo

La vista del modelo describe la UI como un formulario de un tipo de entidad. EMF Forms proporciona un asistente para generar nuevas vistas del modelo a partir de un fichero de modelo Ecore (.ecore).

Para ello usaremos el modelo creado anteriormente junto con el editor generado de forma automática por el generador de código.

Sobre nuestro fichero ecore, pulsamos botón derecho y seleccionamos EMF Forms -> Create View Project.

Rellenamos el nombre del nuevo proyecto, y posteriormente, la UI inicial. En este caso, Sensor.

![Figura 1 - Mi primera UI](http://i.imgur.com/UGf4OOA.jpg)

Una vez acabado el proceso, ya tenemos nuestra primera UI básica generada.

Sobre el nuevo proyecto '.viewmodel', abrimos la carpeta 'viewmodels' y hacemos doble click sobre el fichero 'Sensor.view'.

Veremos una lista de los campos de nuestro formulario. Para activar la vista previa, hacemos click sobre el botón 'Open Preview' en la esquina superior derecha de nuestra vista del editor.

![Figura 2 - Mi primera UI](http://i.imgur.com/RDphS3D.jpg)

Podremos editar los campos del formulario, agruparlos, establecer restricciones, eliminarlos, etc., pero esto lo veremos en la siguiente sección. Ahora pasaremos a probar el funcionamiento de nuestro nuevo formulario.

![Figura 3 - Mi primera UI](http://i.imgur.com/fRwo0KG.jpg)


## Lanzando la aplicación de demostración

El próximo paso de un proyecto real debería ser la integración de nuestra vista en nuestra propia aplicación. Sin embargo, como demostración rápida de las capacidades de EMF Forms, ejecutaremos una aplicación de demostración.

Para crear la aplicación, hacemos click en el menú Run => Run Configurations. Añadimos una nueva configuración y escribimos su nombre.

En el desplegable 'Run an application' seleccionamos la opción 'org.eclipse.emf.ecp.application.e3.application'.

![Figura 4 - Mi primera UI](http://i.imgur.com/XC3LHHg.jpg)


Pulsamos sobre la pestaña 'Plug-ins' y seleccionamos 'features selected below' en el desplegable 'Launch with'.

Hacemos click sobre el botón 'Deselect All'.

![](http://i.imgur.com/bOukCkD.jpg)

Buscamos la característica 'org.eclipse.emf.ecp.demo.e3.feature' y la seleccionamos. Pulsamos sobre el botón 'Select Required'

![Figura 5 - Mi primera UI](http://i.imgur.com/OZsbgC1.jpg)


Click sobre el botón 'Add Plug.ins', y seleccionamos el modelo, el elemento '.edit' y el proyecto con las vistas '.viewmodel'.

![Figura 6 - Mi primera UI](http://i.imgur.com/woXnua3.jpg)

Nuestra configuración quedaría de la siguiente forma:

![Figura 7 - Mi primera UI](http://i.imgur.com/T073N5a.jpg)

Aplicamos, y ejecutamos.

Una vez abierta la aplicación, creamos un nuevo proyecto en la ventana del explorador del modelo.

![](http://i.imgur.com/L2k6EHv.jpg)

![](http://i.imgur.com/muT6szM.jpg)

Ahora podremos crear nuevos elementos de nuestro modelo.

![](http://i.imgur.com/tQFSJVz.jpg)

Vemos la distribución de los elementos del formulario tal como lo dispusimos en la edición de la vista.

![](http://i.imgur.com/sxvXSj1.jpg)









