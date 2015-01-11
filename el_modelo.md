# El metamodelo

Para el desarrollo del tutorial, construiremos un metamodelo de ejemplo haciendo uso de EMF.

Para ello sobre la ventana de proyectos con botón derecho o desde el menú "File" seleccionamos "New -> Other". En la lista de proyectos seleccionamos "Empty EMF Project".

![](http://i.imgur.com/35EM1wN.png)

![](http://i.imgur.com/Q0Ub11a.png)

Diseñaremos el metamodelo usando el editor visual Ecore Diagram. Sobre la carpeta model generada, botón derecho "New -> Other". En la lista de elementos seleccionamos "Ecore Diagram".

![](http://i.imgur.com/BshDQIP.png)


Diseñamos nuestro metamodelo basado en Ecore. En este caso tratamos de modelar una distribución de señales recogidas por sensores.

![](http://i.imgur.com/pqp0ztG.jpg)

Para ello creamos la clase "LoboRojo" que dará nombre a nuestro esquema y agrupará los demás elementos. 

Creamos la clase Sensor y sus propiedades. La clase sensor estará compuesto de una serie de señales recogidas, que serán de tipo Sonido, Vital o Imagen, por lo que creamos un enumerado para cada uno de estos tipos.

La clase Señal tendrá unas propiedades básicas y se especializa en los tres tipos antes nombrados.

Una vez realizado el diagrama, lo guardamos.

Vamos al fichero ecore y hacemos click sobre el modelo.
Rellenamos las propiedades.


![](http://i.imgur.com/WJKWrkN.jpg) 

Una vez rellenos los campos, botón derecho sobre el modelo seleccionamos la opción Validate.


![](http://i.imgur.com/PdpAi6e.jpg) 

Ya tenemos nuestro modelo creado.


S






















