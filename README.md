[TP1 admin linux :]{.ul}

# Table des matières {#table-des-matières .TOC-Heading}

[Exercice1 : Installation du serveur :
1](#exercice1-installation-du-serveur)

[Exercice 2 : Prise en main de l'interpréteur de commandes
1](#exercice-2-prise-en-main-de-linterpréteur-de-commandes)

[Exercice 3. Découverte de l'éditeur de texte nano :
9](#exercice-3.-découverte-de-léditeur-de-texte-nano)

[Exercice 4 : Personnalisation du shell :
10](#exercice-4-personnalisation-du-shell)

# Exercice1 : Installation du serveur :

Cette partie a été faite préalablement.

# Exercice 2 : Prise en main de l'interpréteur de commandes

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image1.png){width="6.3in"
height="1.5944444444444446in"}

1)  **which** permet d'afficher le chemin d'accès d'un fichier.

2)  Pour rechercher un terme dans le manuel il faut utiliser la commande
    **/pattern**

3)  Nous pouvons quitter le manuel avec la lettre **q**

4)  Cette section explique et décrit les jeux et petits programmes
    disponible sur le système Linux.

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image2.png){width="4.385038276465441in"
height="1.3888888888888888in"}

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image3.png){width="5.453987314085739in"
height="1.9767093175853019in"}

1)  La commande **cd** permet de changer de dossier (cd = change
    directory).![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image4.png){width="3.7505238407699037in"
    height="0.531324365704287in"}

2)  Un *chemin relatif* est a priori relatif au répertoire courant où se
    trouve
    l\'utilisateur.![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image5.png){width="2.7816382327209097in"
    height="0.41672462817147854in"}

3)  ![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image6.png){width="3.7921959755030623in"
    height="0.5938331146106737in"}

4)  ![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image7.png){width="2.979582239720035in"
    height="0.5209055118110236in"}

5)  Avec cette commande on retourne au fichier racine. Normalement la
    commande doit être refusé si l'utilisateur n'est pas en
    administrateur.

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image8.png){width="2.917073490813648in"
height="0.3646347331583552in"}

6)  On ne peut accéder au fichier racine seulement en mode
    administrateur (**sudo** permet de spécifier que la commande
    suivante est exécuté avec les privilèges administrateur.)

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image9.png){width="5.435582895888014in"
height="2.2444553805774277in"}

8)  Ici on ne peut pas car le fichier n'est pas sur notre dossier
    personnel directement, il est dans le
    Dossier1.![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image10.png){width="5.552858705161855in"
    height="0.41672462817147854in"}

9)  Le dossier1 s'est bien supprimé (avec le fichier1.txt qui était
    dedans).

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image11.png){width="3.969304461942257in"
height="0.44797900262467194in"}

10) Le dossier ne peut pas être supprimé car il y a des éléments dans ce
    dernier.![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image12.png){width="4.198502843394576in"
    height="0.4792333770778653in"}

11) Avec la commande ***rm --r Dossier2 ***

![Une image contenant texte Description générée
automatiquement](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image13.png){width="3.1211701662292213in"
height="0.3874475065616798in"}

> ![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image14.png){width="6.3in"
> height="2.609722222222222in"}

1)  La commande **date** permet d'afficher la date ainsi que l'heure
    exacte sur le
    terminal.![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image15.png){width="2.8858191163604547in"
    height="0.44797900262467194in"}

2)  Les fichiers avec un point devant sont des fichiers cachés.

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image16.png){width="6.3in"
height="0.4479166666666667in"}

3)  Grâce à la commande **which** on localise la commande ls.

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image17.png){width="3.17752624671916in"
height="0.3854702537182852in"}

4)  Voici le résultat de la commande
    **ll **:![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image18.png){width="5.6570395888014in"
    height="2.2086417322834646in"}

L'entrée manuelle pour cette commande est **ls --l** .

La commande alias nous retourne le résultat suivant pour la commande
ll :

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image19.png){width="3.0316732283464565in"
height="1.375191382327209in"}

5)  La commande permettant d'afficher le contenu du dossier /bin est la
    suivante :![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image20.png){width="3.323380358705162in"
    height="0.34379811898512685in"}

