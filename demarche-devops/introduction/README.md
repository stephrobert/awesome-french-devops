# Qu'est-ce que le Devops

DevOps est une combinaison de philosophies culturelles, de pratiques et d'outils
qui améliorent la capacité d'une entreprise à livrer des applications et des
services à un rythme élevé.

Il permet de faire évoluer et d’optimiser les produits plus rapidement que les
entreprises utilisant des processus traditionnels de développement de logiciels
et de gestion de l’infrastructure.

# La méthode CALMS

CALMS, acronyme de « culture, automation, lean, measurement et sharing »
(culture, automatisation, rationalisation, mesure et partage), est une
infrastructure conceptuelle favorisant l'intégration des groupes, des fonctions
et des systèmes de développement et d'exploitation au sein d'une organisation.

## [C]ulture

Pour qu'un projet aboutisse, nous devons partager la même vision, les mêmes
objectifs et le même vocabulaire. Il faudra donc veiller à ce que tout le monde
soit formé.

## [A]utomatisation

On va alors automatiser pour libérer les employés des tâches répétitives, de
réduire les erreurs et optimiser les processus.

DevOps pousse à identifier et automatiser les taches chronophages sans valeur
ajoutée pour que chacun puisse se concentrer sur ce qui en ajoute réellement.

## [L]ean : Se concentrer sur ce qui donne de la valeur à notre produit

L’amélioration continue est encouragée par des retours entre chaque membre de
l’équipe, ce qui permet d’anticiper, au moment du développement, de potentiels
risques d’exploitation ou de déstabilisation du système d’information.

La rationalisation implique la réduction des excès : par exemple, il faut
limiter minimum le nombre et la durée des réunions, la taille des équipes et le
nombre d'outils susceptibles de fournir les résultats attendus.

## [M]easurement : A-t-on atteint l'objectif ?

Sans la capacité à obtenir des informations sur l’atteinte des objectifs, il est
difficile d’évaluer les performances et de mettre en place les plans d’action
pour s’améliorer. Donc en premier lieu, il est indispensable de mettre en place
des indicateurs pertinents.

**Exemple de KPI** :

* **Mean-time to recovery** (MTTR): temps moyen pour réparer, exprime la moyenne
   des temps de tâches de réparation. Il est calculé en additionnant les temps
   actifs de maintenance ainsi que les temps annexes de maintenance, le tout
   divisé par le nombre d'interventions
* **Feature Usage** : il est primordial de mesurer si un composant est utilisé
   par les utilisateurs. En agilité, nous parlons de la construction d'un MVP
   (Minimum viable product), c'est-à-dire le fait de se concentrer uniquement
   sur les fonctionnalités à plus forte valeur ajoutée.
* **Time To Market** (TTM) : il s'agit du temps qui sépare la décision de
   conception (l'idée) à sa mise en production. L'objectif est de mesurer par
   exemple l'efficacité de la méthodologie projet ou de la collaboration entre
   équipes. Les méthodes agiles comme SCRUM ont été créées pour réduire le TTM
   en optimisant la productivité, la créativité et la flexibilité.
* **Satisfaction utilisateur** : l'idée est d'obtenir un continous feedback de
   la part des utilisateurs. Il faut comprendre les usages, mais également
   comprendre si l'utilisateur est content d'une fonctionnalité et du produit.
   C'est la donnée qui à mon sens est la plus importante, car elle représente la
   finalité du travail effectué.
* **Time to deploy** : Mesurer le temps pour déployer un applicatif, ou pour
   mettre en production la modification d'une seule ligne de code, est pertinent
   pour mesurer l'efficacité du pipeline de delivery, à partir du commit dans
   le gestionnaire de sources à son déploiement en production.
* Et bien d'autres...

## [S]haring Travailler ensemble pour atteindre nos objectifs

Traditionnellement, les équipes de développement et des opérations travaillent
de manière cloisonnée, et ont chacun des intérêts pouvant être qualifiés de
contradictoires. Les opérations ont pour responsabilité de garantir la stabilité
et la performance des applications. L’équipe de développement, elle, a pour
objectif de développer puis mettre en production régulièrement de nouvelles
fonctionnalités. Or, des mises en production régulières font peser un risque sur
la stabilité d’une application.

C’est pour cette raison que se développe la démarche DevOps. Elle vise à faire
travailler ensemble ces équipes en bonne intelligence collective, et dans la
même optique : améliorer le produit.

# Les Objectifs du DevOps

## Fiabilité

Assurons la qualité des mises à jour d'applications et des changements
d'infrastructure afin de livrer en toute confiance nos produits à un rythme
accéléré tout en continuant de proposer une expérience positive aux utilisateurs
finaux. Il faut généraliser l'utilisation des pratiques comme l'intégration
continue et la livraison continue pour nous assurer que chaque changement est
fonctionnel et sûr. Nous devons utiliser les systèmes de supervision et de
journalisation pour rester informé sur les performances en temps réel.

## Sécurité

Avançons rapidement tout en gardant le contrôle et en préservant la conformité.
On peut adopter un modèle DevOps sans sacrifier la sécurité, en utilisant des
politiques de conformité automatisées, des contrôles plus rigoureux et des
techniques de gestion de la configuration. Par exemple, avec l'infrastructure as
code et la security as code , nous pouvons définir et suivre la conformité à
n'importe quelle échelle.

## Évolutivité

L'automatisation et la cohérence nous aident à gérer les systèmes complexes ou
changeants de manière efficace et moins risquée. Par exemple, l'infrastructure
as code peut nous aider à gérer nos environnements de développement, de test et
de production de façon répétitive et plus efficace.

## Livraison rapide

Augmentons le rythme et la fréquence des publications de manière à innover et à
optimiser nos produits plus rapidement. Plus vite, nous publions de nouvelles
fonctionnalités et corrigeons des bogues, plus vite, nous pouvons répondre aux
besoins de nos clients et gagner en compétitivité. L’intégration continue et le
déploiement continu sont des pratiques qui automatisent le processus de
publication de logiciel, du codage au déploiement.
