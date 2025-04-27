## Blog d'Emilie Forteroche

## Pour utiliser ce projet : 

- Commencer par décompresser le fichier. 
- Une fois Décompressé, créez un base de données vide appelée : "blog_forteroche" avec le user root password root
  - Importez le fichier _blog_forteroche.sql_ dans votre base de données.
  - commande :
 ```  
  mysql -u root -p blog_forteroche < blog_forteroche.sql
  ```
## Lancez le projet ! 

> Pour vous connecter en mode **admin**, il faut cliquer sur le lien en bas de page. 
>Un formulaire de connexion apparaît, le login est "Emilie" et le mot de passe est "password" (attention aux majuscules)
 

## Modifications et Explications

Suite à un problème de manipulation de git et GitHub, j'ai perdu le fork et je n'ai plus historique des modications.
Mon repository représente la version final du projet. Je vais donc détailler les différentes des changements que j'ai effectué.

1. Gestion du menu principal et ajout du sous lorsque la personne est connectée.
2. Mise à jour de la base de données pour ajout champ nbvues(int) .cela compte le nombre de vues d'un article
3. Mise à jour controleur et modéle. Ajout propriété **qteCommentaires**  
4. Modification controler Article, Ajout requete pour calculer le nombre de commentaire et de vues 
5. Gestion affichage des articles avec tri sur chaque colonne (Colonnes en plus cumuls).
   1. mise en place du framework bootstrap et fonction JS (DataTable)
   2. Il n'y aucune commande de traitements de l'information, simplement de la mise en forme graphique
   3. afin d'optimiser au mieux le site, le chargement et la mise des données se fait par des requêtes AJAX.
   4. Chaque action de tri ou suppression, sont faites par des commandes PHP.
6. Mise en place des liens vers les commentaires associés aux articles.
7. Affichages des commentaires associés à un article sous forme de tableau avec tri sur chaque colonne.
8. Mise en place Fiche modale (Bootstrap) pour confirmation de suppression pour les commentaires.
9. Modification de la confirmation sur la suppression des articles (homogénéité) 
10. Finalisation du projet avec des tests associés.


## Copyright : 

Projet utilisé dans le cadre d'une formation Openclassrooms. 

            