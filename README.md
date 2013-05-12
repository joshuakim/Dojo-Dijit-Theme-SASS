Dojo-Dijit-Theme-SASS
========================

Customize Dojo's Dijit Theme to use SASS and Compass!
Use any theme name! Not restricted to "Claro"

Based on version: dojo-release-1.9.0

...


------------------------------
DIRECTIONS:
* Copy "mytheme" folder to the Dijit's theme folder.
* mytheme is it's own SASS/Compass project, if you want to create a 2nd custom theme create a copy of this folder and rename the folder name and mytheme.scss and mytheme_rtl.scss

...


------------------------------
TO DO:
* Remove unnecessary mixins in _variables.scss that was converted from the original .less file, which can be handle now by Compass
* Ultimate goal: 


INVESTIGATE:
* _document.scss - review when this is used and the import to dojo.css


DEV NOTES:
.claro
.#{$theme}