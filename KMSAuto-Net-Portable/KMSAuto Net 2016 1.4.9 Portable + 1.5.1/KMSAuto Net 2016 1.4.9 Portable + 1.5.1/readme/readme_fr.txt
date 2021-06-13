
                        KMSAuto Net 2016 Portable par Ratiborus,
                                       MSFree Inc.

				Systèmes requis: 
                          —————————————————————————————————
Editions VL : Windows Vista, 7, Windows 8, 8.1, 10, Serveur 2008, 2008 R2, 2012,
2012 R2, Office 2010/2013/2016.

	  		             Description:
                          —————————————————————————————————
KMSAuto Net - Activateur automatique KMS pour les systèmes d'exploitation Windows
éditions VL: Vista, 7, 8, 8.1, 10, Serveur 2008, 2008 R2, 2012, 2012 R2, 2016 et les éditions 
Office 2010, 2013, 2016.

Additionnellement, le programme active :
	Windows 8.1 Single Language;
	Windows 8.1 Core;
	Windows 8.1 Core N;
	Windows 8.1 Pro WMC;
	Windows Embedded 8.1 Industry Pro;
	Windows Serveur 2012 R2 Standard;
	Windows Serveur 2012 R2 Datacenter.
Il est basé sur le service KMS Serveur de mikmik38 (MDL).

  
        	                   Utilisation du programme :
                          —————————————————————————————————
Lancer KMSAutoNet.exe en tant qu'Administrateur et utiliser l'interface. Si vous avez besoin de 
fonctionnalités supplémentaires, entrer dans le Mode Professionnel. Le bouton On/Off du Mode 
Professionnel est placé dans l'onglet "A propos de".
Le moyen le plus simple pour utiliser le programme est de choisir le mode automatique. Il est 
juste nécessaire de cliquer sur le bouton pour lancer l'activation et d'accepter de créer un tâche
planifiée pour la réactivation en cliquant sur le bouton.

Astuce : D'abord vous devez activer Windows et Office en mode manuel, et seulement lorsque vous 
êtes sûr que l'activation est effective, vous pouvez créer une tâche planifiée pour réactiver les
produits tous les 25 jours. 
Si le système ne peut pas être activé en Mode Professionnel, allez 
dans "Utilitaires" et paramétrez manuellement la clé GVLK correspondant à la version de Windows, 
lancez à nouveau l'activation.

	                    Informations supplémentaires :
                          —————————————————————————————————

Pour activer Windows 8.1 l'adaptateur réseau TAP doit être installé directement
et utilise l'adresse IP 10.3.0.2-254 ou utilise un pilote spécial. Toutes ces fonctionnalités
sont intégrées dans le programme.
Pour l'activation via un LAN, l'interface TAP ne peut pas être utilisée pour
effectuer l'activation à partir de l'adresse d'un ordinateur dans le réseau.
Si vous modifiez les paramètres du programme et qu'il devient instable ou inopérationnel - cochez 
"Réinitialiser le programme." Tous les paramètres seront remis à leurs valeurs par défaut.


	            Paramètres supplémentaires du programme (commutateurs):
                          —————————————————————————————————
/win=act	- Lance le programme en mode silencieux, active Windows
		  et quitte le programme.
/off=act	- Lance le programme en mode silencieux, active Office
		  et quitte le programme.
/log=yes	- Lance le programme en mode silencieux, créer un fichier journal ActStatus.log
		  et quitte le programme.
/kmsset=yes	- Lance le programme en mode silencieux, installe KMS-Service et quitte le 
		  programme. Uniquement pour KMS-Service, sans TAP, WinDivert, Hook.
/kmsdel=yes	- Lance le programme en mode silencieux, enlève KMS-Service et quitte le programme.
/key=yes	- Lance le programme en mode silencieux, installe la clé Windows et quitte le 
		  programme.
/task=yes	- Lance le programme en mode silencieux, créer un tâche planifiée pour l'activation
		  de Windows et
   	          Office tous les 25 jours et quitte le programme.
/taskrun=yes	- Lance le programme en mode silencieux, lance la tâche planifiée pour l'activation
		  de Windows et Office et quitte le programme.
/convert=	- Lance le programme en mode silencieux, prépare la conversion de la version de 
   	          Windows et quitte le programme.
			  Valeurs clés possibles: win81pro, win81ent, win81, win81sl, win81wmc
			  Après l'utilisation de cette fonction, vous devez redémarrer l'ordinateur.
/sound=yes	- Active les sons.
/sound=no	- Désactive les sons.
		  
                          —————————————————————————————————
