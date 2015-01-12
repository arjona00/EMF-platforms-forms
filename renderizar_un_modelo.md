# Renderizar un modelo

Hay varias formas de mostrar un formulario dentro de una aplicación personalizada. EMF Forms incluye renderizaciones para SWF, JavaFX y Web UIs (RAP).

Para integrar una UI dentro de una aplicación, los renderizadores de EMF Forms proporcionan una API que puede llamarse desde código. La API en si misma es especifica para el renderizador de la UI. El renderizador para SWT es significativamente diferente del renderizador JavaFX, sin embargo, mantienen muchas similitudes. 

En general, la API incluye tres parámetros:

- La instancia del modelo de nuestro dominio.
- La vista del modelo.
- El enlace al objeto UI, especifica de cada renderizador.


## Renderizar una vista del modelo en web con RAP

RAP o Remote Application Platform, es una tecnología para el desarrollo de aplicaciones remotas. En nuestro caso, generaremos una aplicación web. También permite desarrollar una aplicación web y de escritorio, que actuarán sobre el mismo código fuente, sin necesidad de desarrollar ambas por separado.

EMF Forms proporciona una renderización de la vista del modelo compatible con RAP que puede ser visualizada en los navegadores actuales.

Para poder lanzar aplicaciones RAP desde eclipse, debemos instalar las herramientas RAP.

Desplegamos el menú Help -> Install new software, e instalamos de la siguiente fuente.

[http://download.eclipse.org/rt/rap/tools/3.0](http://download.eclipse.org/rt/rap/tools/3.0)

![](http://i.imgur.com/SubkQHr.jpg)

    Nota: Solo instalar RAP Tools, NO Target Components.

Consultar en el siguiente [link](https://www.eclipse.org/rap/downloads/) para consultar las últimas versiones disponibles.

Para nuestra demostración, importamos el modelo de ejemplo proporcionado por RAP.

    New -> Examples -> EMF Forms -> Make it happen: sample RAP application -> Next -> Finish.
    
Abrimos el fichero 'makeithappen_RAP.target', y esperamos hasta que se resuelvan las dependencias. Esto puede tardar unos minutos. Una vez resueltas, hacemos click en la parte superior derecha 'Set as target platform'.

![](http://i.imgur.com/HTN6xIT.jpg)

Una vez establecida la plataforma de destino de ejecución, click derecho sobre el fichero '.launch', y seleccionamos la opción 'Run as' -> 'RAP Application'. Esto nos abrirá la aplicación en un navegador (Puede ser necesario recargar el navegador si este muestra un error inicial).


## Otros renderizadores

- [JavaFX](http://eclipsesource.com/blogs/tutorials/emf-forms-renderer/#javafx)
- [SWT](http://eclipsesource.com/blogs/tutorials/getting-started-with-EMF-Forms/#swt)

