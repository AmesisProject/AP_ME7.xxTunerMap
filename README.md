# AP_ME7.xxTunerMap
Sofrware to tuning ME7.xx Family
https://sites.google.com/view/amesis-project/logiciel-fait-maison/ap_me7-xxtunermap?authuser=1
https://www.youtube.com/watch?v=G04ME9IdV2k&t=96s

AP_ME7.xxTunerMap est un logiciel que je suis en train de créer pour modichier les cartographe moteur pour la famillle des ME7 Bosch.
Je travail sur un ME7.1.1 d'audi A3 3.2 VR6 identique GolfIV R32 et Golf V R32.
Après une lecteur en travers du WIKI SA disponible ici https://fr.wikipedia.org/wiki/Audi_S4 que est un calculateur ME7, j'ai compris plusier choses.
Après la lecteur d'un fichier complet sur le remaping d'un ME7.5 le fameux 1.8T 20V de S3 GolfIV GTI est audi TT. 
J'ai compris que le l'algorithe générale de la famile des ME7.xx suivait sensiblement le même deroulement. 
La grande difference sont princepalement les sondes lambda à large bande que nous avont sur l'A3 3.2 VR6 qui nous ajuste les Ratio lambda très proprement.
Et que c'est un moteur atmospherique comtrairement a la S4 et la S3 qui ont des turbo. 

<p align="center">
  <img src="https://github.com/AmesisProject/AP_ME7.xxTunerMap/blob/main/NoReadMe/SharedScreenshot.jpg?raw=true" width="350" title="hover text">
</p>

La 1er partie du logciel concerne la carte KRKTE (valeur seul)
(qui est a peut près l'equivelent de la "Engine Constants" du logiciel TunerStudio pour les personnes travaillant sur les gestion programable)
Ce que j'en ai retenue c'est que la KRKTE doit se recalculer si l'on swap de nouveaux injecteur pour que les map correspondent avec le nouveau débit et AFR.
Normalement nous devons modifier egalement la carte KVB qui est enfait la correspendance de la KRKTE pour l'affichage de la consomation en directe sur l'ordinateur de bord, mais ça perso je m'en balek.

La KRKTE est en quelque sorte un coéficient qui sera utilisé en permanence dans la trategie de calcule d'injection. 
L'aventage de cette carte est que si l'on modifie sa valeur sans modifier les injecteurs, le calcule sera faussé ce qui très praique pour créer un FlexFuel ou E85 ethanol.
Car les constante de c'est calculateur on été etudier pour etre utiler avec un carburant Super sans plomb et nande ethanol.
Vous devez toute foie attendre un certaine addaptation en plusieur passe est avec le même utilisateur du véhicule suivant le style de conduite. 
IL EST PRIMODIAL de controler le cicle d'ouverture des injecteurs (duty cicle) avec une limite de à peut près 85% d'ouverture par cycle. 

Je vais tachez de faire évoluer le logiciel, c'est pour cela que j'ai choisis Google Sheet, car il sera en permanance disponible est a jour car je travail directement dessus.

Merci de me fair par de vos remarque et erreur de ma par dans l'onjet "Issue" prevue à cet effet dans GitHub.

Voici ce que j'ai compris déjà
https://www.youtube.com/watch?v=G04ME9IdV2k&t=96s


