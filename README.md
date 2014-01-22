BLUE-PIXEL
==========
$ mkdir ~ / BLUE-PIXEL
 # Erstellt ein Verzeichnis für Ihr Projekt "BLUE-PIXEL" in Ihrem Benutzerverzeichnis

$ cd ~ / BLUE-PIXEL
 # Ändert das aktuelle Arbeitsverzeichnis auf die neu erstellte Verzeichnis

$ git init
 # Setzt die notwendigen Git-Dateien
 # Initialisiert leeren Git-Repository in / Users / BLUEPIXEL / BLUE-PIXEL/.git /

$ touch  README
 # Erstellt eine Datei namens "Readme" im HBLUE-PIXEL-Verzeichnis
 
 $ git add README
 # Stages your README file, adding it to the list of files to be committed

$git commit -m 'first commit'
 # Commits your files, adding the message "first commit"
 
 $ git remote add origin https://github.com/BLUEPIXEL/BLUE-PIXEL.git
 # Creates a remote named "origin" pointing at your GitHub repository

$ git push origin master
 # Sends your commits in the "master" branch to GitHub
