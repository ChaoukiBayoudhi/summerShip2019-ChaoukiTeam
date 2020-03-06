# summerShip2019 : Chaouki's Team


## Sujet: Election Helper

### Présentation

Pour aider les electeurs à faire un bon choix, la societé **Summership** a decidé de proposer une solution logicielle presentant deux parties une première pour l’administrateur et une autre pour les electeurs.


### Contexte de l'application

* **Summership** veut sauvegarder les informations necessaires à propos des candidats comme nom, prénom, date de naissance, une photo, le nom de sa partie, son facebook, son tweeter, ses activités par type (scientifique, politique,  economique, publique, humanitaire et autre).
Chaque activité a un id, une durée et un support (vidéo, photos, liens, texte).
* Pour chaque candidat ajouté ou modifié, on calcule un score selon son CV et surtout ces activités.
Un candidat fait parti d’une « Liste Electorale ».
Un score est aussi calculé pour chaque liste en fonction des scores de ses membres et leur position dans cette liste(Tête de liste, …).


### Besoins


* L'administrateur se charge de tout ce qui est gestion des candidats, calcul des scores, création des charts des scores par candidat, par liste et par avis des electeurs.
* Les electeurs peuvent visualizer la fiche de chaque candidat ainsi que les differents charts, naviguer dans les details de ses activités et introduire un avis sous forme d’une note sur 100.


### Points Requis


* Le *Backend* doit pouvoir servir un Front Web et des applications mobiles.
* Le *Front Web* doit être Responsive (Reactive).


### Stacks techniques


* *Backend* : Java 11, Spring Boot, JPA, PostgreSQL, Spring Security, Spring Batch
* *Front* : Angular 8 (voir les liens ci-dessous pour en prendre une idée)
            
* [Reactive Form Example](https://jasonwatmore.com/post/2019/06/14/angular-8-reactive-forms-validation-example)
* [Angular Material Example](https://www.positronx.io/angular-8-reactive-forms-validation-with-angular-material-8/)
* [Angular Rest-API Example](https://www.positronx.io/angular-8-httpclient-http-tutorial-build-consume-restful-api/)

Best of Luck
