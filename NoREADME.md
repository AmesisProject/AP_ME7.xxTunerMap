# AP_ME7.xxTunerMap
Sofrware to tuning ME7.xx Family

AP_ME7.xxTunerMap est un logiciel que je suis en train de créer pour modichier les cartographe moteur pour la famillle des ME7 Bosch.
Je travail sur un ME7.1.1 d'audi A3 3.2 VR6 identique GolfIV R32 et Golf V R32.
Après une lecteur en travers du WIKI SA disponible ici https://fr.wikipedia.org/wiki/Audi_S4 que est un calculateur ME7, j'ai compris plusier choses.
Après la lecteur d'un fichier complet sur le remaping d'un ME7.5 le fameux 1.8T 20V de S3 GolfIV GTI est audi TT. J'ai compris que le l'algorithe générale de la famile des ME7.xx suivait
sensiblement le même deroulement. La grande difference sont princepalement les sondes lambda à large bande que nous avont sur l'A3 3.2 VR6 qui nous ajuste les Ratio lambda très proprement.
Et que c'est un moteur atmospherique comtrairement a la S4 et la S3 qui ont des turbo. 

La 1er partie du logciel concerne la map KRKTE 
(qui est a peut près l'equivelent de la "Engine Constants" du logiciel TunerStudio pour les personnes travaillant sur les gestion programable)
Ce que j'en ai retenue c'est que la KRKTE doit se recalculer si l'on swap de nouveaux injecteur pour que les map correspondent avec le nouveau débit et AFR.
Normalement nous devons modifier egalement la carte KVB qui est enfait la correspendance de la KRKTE pour l'affichage de la consomation en directe sur l'ordinateur de bord, mais ça perso je m'en balek.
