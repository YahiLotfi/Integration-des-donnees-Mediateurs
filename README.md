Le projet se focalise sur l'intégration de données en utilisant SQLite. Le 
processus débute par la conversion de fichiers provenant de différentes sources telles que 
JSON, Excel et CSV en tables SQLite. Ces tables sont ensuite exploitées pour créer des vues 
SQL spécifiques, simplifiant l'accès à des informations ciblées.
La conversion de fichiers JSON, Excel et CSV en tables SQLite est réalisée grâce aux fonctions 
`json_to_sqlite`, `excel_to_sqlite`, et `csv_to_sqlite`. Ces fonctions chargent les données dans 
un DataFrame à l'aide de la bibliothèque pandas, établissent une connexion à la base de données 
SQLite, puis utilisent la fonction `to_sql` de pandas pour créer une table dans cette base de 
données.
Suite à la conversion des fichiers en tables SQLite, le code génère plusieurs vues à partir de ces 
tables. 
La deuxième partie du travail consiste en la création d'une application console. Cette application 
propose à l'utilisateur un menu avec cinq options numérotées de 1 à 5, lui demandant ensuite 
de saisir un nombre. Le code vérifie la validité de cette saisie, invitant l'utilisateur à réessayer 
si elle n'est pas conforme
