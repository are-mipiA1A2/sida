- membres du groupe: 

AFERIAT Sophia BENBOUAZZA Alex GOVART Alice RAMAHERISON Manon

- Nom du projet : 

La propragation du sida en France

- Présentation :

Nous allons modéliser la propagation du sida en France. Notre modélisation se base sur des données réelles de l'évolution du sida en France de 2004 à 2016.

- Questions importantes autour du sujet :

Comment se transmet le sida ?

Quels sont les paramètres ?

Existe-t-il une limite à la propagation du VIH en France ?

Les résultats sont-ils ceux attendus ?


- Paramètres principaux :

La probabilité d'être contaminé par le VIH lors d'un rapport sexuel non protégé La sexualité La contracepetion Le niveau de vie

- Méthode de validation :

Nous basons notre modélisation sur des chiffres en France : le taux de cas séropositifs découvertes par années en France, nouvelles contamination, la probablité d'être contaminé par le VIH après un rapport sexuel non protégé selon le type de rapport

- 1ères idées de modélisation :

Instaurer le paramètre : probabilité que deux personnes se rencontrent et aient un rapport sexuel 1ère modélisation : On prend deux invidus dans une population, on verifie leur sexe pour determiner les rapports sexuels possibles puis on regarde s'ils ont un rapport sexuel et s'il y a contamination.

28 février 2018:

 - conception du projet, on a trouvé les agents principaux et intéractions. On a choisit de se baser en fonction de chiffres par régions en France
 - debut de programmation: 
 - On a definit une population de 60 milions de chiffres representant la population Francaise regroupé dans une matrice 
 - On suppose 50% de femmes et 50% d'hommes dans notre population, soit 30 milions de femmes et 30 milions d'hommes
 - On suppose 1% de femmes lesbiennes, 7% de gay, 3,5% de bisexuel
 - On crée une liste pour chaque cas : Lesbienne, gay, bisexuel, hommes, femmes
 - On prend au hasard deux inbdividus dans la population

7 Mars 2018:

- On a refait une matrice plus simple:
- on a décider de faire une matrice de tuple qui nous permet de faire correspondre a chaque individus les différents paramètres choisis
- 1e paramètre: Homme (1) ou Femme (0)
- 2e paramètre: Gay/Lesbienne en fonction du genre et du pourcentage choisit
- On a ensuite créé un programme qui simule une rencontre aléatoire entre deux individus
- puis nous avons fait un programme de compatibilité entre les deux individus d'avoir une relation 

14 Mars:

- On s'est réparti les taches:
Manon et Alice ont codé pour rajouter le paramètre des régions sur la matrice définissant un individu
Alex et Sophia ont réalisé des programmes pour le programme final

21 Mars:
.
- On a arrangé le programme final qui ne fonctionnait pas : SIDA

