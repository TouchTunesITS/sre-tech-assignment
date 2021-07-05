(english version follows)

# Test Technique SRE / Spécialiste DevOps

## S’il-vous-plaît veuillez faire parvenir votre solution au contact qui vous a référé à cette page et NE PAS envoyer de Pull Request avec votre réponse sur ce repo.

L’objectif de cette évaluation est d’écrire un script répondant aux trois défis présentés si bas.

Vous pouvez utiliser le langage de programmation de votre choix pour compléter ce test. Sachez cependant que Python est le langage principalement utilisé pour les taches de programmation associées au poste de spécialiste DevOps, son utilisation est donc recommandée.

Votre solution sera évaluée selon les critères de qualité suivants : 
-	Simplicité et clarté des instructions d’exécution
-	Lisibilité du code
-	Fonctionnalité
-	Structure
-	Exactitude des résultats

## Défis 

Produisez un script qui fait appel à l’API d’astéroïde (NeoWs) de la NASA ( https://api.nasa.gov/ ) afin de : 

1)	Obtenir et afficher l’information suivante sur les astéroïdes détectés entre le 31 Octobre 2019 et le 2 Novembre 2019 inclusivement : 
      - `name`
      - `id`
      - `close_approach_date_full`
   
2)	Pour les astéroïdes entre les dates du 10 et 17 Septembre 2020 inclusivement, calculer : 
      - La vélocité, en kilomètre par secondes, de l’astéroïde le plus rapide 
      - La vélocité, en kilomètre par secondes de l’astéroïde le plus lent 
      - La vélocité moyenne, en kilomètre par secondes, de tous les astéroïdes détectés au cours de cette période
      - La vélocité médiane, en kilomètre par secondes, de tous les astéroïdes détectés au cours de cette période

**Note** : Pour cette section, vous devez implémenter les algorithmes de vélocité, moyenne et médiane vous-même, c’est-à-dire que vous ne devez pas utiliser de bibliothèques intégrées ou de fonctions natives pour faire le calcul. Vous pouvez cependant utiliser les fonctions de tris au besoin. 

3)	Trouver les trois astéroïdes les plus récent dont le drapeau `is_potentially_hazardous_asteroid` est vrai.

Vous pouvez utiliser toutes les ressources en ligne dont vous avez besoin. 




# SRE / DevOps Specialist technical skills assignment 

## Please DO NOT send a pull request to this repository with your answer.  Instead send your answer to your contact who sent you here by email.

The objective is to write a script which solves the three challenges described below. You may use any mainstream programming language you like to answer them.

As the DevOps Specialist position will focus mainly on Python for the programming tasks, we would recommend its use but if you feel you can do a better job in a different language please go ahead.

Qualities we will be looking for in the script: 
- Simple and clearly communicated instructions for use 
- Readability of the code 
- Functionality 
- Structure 
- Exact Results

## Challenges

Write a script that uses the NASA Asteroids (NeoWs) API ( https://api.nasa.gov/ ) to:

1. Retrieve and display the following information about asteroids with approach dates between October 31st 2019 and November 2nd 2019 (inclusive): 

   - `name`
   - `id`
   - `close_approach_date_full`

2. For asteroids with approach dates between September 10th 2020 and September 17th 2020 (inclusive) calculate: 

   - The velocity, in kilometers_per_second, of the fastest asteroid for the period.
   - The velocity, in kilometers_per_second, of the slowest asteroid for the period
   - The mean velocity (in kilometers_per_second) of all asteroids in the period.
   - The median velocity (in kilometers_per_second) of all asteroids in the period.

**Note** : For this task, you must implement the algorithms to determine the velocities, means and medians by yourself.  You may use built-in sorting functions but must not use any built in or lib functions to do the calculations.

3. Find the three most recent asteroid approaches where the `is_potentially_hazardous_asteroid` flag is set to true.

You may use any online resource you like.
