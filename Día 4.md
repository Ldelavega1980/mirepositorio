Diseño 3d
En el uso de Rhino, tener en cuenta las siguientes herramientas:

* Diferencia Booleana (Para restar entre 2 superficies)
* Extrusion de curvas (Para dar volumen a una figura plana)
* Contour (para tranasformar un cuerpo sólido en capas) Esto podría utilizarse para imprimir un cuerpo con un cortador laser
Una vez terminado el objeto a imprimir, es importante Exportar el objeto seleccionado a *.std

Impresión 3D
Una vez generado el archivo (*.std) es necesario procesarlo para transformarlo en Gcode (lenguaje que recibe la impresora)
Esta interfase la realizamos, en esta oportunidad, con el soft: Ultimaker Cura
En este soft es importante definir todos los parámetros de impresión, que dependen de las características de la impresora, y de la pieza a imprimir, ej:
* Que la capa superior debe tener más capas que la de abajo, debido a que no tiene superficie de dónde soportarse y queda más pandeada, a diferencia de la base.
* Cómo se rellenará el interior del cuerpo
* Que en el eje z la pieza tendrá menor resistencia, debido a la característia constructiva
* verificar que el diseño, con los pa rámetros seleccionados, muestre los detalles que se precisan.
* Tener en cuenta la resolución de la impresión, en los lados curvos, por la resolución de los motores pp
Antes de imprimir es importante :
* corregir la nivelación de la base
* se hace con un papel, de modo que el inyectors rose sensiblemente el papel, sin que haya mucha resistencia
