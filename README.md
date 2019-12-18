# Fouille-de-donnees
## Partie Exécution :
pour ouvire le fichier 'Projet Fouille de Données.IPYNB' vous devez disposer de l'application web jupyter notebook (disponible en l'occurrence sur le navigateur Anaconda )

## Partie DataSet :
-	 Data sete représente des données d'un accéléromètre portable monté sur la poitrine.  
-	 Fréquence d'échantillonnage de l’accéléromètre : 52 Hz.
-	 Les données de l'accéléromètre ne sont pas étalonnées
-	 Nombre de participants : 15
-	 Nombre d’activités : 7.
-	 Format des données : CSV.
-	 Les données sont séparées par participant( 1 fichier par participant).
-	 Chaque fichier contient les informations suivantes : 
nombre séquentiel, accélération x, accélération y, accélération z, classe (activités)
-	 Dans la colonnes classe Les activités sont annotées par des chiffres :
1:Working at Computer,2:Standing Up, Walking and Going up\down stairs, 3:Standing, 4:Walking, 5:Going Up\Down Stairs, 6:Walking and Talking with Someone, 7: Talking while Standing
-  Dans chaque fichier csv, il y a 5 colonnes :  
  1- La 1ère est juste un nombre séquentiel  
  2- La 2ème, 3ème, et 4ème contiennent les données de l’accéléromètre sur l’axe de x, y et z respectivement (Remarque : ne pas    confondre les attributs x et y de l’accéléromètre avec les notations utilisés par la suite du tableau des variables explicatives ‘X’ et à expliquer ‘y’).  
  3- La ligne faisant référence au nom des colonnes ne figure pas dans les Csv.  
 
N.B: le dossier 'ds' doit figurer dans le méme répertoire que le fichier jupiter 'Projet Fouille de Données.IPYNB'