L'activation sera effectuée avec les paramètres définis dans l'onglet KMS-Service.


                          —————————————————————————————————
Lorsque vous tranférez le programme vers un autre ordinateur, vous devez réinitialiser le Mode Auto.
L'activation devrait être en automatique, mais ce mode peut ne pas être optimal pour votre nouvel 
ordinateur. 
Pour réinitialiser le mode auto à l'état initial vous devez basculer vers un autre 
mode et selectionner auto une nouvelle fois. Alors tout est réinitialisé à l'état initial.

	              A propos de l'activation avec le programme intégré				
                          —————————————————————————————————
Le programme peut effectuer l'activation de différentes façons par l'émulation d'un serveur KMS 
intégré. Pourquoi en existe t-il plusieurs ?: Le moyen standard pour se connecter au serveur 
d'activation au travers d'un hôte local (127.0.0.2-254) a été bloqué sous Windows 8.1. 
Ces méthodes ont pour but de "leurrer" le système, de telle façon qu'il "pense" que le serveur 
KMS n'est pas sur votre ordinateur, mais quelque part sur le réseau.
				  
						  
	               Les modes de fonctionnement du programme
                          —————————————————————————————————
Auto	 - Le programme tente de trouver la façon qui convient le mieux pour activer le système.
           Tous les moyens pour activer le système ou Office sont lancés, et celui qui correspond 
 	   le mieux sera conservé.
           Pour réinitialiser le mode initial, vous pouvez basculer vers un autre mode et 
	   sélectionner Auto. Ce mode est celui utilisé par défaut.	
Hook     - Méthode basée sur la substitution du fichier système original.
           La nouvelle version de cette méthode fonctionne sans remplacer physiquement le fichier.
WinDivert- Un pilote est installé dans le système au moment de l'activation et il a pour fonction 
           d'émuler, en tâche de fond, une connexion distante avec le serveur KMS.	  
NoAuto   - Dans ce mode il n'y a pas d'automatisation, il n'est pas nécessaire de paramétrer ce 
	   mode de fonctionnement. Ce mode est dédié aux personnes qui savent mieux que moi, quand,
	   comment ou même la façon dont ils souhaitent utiliser ce mode ou pas. :)	
TAP      - Le système est un périphérique virtuel. L'activation TAP est effectuée au travers de ce 
	   périphérique virtuel. Le programme inclus deux pilotes pour l'adaptateur TAP. Si vous 
	   en avez déjà un d'installé, le programme utilisera l'autre pilote pour l'activation, en 
	   laissant intact celui déjà installé.		   
* Nom des modes d'activation dans l'onglet Système - En cliquant sur les liens il est possible de 
  modifier certains paramètres.

				Les options KMSSS.exe
                          —————————————————————————————————
Paramètres en ligne de commande :
  -Port <Valeur du port> - Port KMS. Plage de 1 à 65535
         -PWin <PID> - Windows PID
         -PO14 <PID> - Office 2010 PID
         -PO15 <PID> - Office 2013 PID
    -AI <Intervalle> - Intervalle d'activation. Plage de 15 à 43200 minutes
    -RI <Intervalle> - Intervalle de renouvellement. Plage de 15 à 43200 minutes
              -Debug - Detailed info.
                -Log - Active le fichier journal.
		 -IP - Affiche les adresses IP des ordinateurs clients.         
        -Hwid <HWID> - Valeur de hachage du hardware de la machine.
		   
                          —————————————————————————————————
Le programme nécessite .NET Framework 4.5
Pour que le programme fonctionne correctement, il est nécessaire d'ajouter le fichier KMSSS.exe 
dans les exclusions de votre anti-virus!. 
Ou de désactiver votre anti-virus au moment de l'activation.

Quelque fois le service KMS n'est pas installé correctement selon différentes raisons.
Vous devez alors lancer 2 à 3 fois "Supprimer le service KMS" et redémarrer l'ordinateur.
Lors de l'utilisation du programme il est conseillé de cocher l'option "sauvegarde des paramètres 
dans le dossier programme". Dans ce cas, le fichier de configuration sera stocké dans le dossier 
du programme et non dans C:\Utilisateurs\Nom_Utilisateur\AppData\Local\MSfree Inc.

                          —————————————————————————————————
Les précédente versions de KMS Log Analyzer.xlsm sont incompatibles avec KMS Server Service v1.1.7
Pour la sauvegarde, les anciens enregistrements devront être transférés dans KMS Log Analyzer par 
copier-coller.

                              "Je ne suis pas activé !!!"
                          —————————————————————————————————
