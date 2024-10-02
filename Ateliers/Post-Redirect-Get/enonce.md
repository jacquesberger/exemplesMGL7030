POST-Redirect-GET
=================

Le patron de conception POST-Redirect-GET est élémentaire dans la gestion des
formulaires web. Il permet notamment d'éviter la création de doublons si on
actualise la page après la soumission du formulaire.

Objectifs
---------

* Créer une application Flask.
* Créer un formulaire HTML.
* Effectuer une validation backend.
* Gérer le succès avec POST-Redirect-GET.

Exercices
---------

1. Créez une application Flask avec un formulaire sur la page d'accueil. Le
   formulaire doit contenir 2 champs et un bouton de soumission. Les 2 champs
   sont :
   * un nom complet;
   * un courriel.

2. Ajoutez une validation backend pour vérifier que les deux champs sont bien
   remplis. Ajoutez également une validation pour vérifier que le nom complet
   contient au moin 5 caractères, incluant un espace. Finalement, valider que le
   courriel possède un @. Affichez les messages d'erreurs dans la page s'il y a
   des erreurs. Attention à ce que les valeurs des champs demeurent présents
   dans le formulaire.

3. En cas de succès lors de la validation backend, faites une redirection vers
   une page de confirmation pour compléter le patron POST-Redirect-GET.

_Rédigé par Jacques Berger._
