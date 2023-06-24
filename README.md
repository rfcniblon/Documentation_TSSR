# Documentation_TSSR

Documentation TSSR à été crée en markdown et affiché avec [mkdocs](https://www.mkdocs.org/) qui est un générateur de site static.

### Accés à la [doc de mkdocs](https://www.mkdocs.org/getting-started/)

## Installation sur windows : 
- installer python3  (google)
- puis dans une invite cmd
    - vous tapez:   mkdir Aide  (cela va créer un repertorie nommer Aide)
    - puis tapez: cd Aide (pour être dans le repertoire)
    - tapez: pip install mkdocs   (installation de mkdocs)
    - tapez: cd Memo  (pour être dans le repertoire Memo)
    - et enfin tapez: mkdocs serve  (pour lancer le serveur)
            dans les lignes qui vont apparaitrent l'adresse ip du serveur sera affiché  (ici 127.0.0.1:8000)
 ## Installation depuis Linux :
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
