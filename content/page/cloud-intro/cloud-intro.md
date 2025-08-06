+++
author = "Dumenoir Loan"
title = "Introduction au cloud"
date = "2025-06-19"
description = "Introduction : Cloud Computing & panorama des solutions"
categories = [
    "cloud"
]
tags = [
    "cloud"
]
image = "page/cloud-intro/cloud-intro-couverture.png"
+++  

Hello world, et bienvenue sur cette page d'introduction au cloud !

Cette page est destinée, à tous ceux qui veulent découvrir ou approfondir leurs connaissances sur le cloud. Que vous soyez entrepreneur, technicien en IT, commercial, développeur d'application ou encore étudiant dans le domaine du numérique. Ce post est fait pour vous ! Nous allons dans un premier temps définir ce qu'est un cloud afin de s'accorder sur une définition simple mais précise avant de s'attaquer au vif du sujet, les différents types de cloud et ce qu'ils proposent.

Le cloud est un sujet complexe et souvent abstrait pour le grand public, parfois même pour les techniciens. Mais pas de panique ! Nous allons explorer le sujet pas à pas, nous finirons pas un comparatif des solutions existantes sur le marché afin que vous soyez capable de choisir la solution la plus adapté à votre besoin.

A la fin de cette lecture le cloud n'aura plus de secret pour vous ! Vous serez en mesure de comprendre ce qu'est le cloud. De quel type de cloud s'agit-il lorsque l'on parle d'*iCloud*, *Spotify* ou *Airbnb*. Et quel est la différence entre *DropBox*, *OVH* ou encore *AWS*.

# 1. Définition d'un cloud

Le concept du cloud est loin d'être nouveau. En réalité il existait même avant Internet, au tout début de l'informatique dans les années 1950, à cette époque les utilisateurs travailler conjointement sur un seul et unique serveur par le biais de terminaux.

C'est là que la **notion** de *Cloud computing* émerge, permettant alors à plusieurs utilisateurs de tirer parti d'une puissante machine pour partager des ressources informatiques.

Néamoins ce n'est qu'en 1994 que le terme de *Cloud* fait son apparition. Ce terme était donc une métaphore pour décrire un système accessible à distance. La définition du cloud a cependant évoluer depuis les années 2000.

Aujourd'hui, le *Cloud* repose sur 3 pilliers fondamentaux : **Mutualisation**, **Elasticité** et **Facturation à l'usage**.
Sans ces 3 éléments, on ne parlera pas de *Cloud*. 

### Mutualisation

La mutualisation signifie que les ressources matérielles et logicielles sont partagées. Ces ressources sont principalement des unités de calculs, du stockage et des réseaux.

### Elasticité

L'élasticité est un concept fondamental du *Cloud*, il permet a une plateforme d'ajuster de manière dynamique la puissance dont elle a besoin. Permettant l'optimisation des ressources qui y sont partagées.

### Facturation à l'usage

La facturation à l'usage fait désormais parti de la définition du *Cloud*, ce qui signifie que vous ne payez que pour ce que vous consommez. C'est avantage considérable, permet de s'affranchir des coûts d'investissement.


### Exemple :

Pour illustrer les avantages du *Cloud* nous allons prendre l'exemple d'un jeune entrepreneur John Doe ayant une idée d'application, il souhaite mettre en relation des chauffeur et des personnes voulant voyager d'un point A à un point B (Cela doit vous dire quelques choses...). John décide alors une commission sur chaque course afin de gagner de l'argent, le problème c'est que John n'a pas de capital. Il compte sur ses talents de développeur pour créer une application et il souhaite faire la communication par lui même pour ne pas avoir de coûts d'investissement. Une fois le développement terminé, John doit déployer son application afin que tout le monde puisse l'utiliser. Ne pouvant pas acheter de serveur, John décide d'utiliser le Cloud pour déployer son application. Il payera quelques centimes la course, et pourra se verser une commission. Il évite donc les coûts d'investissement de l'achat du matériel et ne **payera que ce qu'il consomme**. 

Si l'application fonctionne et qu'il dépasse les 100 utilisateurs, John n'aura pas a se soucier d'acheter un autre serveur, car il bénéficiera de l'**élasticité** du cloud.

La **mutualisation** du cloud s'illustre en se disant que l'application de John, sera hébergé sur les mêmes machines que celle de ces amis ayant créé une application mettant en lien des locataires et des bailleurs (*Airbnb*).

### En résumé :
|Concept|Description|Bénéfice|
|---|---|---|
| **Mutualisation** | Les ressources matérielles et logicielles sont **partagées** par plusieurs clients ou projets|Induisant une **réduction des coûts** d'acquisition et de maintenance|
| **Elasticité** | La plateforme peut ajuster **dynamiquement** la puissance de calcul, la capacité de stockage ou la bande passante en fonction de la charge. | Permet une **scalabilité** presque instantanée pour gérer les pics ou baisses d'activité. |
| **Facturation à l'usage** | Le client paie __uniquement pour ce qu'il consomme__ (pay-as-you-go). | Alignement des coûts sur la **consommation réelle**. |


