# Comment est née la démarche DevOps

Contrairement à des normes, comme l'ITIL qui ont été commandé par des
organisations ou des gouvernements, le mouvement DevOps est lui issu d'une
succession de conférences, les **DevOpsDays**, qui se sont déroulées à partir de
2008. C'est pour cette raison qu'il n'existe pas de définition écrite ou de
manifeste comme pour les méthodes agiles. Parmi les noms les plus reconnus, nous
retrouvons :

* Andrew Shafer
* Pierre Debois qui est à l'origine du nom DevOps,
* Jez Humble auteur du livre [*Accelerate*](https://amzn.to/3zR5cyb)
* Gene Kim auteur du livre [*The Phoenix Project*](https://amzn.to/3UcOotc)

Le constat qu'ils tiraient est que le cloisonnement des équipes de développement
et des opérations était contre-productive. Les développeurs écrivaient le code
de l'application et les administrateurs système se chargeaient de son
intégration et de son déploiement et tout cela en ne communiquant que par des
demandes de services, *request* en anglais, et de changements, *change* en
anglais. Cela conduisait à des incompréhensions, des allers-retours à répétition
et a beaucoup d'incidents.

## Un peu d'histoire

### Les méthodes traditionnelles

Il faut se souvenir qu'à cette époque les méthodes de gestion de projet agiles,
dites itératives sont venues remplacer les méthodes traditionnelles, dites
linéaires : cascade ou cycle en V.

Une méthode dite "traditionnelle" est composée d'étapes qui se succèdent les
unes après les autre. Par exemple pour le modèle en Cascade :

* Recueil des exigences du client.
* Constitution du cahier des charges fonctionnel par analyse des exigences du
  client et ajout de celles demandées par des normes.
* Conception du produit afin qu'il soit fabriqué en série et remplisse les
  exigences du cahier des charges
* Pre-Production : le produit est assemblé et déployé
* Validation : le produit est testé afin de voir s'il répond aux exigences
* Production : le produit est installé et utilisé.

![Méthode en cascade](/media/cascade.png)

Chacune de ces étapes ne peut commencer sans que la précédente ne soit terminée,
conduisant à un *effet tunnel*. Il peut se passer de très longues périodes entre
l'expression des besoins du client et la mise en service du produit. Lors de la
livraison, on constate souvent des déphasages entre les besoins initiaux
exprimés par le client et le produit livré. De plus, certaines fonctionnalités
se révèlent finalement inutiles alors que d'autres, découvertes en cours de
route, pourraient donner plus de valeur au produit.

### Les méthodes Agiles

Les méthodologies agiles (Scrum, RAD, Extreme Progamming...) sont différentes au
sens où le développement d'un produit devient incrémentale et inclut le client
tout au long de ce processus. Ces méthodes sont en fait des adaptations des
méthodes de production de l'industrie, appelé Lean, au développement de
logiciels.

### Le Lean

Le Lean, maigre en anglais, est une méthode de gestion de production mise au
point au Japon par le Système de Production Toyota. Cette méthode est axée sur
la recherche de la performance que ce soit en termes de productivité, de
qualité, de délais, et de coûts. L'amélioration continue a pour objectif
d'augmenter la valeur globale du produit en cherchant à éliminer les
gaspillages, *muda* en japonais, qui sont toutes les choses qui finissent à la
poubelle comme les déplacements inutiles, les pertes de temps, les pannes, des
fonctionnalités que le client ne veut pas.

Le Lean a été décliné à d'autres domaines :

* à la gestion des organisations avec le *Lean management* qui a ajouté à la
  chasse aux gaspillages deux autres démons :
  * les excès : *muri* en japonais comme la surcharge de travail engendrée par
    des processus non adaptés ou contre productive.
  * la variabilité ou l'irrégularité, *mura* en japonais, en termes de temps de
    production et de qualité produite.
* à l'industrie informatique avec le *Lean IT*
* au développement Logiciel avec *Lean software development*
* aux services *Lean Services*
* ...

#### Le manifest Agile

Le Manifeste pour le développement agile de logiciels est un texte rédigé aux
États-Unis en 2001 par dix-sept experts du développement logiciels. Ils
estimaient que le taux important d'échecs des projets de développements
logiciels était dû à la lourdeur des méthodes traditionnelles inspirées du génie
civil et s'appuyant sur un cycle de développement en cascade. Chacun d'entre
eux avait déjà mis au point et expérimenté de nouvelles méthodes plus légères.
Les méthodes agiles ne sont donc pas apparues avec le manifeste agile. Cependant
celui-ci a défini leurs dénominateurs communs et consacré le terme d'« agile »
pour les référencer. Les valeurs et les principes du manifeste agile sont
défendus et promus par l'Agile Alliance créée par certains des signataires.8

En s'appuyant sur leur expérience combinée du développement logiciel, les
dix-sept signataires du manifeste ont proclamé qu'ils attachaient de
l'importance « aux individus et leurs interactions plutôt qu'aux processus et
aux outils », « à un logiciel fonctionnel plutôt qu’à une documentation
exhaustive », « à la collaboration avec les clients plutôt qu'à la négociation
contractuelle » et « à l’adaptation au changement plutôt qu'à l'exécution d’un
plan ». Cela signifie que les éléments à gauche du mot « plutôt » dans chaque
citation sont réputés avoir plus de valeur que ceux à droite, bien qu'il y ait
aussi de la valeur dans ces derniers. Ces quatre citations sont appelées les
quatre « valeurs » du manifeste agile.

##### Les quatres valeurs du Manifest Agile

Les 4 valeurs du manifest Agile :

* Les individus et leurs interactions plus que les processus et les outils
* Des logiciels opérationnels plus qu’une documentation exhaustive
* La collaboration avec les clients plus que la négociation contractuelle
* L’adaptation au changement plus que le suivi d’un plan

Les quatre valeurs du manifeste agile ont été déclinées en douze principes afin
d'aider opérationnellement les équipes qui souhaitaient les suivre.

##### Les 12 principes Agile

1. Notre plus haute priorité est de satisfaire le client en livrant rapidement et
régulièrement des fonctionnalités à grande valeur ajoutée.
2. Accueillez positivement les changements de besoins, même tard dans le projet.
Les processus Agiles exploitent le changement pour donner un avantage compétitif
au client.
3. Livrez fréquemment un logiciel opérationnel avec des cycles de quelques semaines
à quelques mois et une préférence pour les plus courts.
4. Les utilisateurs ou leurs représentants et les développeurs doivent travailler
ensemble quotidiennement tout au long du projet.
5. Réalisez les projets avec des personnes motivées. Fournissez-leur
l’environnement et le soutien dont ils ont besoin et faites-leur confiance pour
atteindre les objectifs fixés.
6. La méthode la plus simple et la plus efficace pour transmettre de l’information
à l'équipe de développement et à l’intérieur de celle-ci est le dialogue en face
à face.
7. Un logiciel opérationnel est la principale mesure d’avancement.
8. Les processus Agiles encouragent un rythme de développement soutenable.
Ensemble, les commanditaires, les développeurs et les utilisateurs devraient
être capables de maintenir indéfiniment un rythme constant.
9. Une attention continue à l'excellence technique et à une bonne conception
renforce l’Agilité.
10. La simplicité – c’est-à-dire l’art de minimiser la quantité de travail inutile –
est essentielle.
11. Les meilleures architectures, spécifications et conceptions émergent d'équipes
autoorganisées.
12. À intervalles réguliers, l'équipe réfléchit aux moyens de devenir plus efficace,
puis règle et modifie son comportement en conséquence.


##

Ces méthodes agiles étaient appliquées dans les équipes de développement alors
que les équipes des opérations elles continuaient à travailler en méthode
traditionnelle. Mais pourquoi donc ?

##

## Conclusion

Dans de telles conditions, un changement devenait nécessaire. Ces deux équipes
devaient se rapprocher et travailler avec les mêmes objectifs et les mêmes
méthodes. Ce à partir de ce moment que Pierre Debois a introduit le terme de
DevOps (en 2009). Une contraction de Development et Operations pour symboliser
leur rapprochement nécessaire.


Sources : Wikipedia
