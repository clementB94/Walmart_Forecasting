# Prédiction des ventes chez Walmart 

Le problème considéré ici est bâti à partir d'une compétition Kaggle, https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting
où il s'agissait de prévoir les ventes dans les différents départements des 45 magasins Walmart des Etats-Unis. 
Le problème a été simplifié ici en regroupant les ventes des différents départements pour ne s'intéresser qu'aux ventes globales des magasins, et supprimant les données relatives aux campagnes publicitaires, en modifiant quelques données. 

L'objectif sera donc de prédire les ventes des différents magasins, à partir d'un historique sur 3 années comprenant :

- fichier data.csv
    - 'store':  numéro du magasin
    - 'date' : date (semaine considérée)
    - 'Weekly Sales' : ventes de la semaine (en \$)
    - 'Temperature' : température (en ° Kelvins)
    - 'Fuel_Price' : prix du carburant (en \$)
    - 'CPI' : [Consumer Price Index](https://www.bls.gov/cpi/)
    - 'Unemployment' : taux de chomage
    - 'IsHoliday' : période de vacances (Vrai/faux)

- fichier stores.csv
    - 'store' : numéro du magasin
    - 'Type' : type de magasin
    - 'Size' : surface
