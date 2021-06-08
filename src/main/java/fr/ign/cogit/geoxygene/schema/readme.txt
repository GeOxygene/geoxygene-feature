Package d�di� aux sch�mas conceptuels.
Le mod�le utilis� est celui des normes ISO. Les interfaces correspondantes sont dans le
package interfacesISO.

Deux impl�mentations sont propos�es : une pour les sch�mas de jeu 
(notion de ApplicationSchema dans ISO) et une pour les sch�mas conceptuels
(notion de feature catalogue dans ISO).

Le package d'utilitaires contient des outils pour la persistence des sch�mas, 
pour leur visualisation sous forme de diagramme (� completer) et pour leur 
exploration dans de simples browser swing (� completer).


Produits et leurs m�tadonn�es.
S'il s'agit d'une base de donn�es vecteur, un produit est notamment d�crit par 
un schema conceptuel de produit.

Un produit est identifi� par un entier (classique et pratique pour l'ac�s par OJB)
et par une chaine de caract�res unique de la forme PRODUIT_EE_RR o� EE est le num�ro 
d'�dition, RR, le num�ro de version de l'�dition. Cet identifiant est aussi utilis� au 
SIEL.