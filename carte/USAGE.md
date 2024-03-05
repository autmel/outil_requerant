# Carte des requérants

  Votre avocat vous demandera une carte avec une visualisation des requérants par rapport au site que vous visez.
  
## Démo en ligne

 Démo: [https://autmel.github.io/outil_requerant/carte/carteRequerant.html](https://autmel.github.io/outil_requerant/carte/carteRequerant.html)
   
   
## Lancer la démo en local

  - pré-requis : Python 3 doit être installé sur le poste
  - sous windows: lancer depuis le répertoire carte server.cmd
  - sous linux: lancer depuis le répertoire carte server.sh
  - depuis notre navigateur tapper l'adresse: [http://localhost:8000](http://localhost:8000/carteRequerant.html)

## Faire votre carte

 - le code source peut être télécharger depuis le bouton vert 'code' ou cloner via github
 - Ligne 82: il faudra placer les coordonées GPS du site que vous voulez viser.
 
        // TODO : placer ici Latitude et Longitude du site visé
        var locateWorkPlace = L.latLng(50.6244477,3.1053216);

 - Dans le fichier LibreOffice requerants.ods, il vous faudra placer les numéros d'ordre de votre action et y placer les coordonées GPS corespondantes
 - Puis faire un copier de la colonne E 
 - Et le coller dans le fichier ./data/claimants.json
 - Pour finir, faire une cature d'écran dde votre navigateur web pour l'ajouter au dossier de l'avocat
 