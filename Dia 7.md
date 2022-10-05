FRESADO COMPUTACIONAL
CNC. Para los encastres se puede utilizar las librerias "50 Digital Join"
Selección de la herramienta en función de:
* El tipo de corte que deseamos.
* El tiempo y calidad de terminación que queremos para el trabajo
* Que saque el material hacia arriba (plástico, para no derretirlo y tener mejor terminación) o hacia abajo (madera, para mejor terminacion)

Realizar el diseño en Rhino en 2D, utilizando capas para cada tipo de perfinl de trabajo (cortar, calar, etc)
Plugin para pasar de Rino a impresión: RhinoCAM2018
Configurar "Box Stock"
*Ancho, Alto y prof de la mádera en la que se trabajará
*Cero de la máquina", sobre la madera
Conf "machine Operation"
*Define que se reakuzará para cada curva.
*Define si sera si los cortes serán Downct o upcut
*Define si el corte será por el centro, por dentro o por fuera
*Niveles de corte
*Definir la herramienta: Ej: plana de 6mm, diámetro de la parte sin fresa, velocidad de corte (definida por el fabricante de la fresa); etc Formula: cpt * flutes * RPM (tamaño de viruta * cuchillas de la herramienta * rpm)
Los 3 grados de libertad de velocidad se da por: Tipo de herramienta, RPM y velocidad de movimiento de los ejes.
Movimientos de traslado sobre la madera
Configurar los puentes en los cortes, para que la madera quede sujeta al material originak y no ocasione accidentes
