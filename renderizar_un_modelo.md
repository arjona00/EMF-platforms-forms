# Renderizar un modelo

Hay varias formas de mostrar un formulario dentro de una aplicación personalizada. EMF Forms incluye renderizaciones para SWF, JavaFX y Web UIs (RAP).

Para integrar una UI dentro de una aplicación, los renderizadores de EMF Forms proporcionan una API que puede llamarse desde código. La API en si misma es especifica para el renderizador de la UI. El renderizador para SWT es significativamente diferente del renderizador JavaFX, sin embargo, mantienen muchas similitudes. 

En general, la API incluye tres parámetros:

- La instancia del modelo de nuestro dominio.
- La vista del modelo
- El enlace al objeto UI, especifica de cada renderizador.


## Renderizar una vista del model en web con RAP

RAP o Remote Application Platform, es una tecnología para el desarrollo de aplicaciones remotas. En nuestro caso, generaremos una aplicación web. También permite desarrollar una aplicación web y de escritorio, que actuarán sobre el mismo código fuente, sin necesidad de desarrollar ambas por separado.

EMF Forms proporciona una renderización de la vista del modelo compatible con RAP que puede ser visualizada en los navegadores actuales.

Para poder lanzar aplicaciones RAP desde eclipse, debemos instalar las herramientas RAP.

Desplegamos el menú Help -> Install new software, e instalamos de la siguiente fuente.

[http://download.eclipse.org/rt/rap/tools/3.0](http://download.eclipse.org/rt/rap/tools/3.0)

![](http://i.imgur.com/SubkQHr.jpg)

    Nota: Solo instalar RAP Tools, NO Target Components.

Consultar en el siguiente [link](https://www.eclipse.org/rap/downloads/) para consultar las últimas versiones disponibles.



    
## Otros renderizadores
