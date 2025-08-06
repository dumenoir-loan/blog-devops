+++
author = "Dumenoir Loan"
title = "Openstack Intro"
date = "2025-06-17"
description = "Introduction to Openstack"
categories = [
    "infrastructure"
]
tags = [
    "openstack",
    "infrastructure",
    "cloud",
]
image = "post/openstack/openstack-couverture2.png"
+++

# Qu'est ce que Openstack

Openstack est une solution open source de cloud computing. 

Lorsque l'on parle de cloud computing, il y a plusieurs concept que l'on ne peut pas manquer. Tout d'abord la **mutualisation** des ressources matériel et logiciel, permettant de réduire les coûts d'acquisition et de maintenance. l'**Élasticité**, sa capacité à ajuster dynamiquement la puissance de calcul, de stockage ou la bande passante selon la demande. Pour finir le cloud à également imposer un nouveau format de **facturation** qui est dite **à l'usage** permettant de ne payer que pour ce qui est consommé.

On distingue principalement **3 modèles** de cloud :
* Cloud public, accessible pour tous et géré par des fournisseurs tiers on peut citer comme exemple les 3 leaders, AWS (Amazon Web Services), Azure Cloud (Microsoft) et GCP (Google Cloud Provider).
* Cloud privé, il est dédié a son organisation et est géré en interne ou par un prestataire.
* Cloud hybride, ce type de cloud n'est autre que la combinaison du cloud privé et public, il permet alors de mixer la sécurité et la scalabilité.

Openstack n'est pas la seul solution de Cloud computing aujourd'hui, il existe d'autre solution tel que :
* VMware vSphere / Cloud Foundation : plate-forme propriétaire mature pour la virtualisation de serveurs et le déploiement de clouds privés ou hybrides, avec un écosystème riche (vSAN, NSX, vRealize)
* Apache CloudStack : Projet open source pour la création et la gestion de clouds IaaS. Il est comparable à OpenStack mais avec une architecture monolithique plus simple à déployer.
* Microsoft Azure Stack : Une extension "on-premises" du cloud Azure de Microsoft. Il permet de fournir des services PaaS et IaaS Azure dans son propre datacenter, en profitant de la même API qu'Azure public.

OpenStack est largement adopté par des grandes sociétés on peut citer comme exemple le CERN, Walmart ou encore OVHcloud.

Contrairement à Apache CloudStack, openstack offre une architecture micro-services. Voici une liste non exhaustive des composants principaux d'OpenStack :
* Keystone (IAM)
* Nova (Calcul)
* Neutron (Réseau)
* Cinder (Stockage en bloc)
* Swift (Stockage objet)
* Glance (Catalogue d'images)
* Horizon (Interface web)

Le principal avantage d'OpenStack est donc que l'on peut mettre à l'échelle chaque services indépendamment. Néamoins cela ajoute une complexité de mise en place de l'infrastructure. Il faut donc installer et configurer chaque service.

## Outils de déploiement

Pour palier à ce problème il existe des outils permettant de faciliter le déploiement et la configuration des services. 

* DevStack - Ensemble de scripts pour installer rapidement un environnement OpenStack complet.
* Kolla-Ansible - Déploie les services OpenStack sous forme de conteneurs Docker orchestrés par Ansible.
* TripleO (Openstack-On-Openstack) - Utilise un cloud Openstack "undercloud" pour provisionner, configurer et gérer le "overcloud" de production.

Nous verrons dans un autre post la création d'un cloud Openstack.