MBDS projet REST MIMOUNA Amira

-Intoduction
lien du projet: http://cours.tokidev.fr/mbds/wsrest/tp.pdf
Le projet Rest mes a disposition  deux entit�s:les Libraries & les books qui les composent.
Suite au cours nous avons du apprendre a manipuler les hasmany et hasone pour permettre 
la bonne lisibilit� des entit� et de leur composition.

-SPECIFICATION
Suite au sp�cification demand�:
Il ya bien deux classe Library & Book ce qui repond a la norme
Il ya bien des lien de d�pendance comme convenue un livre peut avoir une
biblioth�que et une biblioth�que peut avoir plusieurs livre.

-Les M�thode GET/POST/PUT/DELETE
On bien �t� impl�ment� pour les livres
On bien �t� impl�ment� pour les biblioth�ques
On bien �t� impl�ment� pour les et les livres dans les Biblioth�ques

-Concernant l'URLMapping
Ici pour plus de lisibilit� j'ai cree un controleur par entit�  avec celui des ressources li�es
"/API/library" Api
"/API/libraries" "Api"
"/API/book" controller: "Book"
"/API/books" controller: "Book"
"/API/library/$id/book" controller: "Rslier"
"/API/library/$id/books" controller: "Rslier"
