# GoFa-apprentissage-traj-en-mode-guidage
                                Installation

RAPID :

Ouvrez Robot Studio.
Connectez-vous au robot.
Allez dans l'onglet "RAPID".
Chargez les trois modules suivants dans le robot :
MainModule.modx
Interruption.modx
EnregistrementJointTarget.modx

WebApp :

Ouvrez "Transfert de fichier" dans l'onglet "Système de commande".
Transférez les fichiers d'application dans le dossier \HOME\WebApps du robot.
Créez un dossier vide nommé "trajectoire".
Création de signaux I/O :
Créez deux signaux "digital output" : ABB_0_DO1 & ABB_0_DO2

                               Fonctionnement

Pour enregistrer les mouvements :

Dans la section "Enregistrement des mouvements", saisissez le nom de la trajectoire à apprendre.
Lancez l'apprentissage de la trajectoire.

Sur le robot :
Appuyez sur le bouton pour activer le mode guidage.
Effectuez la trajectoire.
Une fois la trajectoire souhaitée terminée, appuyez à nouveau sur le bouton.
Dans la section "Exécution des programmes enregistrés" :

Choisissez le programme enregistré à l'étape 1 dans le menu déroulant.
Exécutez la trajectoire enregistrée en cliquant sur le bouton "exécuter le programme".
Option : Si le programme n'apparaît pas, cliquez sur le bouton "rafraîchir".