Vous disposez peut-ętre d'un produit qui n'est pas une version VL, non destiné ŕ l'activation par
le service KMS, (Windows 7 Intégral n'est pas activé), ou votre antivirus bloque l'activation. 
Faire ce qui suit: sur l'onglet "Systčme", cliquez sur l'icône bleue "Service KMS" dans la fenętre
qui apparaît, retirez la coche. Puis ajouter un dossier dans les exceptions de votre antivirus.
 

                          —————————————————————————————————
Remerciements, à mikmik38, sans son travail ce programme n'aurait pas pu être conçu, à Hotbird64, 
pour son client KMS, à Evgeny972 et les personnes du forum.ru-board.com, pour l'assitance et les 
tests des multiples versions du programme.
                                                             

																 
Journal des modifications :
v1.4.9
-Added Keys for Windows Server 2016 Essentials.
-KMS Server Service v2.0.3.

v1.4.8
 -Added Keys for Windows Server 2016.

v1.4.7
 -New KMS-Service.

v1.4.6
 -Added Keys for Windows 10 and Office 2016.

v1.4.5
 -Fixed minor bugs.

v1.4.4
 -Small changes in program code.

v1.4.3
 -Small changes in program code.

v1.4.2
 -Changes in program for compatibility with antivirus software.

v1.4.0
 -Added: Conversion from Office 2016 Mondo.

v1.3.9
 -Conversion from Office 2016 Word, Excel, Access,
  OneNote, OutLook, PowerPoint, Publisher RETAIL to VL.

v1.3.8
 -Corrigé: Image des boutons lorsque la police d'affichage est augmentée ŕ 125%. 
 -Ajout "Affichez la date d'expiration de la licence (180 jours 0 heures 0 minutes)". 
 -Ajout dans "Autres utilitaires" restaurer les fichiers systčme ŕ partir du disque avec 
  la distribution de votre    version de Windows.
 

v1.3.7
 -Fixed: Encoding readme_ru.txt.
 -Added readme.txt in the Bulgarian language.
 -Utility to save activation MSActBackUp v1.0.8.


v1.3.6
 -Mise à jour du programme ProduKey v1.70 vers v1.80.
 -Corrigé: Paramétrage des clés Office 2016.
 -Corrigé: La tâche dans le planificateur démarre tous les 10 jours.

v1.3.5
 -Mise à jour de ProduKey v1.66 vers v1.70.
 -Nouveau pilote TAP pour supporter Windows 10. Un adresse IP aléatoire est utilisée quand l'activation échoue 
  et la boite de contrôle est effacée.
 -Recompilation du service KMS. Les antivirus ne le détecteront comme une menace/faux positif.
 -Inclus l'utilitaire MSActBackUp.
 -Ajout des clés pour Windows 10 et Office 2016.
 -Conversion de Office 2016 RETAIL en VL.
 -Si Office n'est pas installé, le bouton "Activer Office" est désactiver.
 -Dans l'onglet "A propos de" il y a un lien hypertexte vers mes programmes.
 -Ajout du programme "Afficher ou cacher les mises à jour" pour Windows 10

v1.3.4
-Modifications dans le programme pour assurer la compatibilité avec des logiciels antivirus.

v1.3.3
 -Lors d'une tentative d'activation de Office 2013 RETAIL, le programme convertit le canal de 
licence de Office 2013 OfficeProPlus, VisioPro, ProjectPro en client KMS sur Windows 7, 8, 8.1, 10.

v1.3.2
 -Modifications dans l'interface, compatibilité avec Windows Technical Preview.
 -Disponibilité de l'interface en français, remerciements à Coleo.
 
v1.3.1.b4
 -Ajout d'un script de heos(ru-board.com).
  Ce script recherche les mises à jour installées et obsolètes de Office 2010/2013 et permet de 
  les supprimer.

v1.3.1.b3
 -Ajout de la fonction qui permet de basculer entre les différentes langues d'affichage .
 
v1.3.1.b2
 -Correction d'un bogue lors de la création d'une tâche planifiée en ligne de commande.

v1.3.1.b1
 -Ajout du support pour l'activation de Windows Technical Preview, Windows 10.

v1.3.0
 -Ajout du support pour activer les éditions OEM : "Windows 8.1 Single Language avec Bing",
  "Windows 8.1 avec Bing" et "Windows 8.1 Pro pour Education"
 
v1.2.8
 -Le programme ProduKey a été mis à jour de la version v1.65 à la version v1.66.
 -Remplacement de SppPatcher dans la méthode Hook SECO Injector.
 -Suppression d'une erreur qui affiche "Intervalle d'activation" dans ES, VI, UA.
 
v1.2.7
 -KMS Log Analizer.xlsm est intégré afin de visualiser le journal dans le programme d'activation.
 -L'ordinateur devrait avoir une application d'installér pour visualiser les fichiers .xlms(MS Excel).
 -Adaptation du programme pour s'adapter au nouveau format de fichier journal effectué par Bort_Nick,
  forum.ru-board.com.
 -Nouveau Service KMS Server(KMSSS.exe) v1.1.7.
 -Expansion de la liste des systèmes afin de convertir les éditions.
 
v1.2.6.1
 -Modification de la façon dont le bouton "Information programme" fonctionne dans l'onglet "A propos de".
 -Correction du dysfontionnement du bouton "Obtenir ePID et Hwid KMS-Service".
 
v1.2.6
 -Correction d'un problème lors de l'installation de la clé après l'exécution de la commande "slmgr.vbs /upk".
 -Afin d'éviter leur détection par un antivirus, les fichiers pilotes sont protégés par un mot de passe. 
  Cependant, il est impératif d'ajouter les dossiers suivants dans les exclusions de votre antivirus:
  %SYSTEMDRIVE%\ProgramData\KMSAuto\*.* 
  %SYSTEMDRIVE%\ProgramData\KMSAutoS\*.* 
  %TEMP%\KMSAuto\*.*
  %TEMP%\PDK\*.*
  
v1.2.5
 -Lorsque l'activation échoue un message est affiché et une nouvelle tentative est effectuée pour paramétrer 
  une GVLK en force.
 -Ajout d'une option pour désactiver le planificateur de tâches qui contrôle les actions de l'utilisateur.
 
v1.2.4.1
 -Correction d'un bogue lors de la création d'une tâche planifiée en ligne de commande.

v1.2.4
 -L'activation en mode Auto démarre avec la méthode Windivert.
 -Dans la méthode TAP l'adaptateur TAP adapter n'est pas réinstallé.
 
v1.2.3
 -Les fonctions d'activation sont optimisées pour Windows et Office.
 -Correction de bogues mineurs.
 -Modification de l'onglet "Utilitaires". Ajout de "KMS Client par Hotbird64"
 -Nouveau KMSSS.exe supportant l'installation de Hwid KMS-Server.

v1.2.2
 -Correction de la date et de l'heure affichés en format hexadécimal dans le fichier journal. 
 
v1.2.1
 -Ajout de l'utilisation de ShowHideControls miXOnIN. Pour convertir les éditions. 
 -En mode Professionnel, dans l'onglet avancé, le bouton "Convertir Office RETAIL en VL". 
  fonctionne sous Windows 8-8.1, mais pas sous Windows 7!.
 -Nouveau KMSSS.exe supportant l'installation de Hwid KMS-Server.
  
v1.2.0
 -Modification de l'onglet "Paramètres".
 
v1.1.9.b1
 -Mise à jour du programme ProduKey de la version v1.62 vers la version v1.65
 -Ajout du choix des intervalles d'activation de 10 et 20 jours.
 -Installation de la clé GVLK dans l'onglet "Utilitaires", fonctionne sous slmgr.vbs.
 -Modification de la fonction de paramétrage des clés pour "Produit Non Supporté" (rapport WMI OS).
 -Ajout du programme KMS Log Analyzer, afin de visualiser et conserver plus facilement les informations 
  du fichier journal de KMS-Service. 
  L'ordinateur doit avoir une application installée pour gérer ces fichiers .xlsm (MS Excel). Pas encore prêt!

v1.1.7 ÷ v1.1.8
 -Quelques modifications dans l'interface. Ajout d'un lien vers une vidéo.
 -En mode "Auto" le programme recherche une solution avec une adresse IP correcte.
 -Correction d'un bogue relatif à l'impossibilité de supprimer les fichiers "Injector by deagles".
  Le programme peut se figer avec le message "Installation Hook, Injector by deagles"
 -Les fonctions d'activation ont été optimisées pour Windows et Office.
 - Le bouton "Réinitialisation du système non valide" a été ajouté dans l'onglet "Utilitaires".
  Lire attentivement le message lors de son affichage lorsque vous cliquez sur le bouton !

v1.1.6
 -Ajout de la possibilité de réinitialiser le programme aux valeurs par défaut.
 -Nouveaux containers pour les modules. Le dépaquetages des modules et des pilotes est plus rapide.
 -Le planificateur de tâches créé les tâches sous le nom d' Administrateur.
 -La suppression des adresses de KMS Server fonctionne correctement.
 -Correction des bogues mineurs.
  *** Bonne Année 2014 ! ***

v1.1.4
 -Les paramètres du programme peuvent être sauvegardés dans un dossier contenant le programme.
 -Tous les modules du programme peuvent fonctionner à partir de ProgramData ou du dossier contenant le programme.
 -Coorection de bogues mineurs.

v1.1.2.b8
 -Le programme ProduKey est intégré dans le fichier exécutable.

v1.1.2.b7
 -Correction d'un bogue pour accéder au dossier.

v1.1.2.b6
 -Correction d'un bogue dans le planificateur.

v1.1.2.b4
 -En mode Auto, vous pouvez désactiver n'importe quelle méthode d'activation.
 
v1.1.2.b3 
 -La méthode Hook utilise un injecteur SECO modifié. Fonctionne lors de l'activation, lors des intervalles de 
  renouvèlement.  
  et paramètre son propre ePID.
 v1.1.2b2
 -Option pour se connecter à KMS server où le mode Hook fonctione sans remplacer les fichiers.
 -Ajout d'un option dans le planificateur de tâches afin de créer une tâche dans ProgramData\KMSAutoS.

v1.1.1
 -Ajout d'une méthode d'activation avec subsitution temporaire des fichiers 8.1.

v1.0.9.1
 -Elimination d'un bogue avec la non suppression du service TunMirror.

v1.0.9
 -Le programme nécessite .NET Framework 4.5 suite à la demande des utilisateurs.
 -La boite de dialogue pour modifier la clé produit n'apparait qu'une seule fois par session avec le programme.
 -Lorsqu'une tâche planifiée s'exécute, le KMS-Service n'est plus supprimé du système,
  s'il a été installé la première fois.
 -Nouvelle option NoAuto ajoutée pour désactiver le chargement automatique de KMS-Service pendant l'activation.
  En conséquence si NoAuto est appliqué tout est en NoAuto.
 -En mode Auto lorsque le commutateur de configuration est ajouté, l'analyse du système débutera toujours à la 
  position de départ, 
  et non à partir de celle stockée précédemment.
  Ceci est pratique si le programme est exécuté sur des ordinateurs différents.
 -Avant activation l'édition du système est définie et s'il s'agit de 8.1 alors la façon classique
  de l'activation de l'hôte local est exclue.
 -Ajout d'un second type d'adaptateur TAP pour résoudre un conflit avec un TAP VPN déjà installé.
 -WinDivert v1.1 appliqué, pour éviter les BSOD sur des systèmes x86.
 -Suppression des erreurs lorsque le chemin du fichier contient un "&" (et commercial).
 
v1.0.8
 -Ajout d'un paramètre pour enlever le pilote WinDivert. Evitant ainsi un crash possible du
  système, générant un BSOD, il peut être validé sur On.
  Par défaut, la suppression est effectuée après réamorçage.
 -Ajout de la possibilité de lancer le programme avec des commutateurs en ligne de commande.
 
v1.0.8.b5
 -Le programme combine trois façons pour se connecter au serveur KMS, toujours utiliser le mode automatique.

v1.0.7
 -Nouveau Service KMS Server (KMSSS.exe). Ajout d'une fonction pour afficher l'adresse IP 
  du client dans le fichier journal. Plus d'infos dans KMSSS.txt
  
v1.0.6
 -Nouveau Service KMS Server (KMSSS.exe). Plus d'infos dans KMSSS.txt
 -Modification de l'interface.
 
v1.0.5
 -Fichier journal incluant les informations relatives à la version du système d'exploitation du client.
 -Correction d'un problème avec la définition d'un dossier Sysnative.
 
v1.0.4
 -Nouveaux KMSSS.exe, Service KMS Server.
 -Le journal KMS Service est visible dans le dossier spécifié.
 -Corrections de bogues mineurs :)
 
v1.0.3
 -Application du KMS-Service modifié. Permet l'utilisation de votre propre ePID de chaque produit. 
  Incluant CSVLK à partir de la clé actuelle.
 -Modification de l'installation et du retrait de TunMirror.
 -Modification de l'installation et du retrait de l'interface TAP.
 -Ajout de la prise en charge de l'activation des versions Core, Embedded Industry, Single Language, etc...

v1.0.2
 -Modification des paramètres de l'interface TAP.
 -Nouvelle fonction pour la Sauvegarde/Restauration de l'activation.
 -Modification de l'interface.
 -Ajout de la possibilité de créer un tâche planifiée pour l'activation.

v1.0.1
 -Ajout des clés GVLK au Serveur R2.
 -Modification de l'interface.

v1.0.0
 -Première version.




