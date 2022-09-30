# Awesome French Devops [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<!-- vscode-markdown-toc -->
* 1. [Introduction](#introduction)
* 2. [1. Administration de serveurs](#1.-administration-de-serveurs)
  * 2.1. [1.1. Linux](#1.1.-linux)
    * 2.1.1. [1.1.1. Livres gratuits](#1.1.1.-livres-gratuits)
    * 2.1.2. [1.1.2. Livres](#1.1.2.-livres)
    * 2.1.3. [1.1.3. MOOC](#1.1.3.-mooc)
  * 2.2. [1.2. Windows](#1.2.-windows)
    * 2.2.1. [1.2.1. Livres gratuits](#1.2.1.-livres-gratuits)
    * 2.2.2. [1.2.2. Livres](#1.2.2.-livres)
    * 2.2.3. [1.2.3. MOOC](#1.2.3.-mooc)
* 3. [2. Langages de Programmation](#2.-langages-de-programmation)
  * 3.1. [2.1. Python](#2.1.-python)
    * 3.1.1. [2.1.1. Livres gratuits](#2.1.1.-livres-gratuits)
    * 3.1.2. [2.1.2. Livres](#2.1.2.-livres)
    * 3.1.3. [2.1.3. MOOC](#2.1.3.-mooc)
  * 3.2. [2.2. Golang](#2.2.-golang)
    * 3.2.1. [2.2.1 Livres Gratuits](#2.2.1-livres-gratuits)
    * 3.2.2. [2.2.2 Livres](#2.2.2-livres)
    * 3.2.3. [2.2.3. MOOC](#2.2.3.-mooc)
    * 3.2.4. [2.2.3. Sites](#2.2.3.-sites)
  * 3.3. [2.3. Rust](#2.3.-rust)
  * 3.4. [2.4. Ruby](#2.4.-ruby)
* 4. [3. Réseaux et Sécurité Informatique](#3.-réseaux-et-sécurité-informatique)
  * 4.1. [3.1. Réseaux](#3.1.-réseaux)
    * 4.1.1. [3.1.1. Livres gratuits](#3.1.1.-livres-gratuits)
    * 4.1.2. [3.1.2. Livres](#3.1.2.-livres)
    * 4.1.3. [3.1.3. MOOC](#3.1.3.-mooc)
* 5. [4. Configuration et maintenance de Serveurs](#4.-configuration-et-maintenance-de-serveurs)
  * 5.1. [4.1. Serveurs WEB](#4.1.-serveurs-web)
    * 5.1.1. [4.1.1. Apache](#4.1.1.-apache)
    * 5.1.2. [4.1.2. Nginx](#4.1.2.-nginx)
  * 5.2. [4.2. Serveurs de Cache](#4.2.-serveurs-de-cache)
    * 5.2.1. [4.2.1. Redis](#4.2.1.-redis)
    * 5.2.2. [4.2.2. Memcache](#4.2.2.-memcache)
  * 5.3. [4.3. Base de Données](#4.3.-base-de-données)
    * 5.3.1. [4.3.1. Généralités](#4.3.1.-généralités)
  * 5.4. [4.4. MySQL](#4.4.-mysql)
  * 5.5. [4.5. PostgreSQL](#4.5.-postgresql)
  * 5.6. [4.6. MongoDB](#4.6.-mongodb)
  * 5.7. [4.7. OracleDB](#4.7.-oracledb)
* 6. [5. Infrastructure as Code](#5.-infrastructure-as-code)
  * 6.1. [5.1. Provisionning](#5.1.-provisionning)
    * 6.1.1. [5.1.1. Vagrant](#5.1.1.-vagrant)
    * 6.1.2. [5.1.2. Terraform](#5.1.2.-terraform)
    * 6.1.3. [5.1.3. CloudFormation](#5.1.3.-cloudformation)
    * 6.1.4. [5.1.4. Gestion de Configuration :](#5.1.4.-gestion-de-configuration-:)
    * 6.1.5. [5.1.5. Ansible](#5.1.5.-ansible)
    * 6.1.6. [5.1.6. Puppet](#5.1.6.-puppet)
    * 6.1.7. [5.1.7. Chef](#5.1.7.-chef)
    * 6.1.8. [5.1.8. Salt](#5.1.8.-salt)
* 7. [6. Pipelines de CI/CD :](#6.-pipelines-de-ci/cd-:)
  * 7.1. [6.1. Gitlab-CI/CD](#6.1.-gitlab-ci/cd)
  * 7.2. [6.2. Github Actions](#6.2.-github-actions)
  * 7.3. [6.3. Jenkins](#6.3.-jenkins)
* 8. [7. Conteneurs et Orchestrateurs](#7.-conteneurs-et-orchestrateurs)
  * 8.1. [7.1. Conteneurs Docker :](#7.1.-conteneurs-docker-:)
    * 8.1.1. [7.1.1. Docker](#7.1.1.-docker)
    * 8.1.2. [7.1.2. Docker-compose](#7.1.2.-docker-compose)
  * 8.2. [7.2. Orchestrateurs](#7.2.-orchestrateurs)
    * 8.2.1. [7.2.1. Kubernetes](#7.2.1.-kubernetes)
    * 8.2.2. [7.2.2. Nomad](#7.2.2.-nomad)
* 9. [8. Clouders](#8.-clouders)
  * 9.1. [8.1. AWS](#8.1.-aws)
  * 9.2. [8.2. GCP](#8.2.-gcp)
  * 9.3. [8.3. Azure](#8.3.-azure)
* 10. [9. Surveillance](#9.-surveillance)
  * 10.1. [9.1. Logging :](#9.1.-logging-:)
    * 10.1.1. [9.1.1. Zabbix](#9.1.1.-zabbix)
    * 10.1.2. [9.1.2. Centreon](#9.1.2.-centreon)
    * 10.1.3. [9.1.3. Prometheus](#9.1.3.-prometheus)
    * 10.1.4. [9.1.4. Grafana](#9.1.4.-grafana)
  * 10.2. [9.2. Monitoring :](#9.2.-monitoring-:)
    * 10.2.1. [9.2.1. Splunk](#9.2.1.-splunk)
    * 10.2.2. [9.2.2. ELK](#9.2.2.-elk)
    * 10.2.3. [9.2.3. Datadog](#9.2.3.-datadog)
* 11. [10. Blogs Devops](#10.-blogs-devops)
  * 11.1. [10.1. Blogs Perso](#10.1.-blogs-perso)
  * 11.2. [10.2. Sociétés](#10.2.-sociétés)
* 12. [11. Communautés](#11.-communautés)
* 13. [12. Chaines Youtube](#12.-chaines-youtube)
* 14. [13. Des comptes Twitters](#13.-des-comptes-twitters)
* 15. [Contribuer](#contribuer)
* 16. [Des lignes directrices](#des-lignes-directrices)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

##  1. <a name='introduction'></a>Introduction

**C'est une question qui revient souvent. Comment je démarre si je veux maîtriser
les outils Devops ? Par quoi dois-je commencer ?**

Je parle bien d'outils DevOps et non de la culture elle-même. Si vous êtes
intéressé par ce seul sujet je vous conseille de suivre les liens ci-dessous.

- [Découvrez la méthodologie DevOps sur
  OpenClassRooms](https://openclassrooms.com/fr/courses/6093671-decouvrez-la-methodologie-devops)
- [Mieux comprendre DevOps](https://aws.amazon.com/fr/devops/what-is-devops/)

Par contre, pour **mettre en œuvre avec succès le DevOps** on se doit de
connaître un **certain nombre d'outils**. Pour rappel, **l'approche DevOps** met
l'accent sur **l'automatisation des processus** de **développement de
logiciels** tels que la **construction (build)**, les **tests**, la **mise en
production**, les **mesures** et la **détection d'incidents**, ...

C'est dans ce cadre que vous serez amener à connaître un certain nombre de
ces outils. Je vous propose ce **mind-map** qui représente un peu tous les
outils que vous serez amené à **rencontrer le plus souvent** :

- **en rouge** les plus courants
- **en orange** moins courants
- **en jaune** très peu rencontrés (mais c'est bien de les connaître de nom)

_Si vous débutez il faut suivre l'ordre indiqué par les nombres devant les
grands sujets :_

![mind mapping outils devops](media/formation-outils-devops.webp)

1. **Administration de serveurs** : Savoir configurer et dépanner un serveur Linux ou
   Windows
2. **Langages de Programmation** : Savoir écrire des petits programmes
3. **Connaitre les rudiments des réseaux et de la Sécurité Informatique** (Adresse
   IP, Firewalls, Routage)
4. **Configuration et maintenance de serveurs** : WEB, Cache et de Base de Données.
5. **Savoir écrire du code d'infrastructure**
6. **Savoir écrire des pipelines de CI/CD**
7. **Savoir construire et Orchestrer des conteneurs** (applications cloud native)
8. **Connaître les principaux Clouders**.
9. **Mise en place d'outils de Surveillance et de Centralisation de logs**

Vous pouvez démarrer plusieurs sujets en parallèle, mais pas trop tout de même.
Par exemple pour la partie Administration de Serveurs vous pouvez lire en //
la configuration réseau. Vous pouvez aussi regarder la construction de VM avec
**Vagrant** pour réaliser vos exercices.

Pour vous aider je vais mettre ci-dessous rapidement toute une série de liens
menant soit vers des sites, soit des livres (**en cours d'élaboration**) :

##  2. <a name='1.-administration-de-serveurs'></a>1. Administration de serveurs

###  2.1. <a name='1.1.-linux'></a>1.1. Linux

####  2.1.1. <a name='1.1.1.-livres-gratuits'></a>1.1.1. Livres gratuits

- [Programmation Bash](https://upload.wikimedia.org/wikipedia/commons/1/1a/Programmation_Bash-fr.pdf)
- [Guide avancé d'écriture des scripts Bash](https://abs.traduc.org/abs-fr/)
- [Le cahier de l'administrateur Debian](https://debian-handbook.info/browse/fr-FR/stable/)

####  2.1.2. <a name='1.1.2.-livres'></a>1.1.2. Livres

- [LINUX - Maîtrisez l'administration du système (6e
  édition)](https://amzn.to/3e41hWE) de Sébastien Rohaut
- [Administration Linux par la pratique - Tome 1 : les fondamentaux de
  l'administration système](https://amzn.to/3QY8Igo) de Sébastien Chazallet
- [Linux - Administration système et exploitation des services réseau (4e
  édition)](https://amzn.to/3CC3L8D) de Philippe Blanquet

####  2.1.3. <a name='1.1.3.-mooc'></a>1.1.3. MOOC

- [Maîtriser le shell Bash](https://www.fun-mooc.fr/fr/cours/maitriser-le-shell-bash/)

###  2.2. <a name='1.2.-windows'></a>1.2. Windows

####  2.2.1. <a name='1.2.1.-livres-gratuits'></a>1.2.1. Livres gratuits

####  2.2.2. <a name='1.2.2.-livres'></a>1.2.2. Livres

####  2.2.3. <a name='1.2.3.-mooc'></a>1.2.3. MOOC

##  3. <a name='2.-langages-de-programmation'></a>2. Langages de Programmation

###  3.1. <a name='2.1.-python'></a>2.1. Python

**Site officiel** : [Python.org](https://www.python.org/)

####  3.1.1. <a name='2.1.1.-livres-gratuits'></a>2.1.1. Livres gratuits

- [Cours de Python](https://python.sdv.univ-paris-diderot.fr/cours-python.pdf)

####  3.1.2. <a name='2.1.2.-livres'></a>2.1.2. Livres

- [Apprenez à programmer en Python](https://amzn.to/3QWe77T) de Vincent Le Goff
- [Python 3 - Les fondamentaux du langage](https://amzn.to/3pNP76D)

####  3.1.3. <a name='2.1.3.-mooc'></a>2.1.3. MOOC

- [Python : des fondamentaux aux concepts avancés du langage](https://www.fun-mooc.fr/fr/cours/python-3-des-fondamentaux-aux-concepts-avances-du-langage/)
- [Apprendre à coder avec Python](https://www.fun-mooc.fr/fr/cours/apprendre-a-coder-avec-python/)

###  3.2. <a name='2.2.-golang'></a>2.2. Golang

**Site officiel** : [Go.dev](https://go.dev/)

####  3.2.1. <a name='2.2.1-livres-gratuits'></a>2.2.1 Livres Gratuits

####  3.2.2. <a name='2.2.2-livres'></a>2.2.2 Livres

####  3.2.3. <a name='2.2.3.-mooc'></a>2.2.3. MOOC

####  3.2.4. <a name='2.2.3.-sites'></a>2.2.3. Sites

**Site français** : [golang.io/fr/](http://golang.io/fr/) : Des informations et
des tutoriels.

###  3.3. <a name='2.3.-rust'></a>2.3. Rust

**Site officiel** : [Rust-lang.org](https://www.rust-lang.org/fr) (Fr).

###  3.4. <a name='2.4.-ruby'></a>2.4. Ruby

**Site officiel** : [Ruby-lang.fr](https://www.ruby-lang.org/fr/) (Fr).

##  4. <a name='3.-réseaux-et-sécurité-informatique'></a>3. Réseaux et Sécurité Informatique

###  4.1. <a name='3.1.-réseaux'></a>3.1. Réseaux

####  4.1.1. <a name='3.1.1.-livres-gratuits'></a>3.1.1. Livres gratuits

####  4.1.2. <a name='3.1.2.-livres'></a>3.1.2. Livres

####  4.1.3. <a name='3.1.3.-mooc'></a>3.1.3. MOOC

[Les Réseaux Locaux](https://www.fun-mooc.fr/fr/cours/les-reseaux-locaux/)

##  5. <a name='4.-configuration-et-maintenance-de-serveurs'></a>4. Configuration et maintenance de Serveurs

###  5.1. <a name='4.1.-serveurs-web'></a>4.1. Serveurs WEB

####  5.1.1. <a name='4.1.1.-apache'></a>4.1.1. Apache

####  5.1.2. <a name='4.1.2.-nginx'></a>4.1.2. Nginx

###  5.2. <a name='4.2.-serveurs-de-cache'></a>4.2. Serveurs de Cache

####  5.2.1. <a name='4.2.1.-redis'></a>4.2.1. Redis

####  5.2.2. <a name='4.2.2.-memcache'></a>4.2.2. Memcache

###  5.3. <a name='4.3.-base-de-données'></a>4.3. Base de Données

####  5.3.1. <a name='4.3.1.-généralités'></a>4.3.1. Généralités

##### MOOC :

- [Bases de données relationnelles : apprendre pour utiliser](https://www.fun-mooc.fr/fr/cours/bases-de-donnees-relationnelles-apprendre-pour-utiliser/)
-

###  5.4. <a name='4.4.-mysql'></a>4.4. MySQL

###  5.5. <a name='4.5.-postgresql'></a>4.5. PostgreSQL

###  5.6. <a name='4.6.-mongodb'></a>4.6. MongoDB

###  5.7. <a name='4.7.-oracledb'></a>4.7. OracleDB

##  6. <a name='5.-infrastructure-as-code'></a>5. Infrastructure as Code

###  6.1. <a name='5.1.-provisionning'></a>5.1. Provisionning

####  6.1.1. <a name='5.1.1.-vagrant'></a>5.1.1. Vagrant

- Apprendre et Maitriser Vagrant](http://blog.stephane-robert.info/post/introduction-vagrant/)

####  6.1.2. <a name='5.1.2.-terraform'></a>5.1.2. Terraform

####  6.1.3. <a name='5.1.3.-cloudformation'></a>5.1.3. CloudFormation

####  6.1.4. <a name='5.1.4.-gestion-de-configuration-:'></a>5.1.4. Gestion de Configuration :

####  6.1.5. <a name='5.1.5.-ansible'></a>5.1.5. Ansible

- [Apprendre et Maitriser Ansible l'outil de gestion de configuration](http://blog.stephane-robert.info/post/introduction-ansible/)

####  6.1.6. <a name='5.1.6.-puppet'></a>5.1.6. Puppet

####  6.1.7. <a name='5.1.7.-chef'></a>5.1.7. Chef

####  6.1.8. <a name='5.1.8.-salt'></a>5.1.8. Salt

##  7. <a name='6.-pipelines-de-ci/cd-:'></a>6. Pipelines de CI/CD :

###  7.1. <a name='6.1.-gitlab-ci/cd'></a>6.1. Gitlab-CI/CD

###  7.2. <a name='6.2.-github-actions'></a>6.2. Github Actions

###  7.3. <a name='6.3.-jenkins'></a>6.3. Jenkins

##  8. <a name='7.-conteneurs-et-orchestrateurs'></a>7. Conteneurs et Orchestrateurs

###  8.1. <a name='7.1.-conteneurs-docker-:'></a>7.1. Conteneurs Docker :

####  8.1.1. <a name='7.1.1.-docker'></a>7.1.1. Docker

####  8.1.2. <a name='7.1.2.-docker-compose'></a>7.1.2. Docker-compose

###  8.2. <a name='7.2.-orchestrateurs'></a>7.2. Orchestrateurs

####  8.2.1. <a name='7.2.1.-kubernetes'></a>7.2.1. Kubernetes

####  8.2.2. <a name='7.2.2.-nomad'></a>7.2.2. Nomad

##  9. <a name='8.-clouders'></a>8. Clouders

###  9.1. <a name='8.1.-aws'></a>8.1. AWS

###  9.2. <a name='8.2.-gcp'></a>8.2. GCP

###  9.3. <a name='8.3.-azure'></a>8.3. Azure

##  10. <a name='9.-surveillance'></a>9. Surveillance

###  10.1. <a name='9.1.-logging-:'></a>9.1. Logging :

####  10.1.1. <a name='9.1.1.-zabbix'></a>9.1.1. Zabbix

####  10.1.2. <a name='9.1.2.-centreon'></a>9.1.2. Centreon

####  10.1.3. <a name='9.1.3.-prometheus'></a>9.1.3. Prometheus

####  10.1.4. <a name='9.1.4.-grafana'></a>9.1.4. Grafana

###  10.2. <a name='9.2.-monitoring-:'></a>9.2. Monitoring :

####  10.2.1. <a name='9.2.1.-splunk'></a>9.2.1. Splunk

####  10.2.2. <a name='9.2.2.-elk'></a>9.2.2. ELK

####  10.2.3. <a name='9.2.3.-datadog'></a>9.2.3. Datadog

**Vous pouvez m'aider en m'envoyant des liens sur tous ces sujets que vous
considérez comme très bons. Pas simplement des articles, mais du contenu un peu
plus élaboré et complet.**

##  11. <a name='10.-blogs-devops'></a>10. Blogs Devops

Voici une liste non exhaustive ou vous trouverez de bons articles sur les **outils
Devops**.

###  11.1. <a name='10.1.-blogs-perso'></a>10.1. Blogs Perso

- [Zwindler's Reflection](https://blog.zwindler.fr/)
- [Bruno Levasseur](https://blog.levassb.ovh/)
- [damyr](https://www.damyr.fr)
- [dadall](https://www.dadall.info)
- [tferdinand](https://tferdinand.net)
- [grottedubarbu](https://www.grottedubarbu.fr)
- [jesuisundev](https://www.jesuisundev.com)
- [la forge](https://lafor.ge/)

###  11.2. <a name='10.2.-sociétés'></a>10.2. Sociétés

- [linkvalue](https://blog.link-value.fr/)
- [eleven-labs](https://blog.eleven-labs.com)
- [d2si](https://blog.d2si.io)
- [wescale](https://blog.wescale.fr)
- [ovh](https://www.ovh.com/blog)
- [scaleway](https://blog.scaleway.com)
- [journalduhacker](https://www.journalduhacker.net)
- [Claranet notsosecure](https://notsosecure.com/blog)
- [publicissapient](http://blog.engineering.publicissapient.fr)
- [eazytraining](https://eazytraining.fr/blog/)

##  12. <a name='11.-communautés'></a>11. Communautés

- [Compagnons du Devops](https://www.compagnons-devops.fr/)

##  13. <a name='12.-chaines-youtube'></a>12. Chaines Youtube

- [Xavki](https://www.youtube.com/c/xavki-linux)
- [Compagnons du Devops](https://www.youtube.com/c/LesCompagnonsduDevOps)
- [Cloud Nord](https://www.youtube.com/channel/UCD_iUcnDZgFlU_7fBmWH3tA)

##  14. <a name='13.-des-comptes-twitters'></a>13. Des comptes Twitters

- [Aurélie Vache](https://mobile.twitter.com/aurelievache)
- [Katia HIMEUR TALHI](https://mobile.twitter.com/katia_tal)

##  15. <a name='contribuer'></a>Contribuer

Vos contributions sont toujours les bienvenues ! Elles doivent être non
commerciales. Je me garde le droit de ne pas accepter certaines demandes.

##  16. <a name='des-lignes-directrices'></a>Des lignes directrices

* Vous pouvez ajouter plusieurs liens par pull request.
  * Assurez-vous que le titre PR est au format `Ajout du lien`.
* Ajoutez le lien :* [le-lien](http://example.com/) - Une courte phrase
  de description (concise et courte) ponctuée par un point.
* Ajoutez une section si nécessaire.
* Ajoutez la description de la section.
* Ajoutez le titre de la section à la table des matières.
* Recherchez les demandes d'extraction ou les problèmes précédents avant d'en créer un nouveau, car le vôtre peut être un doublon.
* Vérifiez votre orthographe et votre grammaire.
* Supprimez tout espace blanc de fin.
