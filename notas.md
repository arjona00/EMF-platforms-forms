# Notas

Durante el proceso de creación del renderizadi con RAP, se produjeron una serie de errores en la ejecución. Las dependencias sobre org.eclipse.core.runtime y org.eclipse.emf.ecore no podían ser resueltas.

Para solucionarlo, hay que ir a Window -> Preferences. Plug-in Development -> Target Platform. Eliminamos Running Platform y aplicamos. Lugo hacemos click sobre Restore Defaults. Esto debería corregir el problema.

![](http://i.imgur.com/1WPAY3t.jpg)