6)  Cette commande permet d'afficher le contenu du dossier précédent.

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image21.png){width="2.96916447944007in"
height="0.40630686789151355in"}

7)  La commande qui donne le chemin complet du dossier en cours est
    **pwd** :![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image22.png){width="2.8337292213473315in"
    height="0.39588910761154855in"}

8)  La commande a écrit bip dans un fichier nommé bop : ![Une image
    contenant table Description générée
    automatiquement](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image23.png){width="1.2218482064741907in"
    height="0.4166666666666667in"}

Si on exécute la commande une 2^ème^ fois, le contenu sera écrasé.

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image24.png){width="3.7505238407699037in"
height="0.552159886264217in"}

9)  Cette commande permet d'écrire à la ligne suivante dans le fichier
    bop
    ![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image25.png){width="2.8337292213473315in"
    height="1.3960279965004374in"}

L'utilité de cette commande est que l'on peut écrire à la suite du
contenu d'un fichier sans écraser le contenu qui y était déjà.

10) **Sleep** est une commande Unix qui est une enveloppe de l\'appel
    système sleep qui suspend l\'exécution du processus pendant un
    intervalle de temps passé en paramètre.

> ![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image26.png){width="4.677736220472441in"
> height="0.5104877515310586in"}
>
> Pendant 10 secondes, toto est affiché sur le terminal sans que l'on
> puisse faire quelque chose.
>
> ![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image27.png){width="6.3in"
> height="3.647222222222222in"}

11) **File** est une commande UNIX qui permet essentiellement de
    déterminer le type MIME d\'un fichier en explorant son contenu. File
    affiche éventuellement d\'autres informations comme les dimensions
    pour une image ou les codecs.

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image28.png){width="2.6450721784776903in"
height="0.3510433070866142in"}
![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image29.png){width="2.5628576115485564in"
height="0.34379811898512685in"}

12) Si on modifier le fichier référence, le lien suit les modifications.
    ![Une image contenant texte Description générée
    automatiquement](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image30.png){width="2.398772965879265in"
    height="0.48641732283464567in"}

En cas de suppression du fichier référence le lien fonctionne
encore.![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image31.png){width="4.0005588363954505in"
height="0.729268372703412in"}

13) Pour faire le lien symbolique nous avons utilisé la commande
    suivante : **ln -s lien_phy lien_sym** le lien se fait correctement.

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image32.png){width="2.97619094488189in"
height="0.6547626859142607in"}

Le lien ne se fait plus si le fichier référence est supprimé :

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image33.png){width="3.058980752405949in"
height="0.5292661854768154in"}

14) **Ctrl s** permet d'arrêter le défilement et **ctrl q** permet de
    reprendre.

15) Pour afficher les 5 premières lignes il faut utiliser la commande
    **head -n 5 /var/log/syslog**
    ![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image34.png){width="6.3in"
    height="0.9111111111111111in"}

Pour les 15 dernières lignes nous avons utilisé la commande **tail -n 15
/var/log/syslog**

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image35.png){width="6.3in"
height="1.6201388888888888in"}

Pour afficher seulement le contenu de la ligne 10 à 20, nous avons
utilisé cette commande : **head -20 /var/log/syslog \| tail +10**

16) La commande **dmesg** nous permet de scruter le monde caché des
    processus de démarrage Linux, ici avec un affichage réduit ( **\|
    less**).

17) Voici le contenu du fichier /etc/passwd :

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image36.png){width="3.9522090988626424in"
height="3.025583989501312in"}

Il contient les détails des utilisateurs. Chaque ligne représente en
fait un utilisateur sur notre système. D\'après la sortie ci-dessus, il
est très clair que le /etc/passwd fichier suit un modèle très
spécifique.

Chaque ligne d\'utilisateur est subdivisée en sept sections ou champs
séparés par le côlon personnage (:) comme ci-dessous.

![etc fichier passwd sous
Linux](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image37.png){width="4.779429133858268in"
height="1.9208333333333334in"}

18) Pp

