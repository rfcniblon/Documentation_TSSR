# Documentation_TSSR

Documentation TSSR à été crée en markdown et affiché avec [mkdocs](https://www.mkdocs.org/) qui est un générateur de site static,nous utilisons aussi, . [pandoc](https://pandoc.org) pour nous géneré toutes les procédure qui sont au format .md nous genère au format .pdf

### Accés à la [doc de mkdocs](https://www.mkdocs.org/getting-started/)

## Installation mkdocs sur windows : 
- installer python3  (google)
- puis dans une invite cmd
    - vous tapez:   mkdir Aide  (cela va créer un repertorie nommer Aide)
    - puis tapez: cd Aide (pour être dans le repertoire)
    - tapez: pip install mkdocs   (installation de mkdocs)
    - tapez: cd Memo  (pour être dans le repertoire Memo)
    - et enfin tapez: mkdocs serve  (pour lancer le serveur)
            dans les lignes qui vont apparaitrent l'adresse ip du serveur sera affiché  (ici 127.0.0.1:8000)
 ## Installation mkdocs sur Linux :
- installer python3  
    - vous tapez: sudo apt install python3-pip
- puis dans une invite cmd
    - vous tapez:   mkdir Aide  (cela va créer un repertorie nommer Aide)
    - puis tapez: cd Aide (pour être dans le repertoire)
    - tapez: pip install mkdocs
    - tapez: sudo-apt install mkdocs   (installation de mkdocs)
    - tapez: cd Memo  (pour être dans le repertoire Memo)
    - et enfin tapez: mkdocs serve  (pour lancer le serveur)
            dans les lignes qui vont apparaitrent l'adresse ip du serveur sera affiché  (ici 127.0.0.1:8000)
      
            INFO    -  Building documentation...
             INFO    -  Cleaning site directory
             [I 160402 15:50:43 server:271] Serving on http://127.0.0.1:8000
             [I 160402 15:50:43 handlers:58] Start watching changes
             [I 160402 15:50:43 handlers:60] Start detecting changes

# Installation Pandoc sur Windows 10, vous pouvez suivre ces étapes :
    - Rendez-vous sur le site officiel de Pandoc à l'adresse suivante : https://pandoc.org/.
        - Dans la section "Download", recherchez la version appropriée pour Windows et téléchargez le fichier d'installation correspondant (par exemple, pandoc-X.X.X-windows-x86_64.msi, où "X.X.X" représente le numéro de version).
        - Une fois le téléchargement terminé, exécutez le fichier d'installation téléchargé.
        - Suivez les instructions de l'assistant d'installation pour installer Pandoc sur votre système Windows.
        - Après l'installation, vous devriez pouvoir utiliser Pandoc en exécutant des commandes depuis l'invite de commandes ou PowerShell.

# Installer Pandoc sur Ubuntu, vous pouvez suivre ces étapes :
        - Ouvrez un terminal sur votre système Ubuntu.
        - Utilisez le gestionnaire de paquets APT pour installer Pandoc en exécutant la commande suivante :

bash
Copy code
sudo apt-get update
sudo apt-get install pandoc
Saisissez votre mot de passe administrateur lorsque vous y êtes invité.

        - Attendez que l'installation soit terminée. Une fois le processus terminé, Pandoc sera installé sur votre système Ubuntu.

        - Vous pouvez vérifier si Pandoc est correctement installé en exécutant la commande suivante dans le terminal :

bash
Copy code
pandoc --version
Cela affichera la version de Pandoc installée sur votre système, ce qui confirmera que l'installation a été réussie.

        -Notez que les étapes ci-dessus sont des instructions générales et peuvent varier légèrement en fonction de votre système et de la version de Pandoc que vous téléchargez. Assurez-vous de consulter la documentation officielle de Pandoc pour obtenir des informations spécifiques à votre configuration.

  Structure:
  - la documentation est structuré comme l'image ci-dessous
 
        C:.
        |_______docs
                |-----css
                |-----images
                      |-----procèdures
                            |-----vmware
                            |-----windows
                |-----pages
                |-----procèdures
    
             répertoires :
                css     => en test pour injecter du css
                images =>  toutes les images seront dans le repertoire
                pages =>  toutes les pages de la documentation seront ici
                procedures => toutes les procédures seront ici
