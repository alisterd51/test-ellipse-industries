# test-ellipse-industries

## Description

Ce dépôt est une réponse à un test technique pour l'entreprise Ellipse Industries.

L'exercice est composé d'une partie théorique et d'une partie pratique.

## Partie Théorique

1. Qu'est-ce qu'une API ? Donnez un exemple d'utilisation d'une API dans un projet.

    - Une API (Application Programming Interface) est une interface de programmation qui permet à un programme de communiquer avec un autre programme sans avoir connaissance de son fonctionnement interne.
    - Par exemple, dans le projet [crud-nest](https://github.com/alisterd51/crud-nestjs), l'application interroge l'API d'[OpenFoodFact](https://fr.openfoodfacts.org/data) pour récupérer des données qu'elle expose ensuite via une API CRUD.

2. Qu'est-ce qu'un webhook ? Expliquer son fonctionnement et donner un exemple de son utilisation.

    - Un webhook est en quelque sorte l'inverse d'une API : plutôt que d'envoyer une requête à une API dès qu'on en a besoin, on ordonne au serveur de nous envoyer une requête dès que les données sont disponibles.
    - Un exemple bien connu est ifttt qui permet de suivre des événements précis (par exemple : suivre un compte twitter et effectuer une action à chaque tweet)

3. Quelle est la différence entre une base de données relationnelle et une base de données non relationnelle ?

    - la différence est la manière de stocker les données : une base de données relationnelle stocke les données dans des tables tandis qu'une base de données non relationnelle (NoSQL) les stocke au format clé-valeur.
    - l'avantage des bases de données NoSQL (par exemple Redis) est d'être très scalable (permet de gérer la montée en charge et de réduire les coûts)

4. Déjà utilisé Python ? Explique brièvement ton expérience ou tes connaissances concernant le langage

    - Oui, par exemple dans le projet d'école [dslr](https://cdn.intra.42.fr/pdf/pdf/66152/en.subject.pdf), qui est un projet de data-visualization dont l'objectif est d'analyser un ensemble de données à l'aide d'outils d'apprentissage automatique.

5. Déjà utilisé Wordpress ou Odoo ? Explique brièvement ton expérience ou tes connaissances concernant ces outils.

    - Wordpress oui, j'expérimente sur mon site [wordpress.anclarma.fr](https://wordpress.anclarma.fr), cepandent, c'est un site qui me sert uniquement un tester des plugins, mon vrai site est [blog.anclarma.fr](https://blog.anclarma.fr) qui est aussi en développement et est écrit en angular 16.
    - Odoo non, je sais juste qu'il s'agit d'un progiciel de gestion d'entreprise du meme type qu'SAP.
