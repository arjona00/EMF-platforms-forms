# El metamodelo

Para el desarrollo del tutorial, construiremos un metamodelo de ejemplo haciendo uso de EMF.

Para ello sobre la ventana de proyectos con botón derecho o desde el menú "File" seleccionamos "New -> Other". En la lista de proyectos seleccionamos "Empty EMF Project".

![](http://i.imgur.com/35EM1wN.png)

![](http://i.imgur.com/Q0Ub11a.png)

Diseñaremos el metamodelo usando el editor visual Ecore Diagram. Sobre la carpeta model generada, botón derecho "New -> Other". En la lista de elementos seleccionamos "Ecore Diagram".

![](http://i.imgur.com/BshDQIP.png)


Diseñamos nuestro metamodelo basado en Ecore. En este caso tratamos de modelar una distribución de señales recogidas por sensores.

![](http://i.imgur.com/yKrKf2E.png)

Para ello creamos la clase "LoboRojo" que dará nombre a nuestro esquema y del que colgarán los demás elementos. 

Creamos la clase sensor