# 2. Modèles de déploiement

Lorsque l'on parle de cloud, certains noms viennent naturellement à l'esprit tel que **AWS** (Amazon Web Services), **Microsoft Azure**, **GCP** (Google Cloud Platform) ou encore **OVH**. Mais ces géants ne représente en réalité qu'un seul modèle de déploiment cloud, le cloud public. Il existe en réalité une multitude d'autre fournisseur cloud. Néamoins pour certaines entreprises stocker ces données en ligne n'est pas concevable, c'est pour ça qu'un autre modèle de cloud est apparue, le cloud privé. Cependant créer et maintenir un cloud est un défi complexe et très couteux, c'est pour cela que certaines entreprises se sont tourné vers un mix de ses 2 clouds. Créant alors le cloud hybride.

| Modèle | Description | Cas d'usage type |
|---|---|---|
| **Public** | Infrastructures mutualisées, accessibles via Internet. | Démarrage rapide, scalabilité mondiale (start-ups, e-commerce). |
| **Privé** | Ressources dédiées à une seule organisation, hébergées on-premises ou chez un hébergeur. | Secteur réglementés, exigences strictes de sécurité (banque, défense). |
| **Hybride** | Combinaison orchestrée de cloud privé et public | Extension de capacité ponctuelle, résilience multi-site. |

# 3. Modèles de services

Indépendamment du modèle de déploiement, les clouds proposent différents modèles de services. Vous avez certainement déjà entendu parler de SaaS (Software as a Service) cette offre permettant d'avoir accès à une application à la demande. Ici pour les clouds nous pouvons choisir le niveau de granularité voulu avec de nouveau modèles tels que **PaaS** (Plateform as a Service) et **IaaS** (Infrastructure as a Service).

| Modèle | Ce que fournit le fournisseur | Ce que vous gérez | Exemples |
|---|---|---|---|
| **IaaS** | Matériel virtuel, réseau, stockage | OS, middleware, runtime, données, applications | AWS EC2, Google Compute Engine, OpenStack, VMware vSphere |
| **PaaS** | IaaS + OS + middleware + runtime | Données, applications | Azure App Service, Heroku, Red Hat OpenShift |
| **SaaS** | Application compète en ligne | Rien (simple configuration) | Microsoft 365, Salesforce, Dropbox |

# 4. Panorama des solutions du marché

## 4.1 Solution cloud public

| Fournisseur | Avantages | Inconvénient | Exemples d'entreprises qui l'utilisent |
|---|---|---|---|
| Amazon Web Services (AWS) | catalogue très large (>300 services), innovation rapide, présence mondiale, écosystème mature. | complexité, coût variable difficile à prévoir, dépendante forte. | Netflix, Airbnb, Société Générale. |
| Microsoft Azure | intégration native avec l'écosystème Microsoft (AD, Office 365), offres hybrides (Azure Arc), grand réseau de datacenters européens. | tarification complexe, certaines fonctionnalités en *preview* longue. | Heineken, Renault Group, Accor.
| Google Cloud Platform (GCP) | expertise data/ML, réseau backbone performant, facturation à la seconde. | portefeuille plus restreint que ses concurrents, moins de régions en Europe. | Spotify, Paypal, Airbus. |

D'autres solution existent tels que IBM Cloud, Oracle OCI, OVHcloud, Alibaba Cloud... Chacune d'entre elle présente ses avantages et inconvénients.

## 4.2 Solution cloud privé

Maintenant la partie que vous attendiez tous, quelques solutions de déploiement de cloud privé, vous permettant de créer votre propre cloud à la maison !

| Solution | Avantages | Inconvénients | Exemples d'entreprises qui l'utilisent |
|---|---|---|---|
| VMware vSphere / Cloud Foundation | virtualisation éprouvée, forte compatibilité legacy, outils de gestion vRealize. | license coûteuse, dépendance éditeur, orientation principalement IaaS. | nombreux datacenters bancaires et administrations françaises. |
| Apache CloudStack | solution open-source "tout-en-un", interface simple, support multi-hyperviseurs. | communauté plus restreinte qu'OpenStack, roadmap moins riche. | LeaseWeb, Exoscale. |
| Microsoft Azure Stack HCI | apporte les API et services Azure dans un datacenter privé, gestion unifiée via le portail Azure. | matériel validé obligatoire, dépendance Microsoft. | BMW Group, KPMG. |
| OpenStack | 100% open-source, communauté mondiale active, architecture modulaire (extensible), support des conteneurs et de multiples hyperviseurs, indépendance fournisseur. | courbe d'apprentissage, complexité opérationnelle sans outil de déploiement adapté, besoin d'une équipe d'exploitation expérimentée. | CERN, OVHcloud, Walmart Lambs, Bloomberg, Orange, Tencent. |

Depuis début 2025, on observe un accroissement de l'utilisation d'OpenStack à la suite du rachat de VMware par *BroadCom Inc.* cet alternative opensource permet de s'affranchir des licenses devenant de plus en plus couteuse. Dans les prochains posts nous verrons alors l'architecture et les différents composants d'OpenStack avant de créer notre propre infrastructure cloud.