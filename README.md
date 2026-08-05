
<h4 id="top"> <a href="#es">Español</a> &bull; <a href="#en">English</a> &bull; <a href="#de">Deutsch</a> </h4>
- (Translations in English and Deutsch have had machine translation assistance; sorry..)

<a id="es" href="#top">&uArr; Arriba</a></p>
## AlfabLink.oxt
Es una extensión para **LibreOffice Writer** con macros para insertar enlaces a las entradas de índices alfabéticos.

Writer no asigna enlaces a las entradas de los índices alfabéticos, (*Bug 71385*). Esta macro pretende solucionar el problema creando marcadores en las palabras clave dentro del texto e insertando una remisión en el número de página que aparece en el índice alfabético.

Está basada en la macro del post en alemán de OpenOffice <a href="./viewtopic.php?t=76711">Stichwortverzeichnis mit Links zu den betreffenden Seiten</a>

### Instalación y ejecución
- Se instala al igual que otras extensiones.
- Tras la instalación se crea la entrada ***AlfabLink*** en el menú **Formato** que lanzará el diálogo para ejecutar la macro.

### Limitaciones
- Solo procesa el primer índice alfabético que encuentra.
- Si se actualiza el índice, es necesario volver a ejecutar la macro. 
>En la exportación a PDF no todos los enlaces funcionan: Cuando hay varias entradas de la misma palabra en distintas páginas, solo se exporta el enlace a la última página   
 En el ejemplo:  **`LibreOffice Writer....4,18`** solo se exporta el enlace a la página 18.

<a id="en" href="#top">&uArr; Up</a></p>
## AlfabLink.oxt
It is an extension for **LibreOffice Writer** with macros to insert links to alphabetical index entries.

Writer does not assign links to alphabetical index entries, (*Bug 71385*).
This macro is intended to solve the problem by creating bookmarks on keywords within the text and inserting a reference to the page number that appears in the alphabetical index.

It is based on the macro from the German OpenOffice post <a href="./viewtopic.php?t=76711">Stichwortverzeichnis mit Links zu den betreffenden Seiten</a>
### Installation and execution
- Installs just like other extensions.
- After installation, the ***AlfabLink*** entry is created in the **Format** menu that will launch the dialog to execute the macro.

### Limitations
- It only processes the first alphabetical index it finds.
- If the index is updated, the macro needs to be run again. 
> When exporting to PDF, not all links work: When there are several entries of the same word on different pages, only the link to the last page is exported:  
In the example: **`LibreOffice Writer....4,18`** only the link to page 18 is exported.

<a id="de" href="#top">&uArr; Auf</a></p>
## AlfabLink.oxt
Es handelt sich um eine Erweiterung für **LibreOffice Writer** mit Makros zum Einfügen von Links zu alphabetischen Indexeinträgen.

Writer weist keine Links zu alphabetischen Indexeinträgen zu (*Bug 71385*).
Dieses Makro soll das Problem lösen, indem es Lesezeichen für Schlüsselwörter im Text erstellt und einen Verweis auf die Seitenzahl einfügt, die im alphabetischen Index erscheint.

Es basiert auf dem Makro aus dem deutschen OpenOffice-Beitrag <a href="./viewtopic.php?t=76711">Stichwortverzeichnis mit Links zu den betreffenden Seiten</a>
### Installation und Ausführung
- Lässt sich wie andere Erweiterungen installieren.
- Nach der Installation wird im Menü **Format** der Eintrag ***AlfabLink** erstellt, der den Dialog startet.

### Einschränkungen
- Es verarbeitet nur den ersten gefundenen alphabetischen Index.
- Wenn der Index aktualisiert wird, muss das Makro erneut ausgeführt werden. 
> Beim Export in PDF funktionieren nicht alle Links: Bei mehreren Einträgen desselben Wortes auf verschiedenen Seiten wird nur der Link zur letzten Seite exportiert   
 Im Beispiel: **`LibreOffice Writer....4,18`** wird nur der Link zur Seite 18 exportiert.