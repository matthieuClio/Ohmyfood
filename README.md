# Ohmyfood

Welcome in the project Ohmyfood.

The folder sass contains a main file style.scss from which it will import all other file scss.
The style.scss will generate a file style.css and a file stile.css.map, for generate it, you need to download the dart-sass folder at this link :
https://github.com/sass/dart-sass/releases/tag/1.58.3

Extract the foldder dart-sass and and put it in the main folder (Ohmyfood).

Launch a terminal, check the emplacement where you are in the terminal, you need to be at the folder of the project (Ohmfood).
Now, you can write this commande in a terminal :
./dart-sass/sass sass/style.scss css/style.css --watch
