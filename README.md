# CKEditor 4

Editor von musikerseiten.de inkl. der Anpassungen der Labels und des Link-Menüs.

## Release

Um ein Release zu erstellen geht bitte in das CKEditor-Verzeichnis und führt folgenden Befehl aus

	./dev/builder/build.sh

Im Anschluss wird ein Release unter `dev/builder/release/` angelegt. Das Release hat den Namen "ckeditor". 
Danach bitte dieses Verzeichnis in das Musikerseiten-Verzeichnis verschieben. Bitte vorher den `public/javascripts/plugins/ckeditor` innerhalb des musikerseiten-Projekts umbenennen:

	mv dev/builder/release/ckeditor /<MUSIKERSEITEN_PFAD>/public/javascripts/plugins/ckeditor
  
Übernimmt bitte aus den umbenannten ckeditor-Ordner die `config.js`, `build-config.js`, danach könnt ihr den alten ckeditor-Ordner löschen und das Resultat commiten.

