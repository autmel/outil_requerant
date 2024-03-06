# Carte des requérants

  Votre avocat vous demandera peut-être une carte avec la visualisation des requérants par rapport au site que vous visez.
  
## Démo en ligne

 Démo: [https://autmel.github.io/outil_requerant/carte/carteRequerant.html](https://autmel.github.io/outil_requerant/carte/carteRequerant.html)
   
   
## Lancer la démo en local

  - pré-requis : Python 3 doit être installé sur le poste
  - sous windows: lancer depuis le répertoire ./carte **server.cmd**
  - sous linux: lancer depuis le répertoire ./carte **server.sh**
  - depuis notre navigateur saisir l'adresse: [http://localhost:8000](http://localhost:8000/carteRequerant.html)

## Faire votre carte

 - le code source peut être téléchargé depuis le bouton vert 'code' ou cloner via github
 - Ligne 82 du fichier carteRequerant.html: il faudra placer les coordonées GPS du site que vous voulez viser.
 
        // TODO : placer ici Latitude et Longitude du site visé
        var locateWorkPlace = L.latLng(50.6244477,3.1053216);

 - Dans le fichier LibreOffice requerants.ods, il vous faudra placer les numéros d'ordre de votre action et y placer les coordonées GPS correspondantes
 - Puis faire un copier de la colonne C 
 - Et le coller dans le fichier ./data/claimants-new.json et le renommer en claimants.json
 - Puis il faut effacer la dernière virgule de la dernière ligne
 - Pour finir, faire une capture d'écran de votre navigateur web pour l'ajouter au dossier pour l'avocat
 