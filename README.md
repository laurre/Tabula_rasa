<p align="center">
  <img src="https://github.com/erebe/Tabula_rasa/raw/master/logo.png" alt="logo"/>
</p>

-----------

Tabula rasa est un editeur d'algorithme conçu pour répondre aux spécifications de l'IUT de Bayonne

Installation pour Windows :
---------------------------

	+ Se rendre sur https://github.com/erebe/Tabula_rasa
    + Cliquer sur le bouton "Download" en haut à droite
    + Télécharger la package "Tabula_Rasa-VX.X.zip"
    + Extraire tous les fichiers et lancer l'executable


Installation pour Linux (Nécessite Qt 5.5 d'installé et git) :
----------------------------------------------------------
	
    + Ouvrez un terminal et tapez "git clone git://github.com/erebe/Tabula_rasa.git "
    + cd Tabula_rasa
    + chmod +x build.sh
    + ./build.sh
    + sudo make install


Fonctionnalités prévues :
-------------------------	

    + Réaliser facilement un algorithme
    + Sauvegarder l'algorithme vers une image
    + Sauvegarder l'algorithme vers un fichier XML
    + Charger la sauvegarde XML
    + Rendre certains éléments de l'algorithme non reliable
    + Analyser la structure pour répérer des incohérences



Pourquoi le C++ comme choix de langage ? :
------------------------------------------
	Je connais le C#, Python et Java mais le C++ reste mon langage préféré
    (surtout avec le dernier standard C++1x) et permet de produire des applications portables.
    C'est plus un choix de coeur que de raison.


Pourquoi Qt ? :
--------------	
    J'avais comme principal objectif de produire une application portable. D'un point de vue 
    personnel je préfère GTK car il ne s'occupe que de l'interface et laisse
    au développeur entière liberté pour implémenter le coeur métier de l'application.
    Ayant déjà eu des problèmes à porter sous Windows des applications GTK 
    (surtout avec les librairies tierces), je me suis tourné vers Qt.
    Qt possède aussi des facilités de développement avec l'objet QGraphicsScene que GTK ne possède pas.





Date de début du projet, le 22/07/2011
