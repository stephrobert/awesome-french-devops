# Awesome French Devops [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<!-- vscode-markdown-toc -->
* 1. [Introduction](#Introduction)
* 2. [Administration de serveurs](#Administrationdeserveurs)
	* 2.1. [Linux](#Linux)
		* 2.1.1. [Livres gratuits](#Livresgratuits)
		* 2.1.2. [Livres](#Livres)
		* 2.1.3. [MOOC](#MOOC)
	* 2.2. [Windows](#Windows)
		* 2.2.1. [Livres gratuits](#Livresgratuits-1)
		* 2.2.2. [Livres](#Livres-1)
		* 2.2.3. [MOOC](#MOOC-1)
* 3. [Langages de Programmation](#LangagesdeProgrammation)
	* 3.1. [Python](#Python)
		* 3.1.1. [Livres gratuits](#Livresgratuits-1)
		* 3.1.2. [Livres](#Livres-1)
		* 3.1.3. [MOOC](#MOOC-1)
	* 3.2. [Golang](#Golang)
		* 3.2.1. [Livres Gratuits](#LivresGratuits)
		* 3.2.2. [Livres](#Livres-1)
		* 3.2.3. [MOOC](#MOOC-1)
		* 3.2.4. [Sites](#Sites)
	* 3.3. [Rust](#Rust)
	* 3.4. [Ruby](#Ruby)
* 4. [Réseaux et Sécurité Informatique](#RseauxetScuritInformatique)
	* 4.1. [Réseaux](#Rseaux)
		* 4.1.1. [Livres gratuits](#Livresgratuits-1)
		* 4.1.2. [Livres](#Livres-1)
		* 4.1.3. [MOOC](#MOOC-1)
* 5. [Configuration et maintenance de Serveurs](#ConfigurationetmaintenancedeServeurs)
	* 5.1. [Serveurs WEB](#ServeursWEB)
		* 5.1.1. [Apache](#Apache)
		* 5.1.2. [Nginx](#Nginx)
	* 5.2. [Serveurs de Cache](#ServeursdeCache)
		* 5.2.1. [Redis](#Redis)
		* 5.2.2. [Memcache](#Memcache)
	* 5.3. [Base de Données](#BasedeDonnes)
		* 5.3.1. [Généralités](#Gnralits)
	* 5.4. [MySQL](#MySQL)
	* 5.5. [PostgreSQL](#PostgreSQL)
	* 5.6. [MongoDB](#MongoDB)
	* 5.7. [OracleDB](#OracleDB)
* 6. [Infrastructure as Code](#InfrastructureasCode)
	* 6.1. [Provisionning](#Provisionning)
		* 6.1.1. [Vagrant](#Vagrant)
		* 6.1.2. [Terraform](#Terraform)
		* 6.1.3. [CloudFormation](#CloudFormation)
		* 6.1.4. [Gestion de Configuration :](#GestiondeConfiguration:)
		* 6.1.5. [Ansible](#Ansible)
		* 6.1.6. [Puppet](#Puppet)
		* 6.1.7. [Chef](#Chef)
		* 6.1.8. [Salt](#Salt)
* 7. [Pipelines de CI/CD :](#PipelinesdeCICD:)
	* 7.1. [Gitlab-CI/CD](#Gitlab-CICD)
	* 7.2. [Github Actions](#GithubActions)
	* 7.3. [Jenkins](#Jenkins)
* 8. [Conteneurs et Orchestrateurs](#ConteneursetOrchestrateurs)
	* 8.1. [Conteneurs Docker :](#ConteneursDocker:)
		* 8.1.1. [Docker](#Docker)
		* 8.1.2. [Docker-compose](#Docker-compose)
	* 8.2. [Orchestrateurs](#Orchestrateurs)
		* 8.2.1. [Kubernetes](#Kubernetes)
		* 8.2.2. [Nomad](#Nomad)
* 9. [Clouders](#Clouders)
	* 9.1. [AWS](#AWS)
	* 9.2. [GCP](#GCP)
	* 9.3. [Azure](#Azure)
* 10. [Surveillance](#Surveillance)
	* 10.1. [Logging :](#Logging:)
		* 10.1.1. [Zabbix](#Zabbix)
		* 10.1.2. [Centreon](#Centreon)
		* 10.1.3. [Prometheus](#Prometheus)
		* 10.1.4. [Grafana](#Grafana)
	* 10.2. [Monitoring :](#Monitoring:)
		* 10.2.1. [Splunk](#Splunk)
		* 10.2.2. [ELK](#ELK)
		* 10.2.3. [Datadog](#Datadog)
* 11. [Blogs Devops](#BlogsDevops)
	* 11.1. [Blogs Perso](#BlogsPerso)
	* 11.2. [Sociétés](#Socits)
* 12. [Communautés](#Communauts)
* 13. [Chaines Youtube](#ChainesYoutube)
* 14. [Des comptes Twitters](#DescomptesTwitters)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

##  1. <a name='Introduction'></a>Introduction

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

##  2. <a name='Administrationdeserveurs'></a>Administration de serveurs

###  2.1. <a name='Linux'></a>Linux

####  2.1.1. <a name='Livresgratuits'></a>Livres gratuits

- [Programmation Bash](https://upload.wikimedia.org/wikipedia/commons/1/1a/Programmation_Bash-fr.pdf)
- [Guide avancé d'écriture des scripts Bash](https://abs.traduc.org/abs-fr/)
- [Le cahier de l'administrateur Debian](https://debian-handbook.info/browse/fr-FR/stable/)

####  2.1.2. <a name='Livres'></a>Livres

- [LINUX - Maîtrisez l'administration du système (6e
  édition)](https://amzn.to/3e41hWE) de Sébastien Rohaut
- [Administration Linux par la pratique - Tome 1 : les fondamentaux de
  l'administration système](https://amzn.to/3QY8Igo) de Sébastien Chazallet
- [Linux - Administration système et exploitation des services réseau (4e
  édition)](https://amzn.to/3CC3L8D) de Philippe Blanquet

####  2.1.3. <a name='MOOC'></a>MOOC

- [Maîtriser le shell Bash](https://www.fun-mooc.fr/fr/cours/maitriser-le-shell-bash/)

###  2.2. <a name='Windows'></a>Windows

####  2.2.1. <a name='Livresgratuits-1'></a>Livres gratuits

####  2.2.2. <a name='Livres-1'></a>Livres

####  2.2.3. <a name='MOOC-1'></a>MOOC

##  3. <a name='LangagesdeProgrammation'></a>Langages de Programmation

###  3.1. <a name='Python'></a>Python

**Site officiel** : [Python.org](https://www.python.org/)

####  3.1.1. <a name='Livresgratuits-1'></a>Livres gratuits

- [Cours de Python](https://python.sdv.univ-paris-diderot.fr/cours-python.pdf)

####  3.1.2. <a name='Livres-1'></a>Livres

- [Apprenez à programmer en Python](https://amzn.to/3QWe77T) de Vincent Le Goff
- [Python 3 - Les fondamentaux du langage](https://amzn.to/3pNP76D)

####  3.1.3. <a name='MOOC-1'></a>MOOC

- [Python : des fondamentaux aux concepts avancés du langage](https://www.fun-mooc.fr/fr/cours/python-3-des-fondamentaux-aux-concepts-avances-du-langage/)
- [Apprendre à coder avec Python](https://www.fun-mooc.fr/fr/cours/apprendre-a-coder-avec-python/)

###  3.2. <a name='Golang'></a>Golang

**Site officiel** : [Go.dev](https://go.dev/)

####  3.2.1. <a name='LivresGratuits'></a>Livres Gratuits

####  3.2.2. <a name='Livres-1'></a>Livres

####  3.2.3. <a name='MOOC-1'></a>MOOC

####  3.2.4. <a name='Sites'></a>Sites

**Site français** : [golang.io/fr/](http://golang.io/fr/) : Des informations et
des tutoriels.

###  3.3. <a name='Rust'></a>Rust

**Site officiel** : [Rust-lang.org](https://www.rust-lang.org/fr) (Fr).

###  3.4. <a name='Ruby'></a>Ruby

**Site officiel** : [Ruby-lang.fr](https://www.ruby-lang.org/fr/) (Fr).

##  4. <a name='RseauxetScuritInformatique'></a>Réseaux et Sécurité Informatique

###  4.1. <a name='Rseaux'></a>Réseaux

####  4.1.1. <a name='Livresgratuits-1'></a>Livres gratuits

####  4.1.2. <a name='Livres-1'></a>Livres

####  4.1.3. <a name='MOOC-1'></a>MOOC

[Les Réseaux Locaux](https://www.fun-mooc.fr/fr/cours/les-reseaux-locaux/)

##  5. <a name='ConfigurationetmaintenancedeServeurs'></a>Configuration et maintenance de Serveurs

###  5.1. <a name='ServeursWEB'></a>Serveurs WEB

####  5.1.1. <a name='Apache'></a>Apache

####  5.1.2. <a name='Nginx'></a>Nginx

###  5.2. <a name='ServeursdeCache'></a>Serveurs de Cache

####  5.2.1. <a name='Redis'></a>Redis

####  5.2.2. <a name='Memcache'></a>Memcache

###  5.3. <a name='BasedeDonnes'></a>Base de Données

####  5.3.1. <a name='Gnralits'></a>Généralités

##### MOOC :

- [Bases de données relationnelles : apprendre pour utiliser](https://www.fun-mooc.fr/fr/cours/bases-de-donnees-relationnelles-apprendre-pour-utiliser/)
-

###  5.4. <a name='MySQL'></a>MySQL

###  5.5. <a name='PostgreSQL'></a>PostgreSQL

###  5.6. <a name='MongoDB'></a>MongoDB

###  5.7. <a name='OracleDB'></a>OracleDB

##  6. <a name='InfrastructureasCode'></a>Infrastructure as Code

###  6.1. <a name='Provisionning'></a>Provisionning

####  6.1.1. <a name='Vagrant'></a>Vagrant

- Apprendre et Maitriser Vagrant](http://blog.stephane-robert.info/post/introduction-vagrant/)

####  6.1.2. <a name='Terraform'></a>Terraform

####  6.1.3. <a name='CloudFormation'></a>CloudFormation

####  6.1.4. <a name='GestiondeConfiguration:'></a>Gestion de Configuration :

####  6.1.5. <a name='Ansible'></a>Ansible

- [Apprendre et Maitriser Ansible l'outil de gestion de configuration](http://blog.stephane-robert.info/post/introduction-ansible/)

####  6.1.6. <a name='Puppet'></a>Puppet

####  6.1.7. <a name='Chef'></a>Chef

####  6.1.8. <a name='Salt'></a>Salt

##  7. <a name='PipelinesdeCICD:'></a>Pipelines de CI/CD :

###  7.1. <a name='Gitlab-CICD'></a>Gitlab-CI/CD

- [Commencer simplement avec GitLab CI](https://dev.to/jphi_baconnais/commencer-simplement-avec-gitlabci-53fa)
- [Comment organiser son travail avec GitLab](https://dev.to/zenika/comment-organiser-son-travail-avec-gitlab-42da)

###  7.2. <a name='GithubActions'></a>Github Actions

###  7.3. <a name='Jenkins'></a>Jenkins

##  8. <a name='ConteneursetOrchestrateurs'></a>Conteneurs et Orchestrateurs

###  8.1. <a name='ConteneursDocker:'></a>Conteneurs Docker :

####  8.1.1. <a name='Docker'></a>Docker

####  8.1.2. <a name='Docker-compose'></a>Docker-compose

###  8.2. <a name='Orchestrateurs'></a>Orchestrateurs

####  8.2.1. <a name='Kubernetes'></a>Kubernetes

####  8.2.2. <a name='Nomad'></a>Nomad

##  9. <a name='Clouders'></a>Clouders

###  9.1. <a name='AWS'></a>AWS

###  9.2. <a name='GCP'></a>GCP

###  9.3. <a name='Azure'></a>Azure

##  10. <a name='Surveillance'></a>Surveillance

###  10.1. <a name='Logging:'></a>Logging :

####  10.1.1. <a name='Zabbix'></a>Zabbix

####  10.1.2. <a name='Centreon'></a>Centreon

####  10.1.3. <a name='Prometheus'></a>Prometheus

####  10.1.4. <a name='Grafana'></a>Grafana

###  10.2. <a name='Monitoring:'></a>Monitoring :

####  10.2.1. <a name='Splunk'></a>Splunk

####  10.2.2. <a name='ELK'></a>ELK

####  10.2.3. <a name='Datadog'></a>Datadog

**Vous pouvez m'aider en m'envoyant des liens sur tous ces sujets que vous
considérez comme très bons. Pas simplement des articles, mais du contenu un peu
plus élaboré et complet.**

##  11. <a name='BlogsDevops'></a>Blogs Devops

Voici une liste non exhaustive ou vous trouverez de bons articles sur les **outils
Devops**.

###  11.1. <a name='BlogsPerso'></a>Blogs Perso

- [Zwindler's Reflection](https://blog.zwindler.fr/)
- [Bruno Levasseur](https://blog.levassb.ovh/)
- [damyr](https://www.damyr.fr)
- [dadall](https://www.dadall.info)
- [tferdinand](https://tferdinand.net)
- [grottedubarbu](https://www.grottedubarbu.fr)
- [jesuisundev](https://www.jesuisundev.com)
- [la forge](https://lafor.ge/)

###  11.2. <a name='Socits'></a>Sociétés

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

##  12. <a name='Communauts'></a>Communautés

- [Compagnons du Devops](https://www.compagnons-devops.fr/)

##  13. <a name='ChainesYoutube'></a>Chaines Youtube

- [Xavki](https://www.youtube.com/c/xavki-linux)
- [Compagnons du Devops](https://www.youtube.com/c/LesCompagnonsduDevOps)
- [Cloud Nord](https://www.youtube.com/channel/UCD_iUcnDZgFlU_7fBmWH3tA)
- [Inpulse.tv - Playlist Devops & cloud](https://www.youtube.com/playlist?list=PLORtqNVm6r7BVC3ldqwLK4Nl_FgjwpQpU) 

##  14. <a name='DescomptesTwitters'></a>Des comptes Twitters

- [Aurélie Vache](https://mobile.twitter.com/aurelievache)
- [Katia HIMEUR TALHI](https://mobile.twitter.com/katia_tal)
