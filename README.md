
# DataViz
Projet Mike/Achille


Graph avec bokeh, la docu est plutot claire : https://docs.bokeh.org/en/latest/docs/first_steps/first_steps_1.html

Graph avec holoviews, la docu est plutôt pas clair : http://holoviews.org/getting_started/index.html


**TODO :**

afficher les deux graph en même temps : 
  - faire une fonction qui affiche l'un ou l'autre en fonction de si on clique sur bouton1 ou bouton2
  - juste les afficher l'un après l'autre (en colonne pck on a un menu pour l'année pour ds)



Faire plus de traitement de donneés (ptete voir une prédiction de la courbe) (on commence à être pas mal là ) 

Améliorer la **visibilité** & les commentaires


**Done :**

[x] récup data et organisation en tableau (data_test)
[x] fonction moy_annee() : réorganise les données et crée un nouveau tableau montrant seulement le prix moyen par année
[x] fonction Ecart_type
[x] fonction forte_évolution
[x] fonction reg_lineaire
[x] organisation des data en un tableau de 3 colonnes (data_tab) : Année, Période(mois), Prix. (Permettra de faire le graph qui propose de choisir quel année vous voulez regarder)
[x] graph montrant l'évolution du prix du gazole depuis 1992 ( fait avec bokeh ). 
  Comprend plusieurs courbes :
  - regréssion linéaire
  - courbes prix par mois
  - courbe prix moyen par an
  - rond rouge montrant une forte évolution.

[x] graph avec menu déroulant permettant de choisir l'année (fait avec HoloViews)



Pour le 1 avril on doit montrer une image de notre graph mais c'est pas la version final. La version final c'est le 8
