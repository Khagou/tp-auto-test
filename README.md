# tp-auto-test

Tests d'une application python avec RobotFramework, Unittest, Radon et pycodestyle.

L'application et les test sont hébergés sur des conteneurs docker avec un montage de volume entre la machine hote et les conteneurs et un reseau virtuel. 
Et l'ensemble des conteneurs est hébergé sur une VM avec une distribution linux.

Les images nécessaires ce trouvent sur le lien suivant:
 - https://hub.docker.com/repositories/khagu
 - application
 - raws:2.0.0
 - cyclomatique
 - robotframework
 - unit
 - pycodestyle

Installation:
- telechargez les images depuis le depot hub.docker:
  - par exemple: docker pull khagu/robotframework:tagname
- ainsi que l'enseble du code contenu dans le depot github:
  git clone git@github.com:Khagou/tp-auto-test.git
- puis placez vous à la racine du dossier à l'emplacement du fichier docker-compose.yml et lancez la commande.
  - docker compose up -d
 
Resultats:
Les resultats de chaque test ce trouveront dans le dossier rapport.
