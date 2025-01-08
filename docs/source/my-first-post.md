# DOCUMENTATION TECHNIQUE : PROJET COLIBRI
 
## 1. INTRODUCTION
Colibri est une plateforme web conçue pour simplifier la gestion de l’expédition et de la livraison de colis. Elle s’appuie sur des technologies modernes pour :
- Offrir une interface fluide aux utilisateurs.
- Optimiser les processus logistiques.
Cette documentation détaille les étapes de développement, les outils utilisés, et les fonctionnalités principales.
 
## 2. INSTALLATION DES OUTILS
 
### 2.1. Installation de Visual Studio Code (VSCode)
Visual Studio Code (VSCode) est un éditeur de code léger, puissant et open-source, qui fournit des fonctionnalités avancées pour le développement.
 
#### Étapes d'installation :
1. Téléchargez le fichier d’installation de VSCode depuis le site officiel :  
   [https://code.visualstudio.com/download](https://code.visualstudio.com/download)
2. Choisissez la version compatible avec votre système d’exploitation.
3. Suivez les instructions d’installation fournies sur le site Web.
4. Une fois installé, lancez VSCode pour vous assurer qu’il fonctionne correctement.
 
## INSTALLATION DE MYSQL WORKBENCH
 
MySQL Workbench est un outil visuel unifié destiné aux architectes de bases de données, aux développeurs et aux administrateurs de bases de données. MySQL Workbench fournit des outils de modélisation de données, de développement SQL et d'administration complets pour la configuration du serveur, l'administration des utilisateurs, la sauvegarde et bien plus encore. MySQL Workbench est disponible sur Windows, Linux et macOS.
 
Pour pouvoir visualiser la base de données de votre projet, si vous n'avez pas encore installé MySQL Workbench, cliquez sur le lien ci-dessous :  
[Comment installer MySQL Workbench](https://support.academicsoftware.eu/hc/fr/articles/360007014958-Comment-installer-MySQL-workbench)
 
 
## INSTALLATION DE XAMPP
 
Maintenant que MySQL Workbench est installé sur votre machine, passons à l'installation de Xampp.  
**XAMPP** est une solution complète libre et open source pour la mise en place de serveurs web, contenant :
- Le serveur web Apache.
- Le système de gestion de bases de données MariaDB (un fork maintenu par la communauté MySQL).
- Les interpréteurs pour les langages de script PHP et Perl.
 
C'est cette application qui vous permettra de lancer votre serveur.
 
# PREMIÈRE PRISE EN MAIN
 
## Étape 1 : Cloner le Dépot Git
 
Une fois tous ces outils installés, ouvrez votre dépôt Git et clonez le lien de votre projet :
 
```bash
git clone https://github.com/Coli-s-bri-dev
```
 
 Étape 2 : Frontend
 
1. Lancez votre interface IDE, dans notre cas **VSCode**, et clonez le dépôt suivant :  
   ```bash
   git clone https://github.com/Coli-s-bri-dev/Colibri-react-ts.git
    ```
   
2. Une fois le frontend ouvert, tapez la commande suivante dans votre terminal pour mettre à jour la bibliothèque :
 
  ```bash
npm install
  ```

3.Toujours dans le terminal, tapez la commande suivante pour lancer l'application React :
 
 ```bash
npm start
 ```
 ## Étape 3 : Lancer le Backend
 
Lancez VSCode, puis clonez le dépôt backend :
 
```bash
git clone https://github.com/Coli-s-bri-dev/ColibriBackend.git
```

Exécutez le code source du programme(run).
 
## LANCEMENT DE L'APPLICATION WEB
 
Une fois que vous avez lancé les deux programmes (frontend et backend), l'application Web va s’ouvrir automatiquement dans un navigateur Web de votre choix.
 
- ATTENTION
 
Pour exécuter le programme, vous devez vous assurer d'avoir lancé votre serveur **XAMPP** au préalable.
