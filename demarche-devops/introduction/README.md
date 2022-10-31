# Qu'est-ce que le Devops

<!-- toc -->

La philosophie DevOps est une combinaison de principes, de pratiques et d'outils
visant à améliorer la capacité d'une entreprise à livrer à un rythme élevé des
applications et des services d'infrastructures.

Ils tirent ses racines des méthodes Agiles et du Lean que nous avons vu dans le
chapitre précédent. Il est important de comprendre tout de suite que le DevOps
n'est pas une méthode, mais plutôt une culture. De même, il ne repose pas sur
l'utilisation d'outil précis, mais plutôt, il les utilise pour atteindre les
objectifs fixés. D'ailleurs quels sont ces objectifs ?

## Les Objectifs du DevOps

Sans directions claires comment définir le chemin à emprunter. Donc les auteurs
ont fixé des objectifs clairs et atteignables. Chacun pouvant les adapter à son
niveau de connaissances et de pratique, mais en cherchant sans cesse à
s'améliorer.

### La vélocité

Plus vite, vous publiez de nouvelles fonctionnalités et corrigez des bogues,
plus vite, vous pourrez répondre aux besoins de vos clients et gagner en
vélocité.

### Fiabilité

Il faut généraliser l'utilisation des pratiques comme l'intégration et le
déploiement continus (nous les verrons plus tard) pour assurer la qualité du
delivery. Il faut aussi généraliser l'utilisation des systèmes de supervision et
de journalisation pour rester informé sur les performances de l'application.

### Sécurité

La sécurité ne doit pas être sacrifiée lors de la mise en pratique du DevOps. Il
faut mettre en place des outils de conformité automatisés pour vérifier que le
code n'embarque pas des secrets et que la configuration d'un équipement ou d'un
middleware ne laisse une faille ouverte. Par contre, si les personnes en charge
de la sécurité imposent des restrictions aux développeurs, elles doivent aussi
fournir des solutions pour ne pas tuer la créativité.

### Évolutivité

Afin de garantir l'évolutivité, nous devons garantir que les environnements de
développement, de tests, de préproduction sont à l'image de ceux de la
production. Par exemple, l'infrastructure as code peut nous aider à gérer ces
environnements de manière efficace.

### La satisfaction du client

C'est l'objectif le plus important. Nous devons répondre à ses besoins et à ses
exigences dans un délai raisonnable.

## Les principes du Devops

Le Devops repose avant tout sur des principes, c'est pour cela que nous parlons
de philosophie ou culture DevOps. Parmi les principes, nous retrouvons ceux
définis en 2010 par Damon Edwards et John Willis avec l'Acronyme CAMS qui a
évolué ensuite vers CALMS.

### Le CALMS

CALMS est l'acronyme de « Culture, Automation, Lean, Measurement and Sharing »
(culture, automatisation, rationalisation, mesure et partage) où toutes les
notions importantes. DevOps ne se limite pas à de l'automatisation comme on
l'entend souvent.

#### [C]ulture

Pour qu'un projet aboutisse, nous devons partager la même vision, les mêmes
objectifs et le même vocabulaire. Il faudra donc veiller à ce que tout le monde
soit formé.

#### [A]utomatisation

On va alors automatiser pour libérer les employés des tâches répétitives sans
valeur ajoutée. Elle permet également de limiter les erreurs (surtout humaine)
et optimiser les processus.

Mais attentions à ne pas construire des usines à gaz, appelé communément appelés
monolithes, où la complexité limitera la créativité, demandera beaucoup de
maintenance et finira inexorablement en échec.

#### [L]ean : Se concentrer sur ce qui donne de la valeur à notre produit

La rationalisation implique la réduction des excès et des gaspillages. Par
exemple en limitant le nombre et la durée des réunions, réduisant la taille des
équipes, en évitant de recourir à des outils inadaptés et onéreux ne couvrant
qu'une partie d'un besoin. Cela passe aussi par l'optimisation de toutes les
tâches pouvant provoquer des goulets d'étranglement ou consommateur de temps CPU
comme l'analyse de code, l'intégration, de tests, de scans de sécurité. Même si
ces tâches sont masquées, car effectuées automatiquement, elles ont un cout. On
parle dans ce cadre de FinOps.

#### [M]easurement : A-t-on atteint l'objectif ?

Pour pouvoir contrôler que des objectifs sont atteints et mettre en place des
plans d'actions pour corriger ou améliorer si besoin, il est nécessaire de
mettre en place des indicateurs pertinents. Parmi ces indicateurs, on retrouve :

* **Time to deploy** : Mesurer le temps pour déployer un applicatif, ou pour
   mettre en production la modification d'une seule ligne de code. On calcule le
  temps passé depuis le commit dans le gestionnaire de sources jusqu'à son
   déploiement.
* **User Satisfaction** : l'idée est d'obtenir un retour continue de la part des
   utilisateurs. Il faut comprendre les usages, mais également comprendre si
   l'utilisateur est content d'une fonctionnalité et du produit. C'est la donnée
   qui à mon sens est la plus importante, car elle représente la finalité du
   travail effectué.
* **Mean-Time To Recovery**: temps moyen pour réparer, exprime la moyenne des
   temps de tâches de réparation. Il est calculé en additionnant les temps
   actifs de maintenance ainsi que les temps annexes de maintenance, le tout
   divisé par le nombre d'interventions.
* Et bien d'autres...

#### [S]haring Travailler ensemble pour atteindre nos objectifs

Il est nécessaire que les personnes composant cette équipe soit transparente et
partage leurs connaissances. Mais aussi entendent les opinions, les remarques,
les difficultés voir les échecs de chacun.

### Pratiquer le CALMS

Il s'agit de garder à l'esprit ces cinq principes, à les cultiver et les
renforcer sans cesse. Ce cadre n'est pas restrictif, mais peut s'adapter aux
particularités de chaque équipe ou entreprise.
