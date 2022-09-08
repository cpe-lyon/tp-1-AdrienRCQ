TP1 admin linux :

Exo 2 :

![](/media/image1.png){width="6.3in"
height="1.5944444444444446in"}

1)  which permet d'afficher le chemin d'accès d'un fichier.

2)  /pattern

3)  Avec la lettre q

4)  ![](/media/image2.png){width="4.385889107611549in"
    height="3.2700787401574805in"}

![](/media/image3.png){width="5.453987314085739in"
height="1.9767093175853019in"}

1)  ![](/media/image4.png){width="3.7505238407699037in"
    height="0.531324365704287in"}

2)  ![](/media/image5.png){width="2.7816382327209097in"
    height="0.41672462817147854in"}

3)  ![](/media/image6.png){width="3.7921959755030623in"
    height="0.5938331146106737in"}

4)  ![](/media/image7.png){width="2.979582239720035in"
    height="0.5209055118110236in"}

5)  ![](/media/image8.png){width="2.917073490813648in"
    height="0.3646347331583552in"} Avec cette commande on retourne au
    fichier racine. Normalement la commande doit être refusé si
    l'utilisateur n'est pas en administrateur.

6)  On ne peut accéder au fichier racine seulement en mode
    administrateur (sudo permet de spécifier que la commande suivante
    est exécuté avec les privilèges administrateur.)

![](/media/image9.png){width="5.435582895888014in"
height="2.2444553805774277in"}

7)  Pppppp

8)  ![](/media/image10.png){width="5.552858705161855in"
    height="0.41672462817147854in"} Ici on ne peut pas car le fichier
    n'est pas sur notre dossier personnel directement, il est dans le
    Dossier1.

9)  ![](/media/image11.png){width="3.969304461942257in"
    height="0.44797900262467194in"} Le dossier1 s'est bien supprimé
    (avec le fichier1.txt qui était dedans).

10) ![](/media/image12.png){width="4.198502843394576in"
    height="0.4792333770778653in"}

11) Avec la commande ***rm --r Dossier2***

> ![](/media/image13.png){width="2.9197561242344707in"
> height="0.3624453193350831in"}
>
> ![](/media/image14.png){width="6.3in"
> height="2.609722222222222in"}

1)  ![](/media/image15.png){width="2.8858191163604547in"
    height="0.44797900262467194in"}

2)  ![](/media/image16.png){width="6.3in"
    height="0.4479166666666667in"}

Les fichiers avec un point devant sont des fichiers cachés.

3)  ![](/media/image17.png){width="3.17752624671916in"
    height="0.3854702537182852in"} Grâce à la commande which on localise
    la commande ls.

4)  ![](/media/image18.png){width="5.6570395888014in"
    height="2.2086417322834646in"}

L'entrée manuelle pour cette commande est ls --l .

![](/media/image19.png){width="3.0316732283464565in"
height="1.375191382327209in"}

5)  ![](/media/image20.png){width="3.323380358705162in"
    height="0.34379811898512685in"}

6)  ![](/media/image21.png){width="2.96916447944007in"
    height="0.40630686789151355in"}

Cette commande permet d'afficher le contenu du dossier précédent.

7)  ![](/media/image22.png){width="2.8337292213473315in"
    height="0.39588910761154855in"}

8)  ![](/media/image23.png){width="3.7505238407699037in"
    height="0.552159886264217in"}

La commande a écrit bip dans un fichier nommé bop :
![](/media/image24.png){width="0.9714818460192476in"
height="0.33128827646544184in"}

Si on exécute la commande une 2^ème^ fois, le contenu sera écrasé.

9)  Cette commande permet d'écrire à la ligne dans le fichier bop
    ![](/media/image25.png){width="2.8337292213473315in"
    height="1.3960279965004374in"}

10) Sleep est une commande Unix qui est une enveloppe de l\'appel
    système sleep qui suspend l\'exécution du processus pendant un
    intervalle de temps passé en paramètre.

> ![](/media/image26.png){width="4.677736220472441in"
> height="0.5104877515310586in"}
>
> Pendant 10 secondes, toto est affiché sur le terminal sans que l'on
> puisse faire quelque chose.
>
> ![](/media/image27.png){width="6.3in"
> height="3.647222222222222in"}

11) File est une commande UNIX qui permet essentiellement de déterminer
    le type MIME d\'un fichier en explorant son contenu. File affiche
    éventuellement d\'autres informations comme les dimensions pour une
    image ou les codecs.

![](/media/image28.png){width="2.6450721784776903in"
height="0.3510433070866142in"}
![](/media/image29.png){width="2.5628576115485564in"
height="0.34379811898512685in"}

12) ![](/media/image30.png){width="2.398772965879265in"
    height="0.48641732283464567in"} Si on modifier le fichier référence,
    le lien suit les modifications. En cas de suppression du fichier
    référence le lien fonctionne
    encore.![](/media/image31.png){width="4.0005588363954505in"
    height="0.729268372703412in"}

13) ![](/media/image32.png){width="3.6073622047244096in"
    height="0.7936198600174978in"}![](/media/image33.png){width="3.55257874015748in"
    height="0.6146686351706037in"} Le lien ne se fait plus

14) Ctrl s permet d'arrêter le défilement et ctrl q permet de reprendre.

15) 5 premières
    lignes :![](/media/image34.png){width="6.3in"
    height="0.9111111111111111in"}

Pour les 15 dernières lignes :

![](/media/image35.png){width="6.3in"
height="1.6201388888888888in"}

head -20 /var/log/syslog \| tail +10

16) La commande vous permet de scruter le monde caché des processus de
    démarrage Linux. Avec un affichage réduit.

17) ![](/media/image36.png){width="5.287729658792651in"
    height="4.047981189851269in"}

![](/media/image37.png){width="6.3in"
height="4.338888888888889in"}

18) Pp

19) ![](/media/image38.png){width="4.021394356955381in"
    height="0.3854702537182852in"}

20) PP

21) ![](/media/image39.png){width="5.500767716535433in"
    height="3.5838331146106737in"}

> ![](/media/image40.png){width="6.3in"
> height="1.426388888888889in"}

22) pp

23) pp

24) ![](/media/image41.png){width="4.052648731408574in"
    height="0.3854702537182852in"}

25) Rien ne se passe car nous sommes déjà dans le bon dossier où est
    situé le fichier créé.

> Exercice 3. Découverte de l'éditeur de texte nano/

![](/media/image42.png){width="6.3in"
height="1.2208333333333334in"}

1\)
![](/media/image43.png){width="5.9070745844269466in"
height="0.8230314960629921in"}

2\)
![](/media/image44.png){width="6.3in"
height="1.8625in"}![](/media/image45.png){width="6.3in"
height="4.795833333333333in"}

3\) On va les couper puis les coller à la fin du fichier :

4)pp

5\) pp
