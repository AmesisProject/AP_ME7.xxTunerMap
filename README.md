#VE AP_ME7.xxTunerMap

Sofrware to tuning ME7.xx Family

https://sites.google.com/view/amesis-project/logiciel-fait-maison/ap_me7-xxtunermap?authuser=1

https://www.youtube.com/watch?v=G04ME9IdV2k&t=96s

AP_ME7.xxTunerMap is software I am creating to modify engine maps for the Bosch ME7 family.
I am working on an Audi A3 3.2 VR6 ME7.1.1 identical to GolfIV R32 and Golf V R32.
After reading through the WIKI SA available here https://fr.wikipedia.org/wiki/Audi_S4 which is an ME7 calculator, I understood several things.
After reading a complete file on the remaping of an ME7.5 the famous 1.8T 20V from S3 GolfIV GTI is audi TT.
I understood that the general algorithm of the ME7.xx family followed more or less the same process.
The big difference is mainly the wideband lambda sensors that we have on the A3 3.2 VR6 which adjusts the Lambda Ratio very cleanly.
And that it is an atmospheric engine unlike the S4 and S3 which have turbo.

<p align = "center">
  <img src = "https://github.com/AmesisProject/AP_ME7.xxTunerMap/blob/main/NoReadMe/SharedScreenshot.jpg?raw=true" width = "350" title = "hover text">
</p>

The 1st part of the software concerns the KRKTE card (value only)
(which is roughly the equivalent of the "Engine Constants" of the TunerStudio software for people working on programmable management)
What I learned from this is that the KRKTE must be recalculated if we swap new injectors so that the cards correspond with the new flow and AFR.
Normally we also have to modify the KVB card which is in fact the correspondence of the KRKTE for the display of the consumption live on the on-board computer, but that I personally don't care.

The KRKTE is in a way a coefficient which will be used permanently in the injection calculation strategy.
The advantage of this card is that if we modify its value without modifying the injectors, the calculation will be distorted which is very practical to create a FlexFuel or E85 ethanols.
Because the constants of this calculator have been studied to be used with a super unleaded fuel and not ethanol.
You should however expect some addaptation in multiple passes is with the same vehicle user depending on the driving style.
IT IS PRIMODIAL to control the opening cycle of the injectors (duty cycle) with a limit of about 85% opening per cycle.

I will try to make the software evolve, that's why I chose Google Sheet, because it will be permanently available and up to date because I am working directly on it.

Thank you for informing me of your remark and error of my by in the tab "Issue" provided for this purpose in GitHub.

Here is what I already understood
https://www.youtube.com/watch?v=G04ME9IdV2k&t=96s



#VF AP_ME7.xxTunerMap
  ^ ^
=( '.')=
( ")_( ")
Sofrware to tuning ME7.xx Family

https://sites.google.com/view/amesis-project/logiciel-fait-maison/ap_me7-xxtunermap?authuser=1

https://www.youtube.com/watch?v=G04ME9IdV2k&t=96s

AP_ME7.xxTunerMap est un logiciel que je suis en train de créer pour modifier les cartographie moteur pour la famille des ME7 Bosch.
Je travaille sur un ME7.1.1 d'audi A3 3.2 VR6 identique GolfIV R32 et Golf V R32.
Après une lecture en travers du WIKI SA disponible ici https://fr.wikipedia.org/wiki/Audi_S4 qui est un calculateur ME7, j'ai compris plusieur choses.
Après la lecture d'un fichier complet sur le remaping d'un ME7.5 le fameux 1.8T 20V de S3 GolfIV GTI est audi TT. 
J'ai compris que le l'algorithe générale de la famile des ME7.xx suivait sensiblement le même deroulement. 
La grande difference sont princepalement les sondes lambda à large bande que nous avont sur l'A3 3.2 VR6 qui nous ajuste les Ratio lambda très proprement.
Et que c'est un moteur atmospherique comtrairement a la S4 et la S3 qui ont des turbo. 

<p align="center">
  <img src="https://github.com/AmesisProject/AP_ME7.xxTunerMap/blob/main/NoReadMe/SharedScreenshot.jpg?raw=true" width="350" title="hover text">
</p>

La 1er partie du logiciel concerne la carte KRKTE (valeur seule)
(qui est a peut près l'equivelent de la "Engine Constants" du logiciel TunerStudio pour les personnes travaillant sur les gestions programmable)
Ce que j'en ai retenue c'est que la KRKTE doit se recalculer si l'on swap de nouveaux injecteurs pour que les cartes correspondent avec le nouveau débit et AFR.
Normalement nous devons modifier également la carte KVB qui est en fait la correspondance de la KRKTE pour l'affichage de la consomation en direct sur l'ordinateur de bord, mais ça perso je m'en balek.

La KRKTE est en quelque sorte un coefficient qui sera utilisé en permanence dans la stratégie de calcul d'injection.
L'avantage de cette carte est que si l'on modifie sa valeur sans modifier les injecteurs, le calcule sera faussé ce qui très pratique pour créer un FlexFuel ou E85 éthanols.
Car les constantes de ce calculateur on été étudiées pour être utilées avec un carburant super sans plomb et non éthanol.
Vous devez toutefois attendre une certaine addaptation en plusieurs passes est avec le même utilisateur du véhicule suivant le style de conduite. 
IL EST PRIMODIAL de contrôler le cycle d'ouverture des injecteurs (duty cycle) avec une limite d'à peut près 85% d'ouverture par cycle. 

Je vais tâcher de faire évoluer le logiciel, c'est pour cela que j'ai choisi Google Sheet, car il sera en permanence disponible et à jour car je travaille directement dessus.

Merci de me fair part de vos remarque et erreur de ma par dans l'onglet "Issue" prevue à cet effet dans GitHub.

Voici ce que j'ai compris déjà
https://www.youtube.com/watch?v=G04ME9IdV2k&t=96s


