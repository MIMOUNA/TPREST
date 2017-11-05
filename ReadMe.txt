MBDS projet REST MIMOUNA Amira

-Intoduction
lien du projet: http://cours.tokidev.fr/mbds/wsrest/tp.pdf
Le projet Rest mes a disposition  deux entités:les Libraries & les books qui les composent.
Suite au cours nous avons du apprendre a manipuler les hasmany et hasone pour permettre 
la bonne lisibilité des entité et de leur composition.

-SPECIFICATION
Suite au spécification demandé:
Il ya bien deux classe Library & Book ce qui repond a la norme
Il ya bien des lien de dépendance comme convenue un livre peut avoir une
bibliothèque et une bibliothèque peut avoir plusieurs livre.

-Les Méthode GET/POST/PUT/DELETE
On bien été implémenté pour les livres
On bien été implémenté pour les bibliothèques
On bien été implémenté pour les et les livres dans les Bibliothèques

-Concernant l'URLMapping
Ici pour plus de lisibilité j'ai cree un controleur par entité  avec celui des ressources liées
"/API/library" Api
"/API/libraries" "Api"
"/API/book" controller: "Book"
"/API/books" controller: "Book"
"/API/library/$id/book" controller: "Rslier"
"/API/library/$id/books" controller: "Rslier"
