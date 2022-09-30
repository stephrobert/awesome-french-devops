# Awesome French Devops [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

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

{{< table_of_contents >}}

## 1. Administration de serveurs

### 1.1. Linux

#### 1.1.1. Livres gratuits

- [Programmation Bash](https://upload.wikimedia.org/wikipedia/commons/1/1a/Programmation_Bash-fr.pdf)
- [Guide avancé d'écriture des scripts Bash](https://abs.traduc.org/abs-fr/)
- [Le cahier de l'administrateur Debian](https://debian-handbook.info/browse/fr-FR/stable/)

#### 1.1.2. Livres

- [LINUX - Maîtrisez l'administration du système (6e
  édition)](https://amzn.to/3e41hWE) de Sébastien Rohaut
- [Administration Linux par la pratique - Tome 1 : les fondamentaux de
  l'administration système](https://amzn.to/3QY8Igo) de Sébastien Chazallet
- [Linux - Administration système et exploitation des services réseau (4e
  édition)](https://amzn.to/3CC3L8D) de Philippe Blanquet

#### 1.1.3. MOOC

- [Maîtriser le shell Bash](https://www.fun-mooc.fr/fr/cours/maitriser-le-shell-bash/)

### 1.2. Windows

#### 1.2.1. Livres gratuits

#### 1.2.2. Livres

#### 1.2.3. MOOC

## 2. Langages de Programmation

### 2.1. Python

**Site officiel** : [Python.org](https://www.python.org/)

#### 2.1.1. Livres gratuits

- [Cours de Python](https://python.sdv.univ-paris-diderot.fr/cours-python.pdf)

#### 2.1.2. Livres

- [Apprenez à programmer en Python](https://amzn.to/3QWe77T) de Vincent Le Goff
- [Python 3 - Les fondamentaux du langage](https://amzn.to/3pNP76D)

#### 2.1.3. MOOC

- [Python : des fondamentaux aux concepts avancés du langage](https://www.fun-mooc.fr/fr/cours/python-3-des-fondamentaux-aux-concepts-avances-du-langage/)
- [Apprendre à coder avec Python](https://www.fun-mooc.fr/fr/cours/apprendre-a-coder-avec-python/)

### 2.2. Golang

**Site officiel** : [Go.dev](https://go.dev/)

#### 2.2.1 Livres Gratuits

#### 2.2.2 Livres

#### 2.2.3. MOOC

#### 2.2.3. Sites

**Site français** : [golang.io/fr/](http://golang.io/fr/) : Des informations et
des tutoriels.

### 2.3. Rust

**Site officiel** : [Rust-lang.org](https://www.rust-lang.org/fr) (Fr).

### 2.4. Ruby

**Site officiel** : [Ruby-lang.fr](https://www.ruby-lang.org/fr/) (Fr).

## 3. Réseaux et Sécurité Informatique

### 3.1. Réseaux

#### 3.1.1. Livres gratuits

#### 3.1.2. Livres

#### 3.1.3. MOOC

[Les Réseaux Locaux](https://www.fun-mooc.fr/fr/cours/les-reseaux-locaux/)

## 4. Configuration et maintenance de Serveurs

### 4.1. Serveurs WEB

#### 4.1.1. Apache

#### 4.1.2. Nginx

### 4.2. Serveurs de Cache

#### 4.2.1. Redis

#### 4.2.2. Memcache

### 4.3. Base de Données

#### 4.3.1. Généralités

##### MOOC :

- [Bases de données relationnelles : apprendre pour utiliser](https://www.fun-mooc.fr/fr/cours/bases-de-donnees-relationnelles-apprendre-pour-utiliser/)
-

### 4.4. MySQL

### 4.5. PostgreSQL

### 4.6. MongoDB

### 4.7. OracleDB

## 5. Infrastructure as Code

### 5.1. Provisionning

#### 5.1.1. Vagrant

- Apprendre et Maitriser Vagrant](http://blog.stephane-robert.info/post/introduction-vagrant/)

#### 5.1.2. Terraform

#### 5.1.3. CloudFormation

#### 5.1.4. Gestion de Configuration :

#### 5.1.5. Ansible

- [Apprendre et Maitriser Ansible l'outil de gestion de configuration](http://blog.stephane-robert.info/post/introduction-ansible/)

#### 5.1.6. Puppet

#### 5.1.7. Chef

#### 5.1.8. Salt

## 6. Pipelines de CI/CD :

### 6.1. Gitlab-CI/CD

### 6.2. Github Actions

### 6.3. Jenkins

## 7. Conteneurs et Orchestrateurs

### 7.1. Conteneurs Docker :

#### 7.1.1. Docker

#### 7.1.2. Docker-compose

### 7.2. Orchestrateurs

#### 7.2.1. Kubernetes

#### 7.2.2. Nomad

## 8. Clouders

### 8.1. AWS

### 8.2. GCP

### 8.3. Azure

## 9. Surveillance

### 9.1. Logging :

#### 9.1.1. Zabbix

#### 9.1.2. Centreon

#### 9.1.3. Prometheus

#### 9.1.4. Grafana

### 9.2. Monitoring :

#### 9.2.1. Splunk

#### 9.2.2. ELK

#### 9.2.3. Datadog

**Vous pouvez m'aider en m'envoyant des liens sur tous ces sujets que vous
considérez comme très bons. Pas simplement des articles, mais du contenu un peu
plus élaboré et complet.**

## 10. Blogs Devops

Voici une liste non exhaustive ou vous trouverez de bons articles sur les **outils
Devops**.

### 10.1. Blogs Perso

- [Zwindler's Reflection](https://blog.zwindler.fr/)
- [Bruno Levasseur](https://blog.levassb.ovh/)
- [damyr](https://www.damyr.fr)
- [dadall](https://www.dadall.info)
- [tferdinand](https://tferdinand.net)
- [grottedubarbu](https://www.grottedubarbu.fr)
- [jesuisundev](https://www.jesuisundev.com)
- [la forge](https://lafor.ge/)

### 10.2. Sociétés

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

## 11. Communautés

- [Compagnons du Devops](https://www.compagnons-devops.fr/)

## 12. Chaines Youtube

- [Xavki](https://www.youtube.com/c/xavki-linux)
- [Compagnons du Devops](https://www.youtube.com/c/LesCompagnonsduDevOps)
- [Cloud Nord](https://www.youtube.com/channel/UCD_iUcnDZgFlU_7fBmWH3tA)

## 13. Des comptes Twitters

- [Aurélie Vache](https://mobile.twitter.com/aurelievache)
- [Katia HIMEUR TALHI](https://mobile.twitter.com/katia_tal)