19) La commande qui nous donne le nombre d'utilisateurs ayant un compte
    sur cette machine est la suivant : **wc -l
    /etc/passwd**![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image38.png){width="4.021394356955381in"
    height="0.3854702537182852in"}

20) PP

21) Pour rechercher un fichier avec un nom spécifique, il est
    intéressant d'utiliser la commande *find* :

**find / -name « passwd »**

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image39.png){width="3.888888888888889in"
height="2.5336712598425195in"}

> ![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image40.png){width="6.3in"
> height="1.426388888888889in"}

22) pp

23) pp

24) La commande **locate** permet d'indiquer le chemin d'un fichier avec
    des caractéristiques particulières. Pour chercher l'emplacement du
    fichier history.log nous allons utiliser la commande locate :

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image41.png){width="4.052648731408574in"
height="0.3854702537182852in"}

25) Rien ne se passe car nous sommes déjà dans le bon dossier où est
    situé le fichier créé.

# Exercice 3. Découverte de l'éditeur de texte nano :

[Tableau des raccourcies :]{.ul}

![Une image contenant texte Description générée
automatiquement](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image42.png){width="6.3in"
height="2.4347222222222222in"}

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image43.png){width="6.3in"
height="1.2208333333333334in"}

1)  Pour copier un fichier il faut utiliser la commande
    **cp** :![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image44.png){width="5.9070745844269466in"
    height="0.8230314960629921in"}

2)  

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image45.png){width="6.3in"
height="1.8069444444444445in"}

Pour remplacer kernel par le mot noyau, nous devons faire **ctrl \\**
pour spécifier remplacer le mot kernel par noyau et de tous les
remplacer.

![Une image contenant texte Description générée
automatiquement](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image46.png){width="6.3in"
height="2.1805555555555554in"}

> 3\) On va les couper puis les coller à la fin du fichier, pour cela on
> sélectionne le texte voulu avec Alt A : ![Une image contenant texte
> Description générée
> automatiquement](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image47.png){width="6.3in"
> height="1.675in"}

Puis nous allons à la dernière ligne où nous allons coller la
sélection :

![Une image contenant texte, batterie Description générée
automatiquement](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image48.png){width="6.3in"
height="1.1861111111111111in"}

4\) Pour annuler notre action précédente, nous allons utiliser le
raccourcie **Alt U**.

5\) Pour enregistrer sous nano il suffis de faire **Ctrl O** et Oui.

# Exercice 4 : Personnalisation du shell :

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image49.png){width="6.3in"
height="0.44375in"}

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image50.png){width="6.3in"
height="0.6777777777777778in"}

1)  Ce fichier ce trouve dans /etc/skel , de plus le fichier rechercher
    est un fichier caché il faut donc utiliser ll pour le voire. Nous
    avons ensuite fait un copie du fichier pour avoir un backup.![Une
    image contenant texte Description générée
    automatiquement](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image51.png){width="5.229896106736658in"
    height="3.1462718722659666in"}

2)  ![Une image contenant texte, horloge Description générée
    automatiquement](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image52.png){width="4.760416666666667in"
    height="0.65625in"}

![Une image contenant table Description générée
automatiquement](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image53.png){width="6.3in"
height="2.3159722222222223in"}

![Une image contenant texte Description générée
automatiquement](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image54.png){width="6.3in"
height="1.2381944444444444in"}

3)  ![Une image contenant texte, horloge Description générée
    automatiquement](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image55.png){width="3.875in"
    height="0.6979166666666666in"}

Grace à la commande source .bashrc , les modifications de couleurs du
bash ce sont bien activés.

4)  Dans le fichier config nous avons indiqué ceci :

![](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image56.png){width="6.3in"
height="0.15555555555555556in"}

Une fois terminé, on enregistre puis on actualise le .bashrc.

![Une image contenant texte, horloge Description générée
automatiquement](vertopal_c0044276fbb049fd9cd3f8ea0714ba49/media/image57.png){width="4.989583333333333in"
height="0.6666666666666666in"}

[.bashrc generator: create your .bashrc PS1 with a drag and drop
interface](https://bashrcgenerator.com/)
