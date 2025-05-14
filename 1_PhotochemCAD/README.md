# Stratégie

Récupération de la base de donnée ouverte PuotochemCAD avec un script python automatisé (scrap-photochemcac.ipynb).

1. Collecte des données : difficultés à automatiser en raison de l'arborescence du site web, obligeant à créer un .csv transitoire contenant le lien des molécules visées : photocompounds_urls.csv
2. Récupération des informations désirées depuis la liste d'URLs : photocompounds_database_crude.csv
3. Analyse succinte et nettoyage des données récupérées (clean-csv.ipynb) : photocompounds_database.csv
