# textogcode
Traduce un fichero de texto a gcode.</br>
Para obtener la ayuda invocar programa con la opcion -h:</br>
$./textogcode -h</br>
Con la opcion -o se posibilita que la salida utilice o no subrutinas. </br>
grbl de momento no es compatible con el uso de subrutinas. LinuxCnc si es compatible.</br>
Para cambiar la fuente basta cambiar el valor de la variable 'fontfile' </br>
editando la linea 32 del fichero 'textogcode' </br>
Podemos añadir fuentes truetype utilizando la herramienta ttf2cxf_stream </br>
del proyecto F-Engrave-1.66_src </br>
