# Chapitre : NORMALISATION


# Normalisation

* **La normalisation** ou **standardisation** consiste à fixer des règles sur la structure des données afin de respecter la cohérence des données et d'éviter toute redondance d'information.
* L’objectif principal de la normalisation est de concevoir une **base de données cohérente** .
* Certaines contraintes appelées **« Formes Normales (NF) »** doivent être respectées pour avoir un modèle relationnel normalisé.
* Ces formes normales sont basées sur **des dépendances fonctionnelles (DF).**

![](https://i.imgur.com/sUhYyJf.png)

# Normalisation

La normalisation élimine les redondances, ce qui permet :

* Une diminution de la taille de la base de données sur le disque
* Risque réduit d'incohérence
* Evitez les mises à jour multiples des mêmes données

![](https://i.imgur.com/adI0mFK.png)

# Dépendances fonctionnelles (DF)

* X est en dépendance fonctionnelle de Y si à toute valeur de la propriété Y on ne peut faire correspondre qu'une seule valeur de la propriété X.
* Si nous connaissons la valeur de Y, nous pouvons déduire la valeur unique de Y à partir de X (l'inverse n'est pas vrai)

![](https://i.imgur.com/gAgXuMM.png)

# Dépendances fonctionnelles : exemple

![](https://i.imgur.com/1PNnKvn.png)

* Il y a un FD entre Employee_id et Employee_name
* Si nous connaissons la valeur de « employee_id », nous pouvons identifier la valeur de « employee_name »

### Ces ressources peuvent vous aider

normalisation de base de données

[https://www.guru99.com/database-normalization.html](https://www.guru99.com/database-normalization.html)
