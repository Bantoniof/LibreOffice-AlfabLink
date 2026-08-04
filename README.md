Macro para insertar enlaces a las entradas de índices alfabéticos.
Writer no asigna enlaces a las entradas de los índices alfabéticos, esta macro pretende solucionar el problema creando marcadores en las palabras clave  dentro del texto e insertando una remisión en el número de página que aparece en el índice alfabético.
Basado en la macro del post de OpenOffice https://de.openoffice.info/viewtopic.php?t=76711&sid=d9a9e9a4ce3e80676e2a17ea9c40fb1a 
Localizado en  Inglés, Alemán y Español
Tras la instalación se crea la entrada AlfabLink en el menú Formato que lanzará el diálogo
Limitaciones:
- Solo procesa el primer índice alfabético que encuentra.
- Si se actualiza el índice, es necesario volver a ejecutar la macro. 
- En la exportación a PDF no todos los enlaces funcionan: Cuando hay dos entradas iguales, solo se exporta el enlace a la última página En el ejemplo:  LibreOffice Writer ……..4,18 solo se exporta el enlace a la página 18.
- Existe un problema no resuelto en LibreOffice que duplica entradas cuando se utiliza un archivo concordancias y este archivo se modifica https://bugs.documentfoundation.org/show_bug.cgi?id=44152 
