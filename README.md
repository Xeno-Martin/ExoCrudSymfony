# ExoCrudSymfony
Un CRUD est un système de manipulation des données de la base : ça signifie Create, Read, Update, Delete(Créer, Lire, Mettre à jour, Supprimer).
1- Initialiser un projet avec Symfony ou bien reprendre un projet déjà existant
2- Pour commencer on va taper la commande  php bin/console make:crud dans notre terminal 
3-Définir l'Entity pour laquelle nous souhaiton créer le CRUD (pour ma part il s'agit de mon entité Habitat pour laquelle je n'ai pas encore fait de formulaire)
4- A la suite de cette commande , on peut remarquer que Symfony nous à créer tous les fichiers nécessaires : 
 created: src/Controller/HabitatController.php
 created: src/Form/HabitatType.php
 created: templates/habitat/_delete_form.html.twig
 created: templates/habitat/_form.html.twig
 created: templates/habitat/edit.html.twig
 created: templates/habitat/index.html.twig
 created: templates/habitat/new.html.twig
 created: templates/habitat/show.html.twig
5- Saviez vous que Symfony était magique? Si vous aviez encore des doutes , je pense désormais que vous êtes convaincu(e)s!
En effet , tous ces fichiers crées reprennent toutes les propriétés de votre entités (ainsi que de la table associée dans la base de données) et vous crée les formulaires avec toutes les fonctionnalités qui vont bien (edit , show,delete , create).
Voilà maintenant que vous connaissez un des énièmes prodiges de Symfony , vous pourrez aisément faire vos formulaires en 4s chrono (5s pour ceux qui ,comme moi ,ont un terminal mou du genou).


