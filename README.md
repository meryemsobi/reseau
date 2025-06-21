# 🌐 Projet Réseau : Configuration d’une infrastructure avec IP, DHCP, Routage et DNS

## 📋 Présentation

Ce projet a été réalisé dans le cadre de mon **parcours universitaire en informatique** (BUT Informatique, 1ère année).  
L’objectif principal était de **concevoir et configurer une infrastructure réseau complète**, en utilisant des outils de simulation.

Le fichier `.mar` correspond à une **topologie réseau conçue avec Marionnet**, un simulateur de réseaux virtuels.

## 🛠️ Objectifs pédagogiques

- Comprendre et appliquer les concepts fondamentaux des **réseaux informatiques**
- Mettre en œuvre les protocoles **IP, DHCP, DNS** et **le routage**
- Manipuler des machines virtuelles et configurer manuellement les services réseau
- Tester la **connectivité et les résolutions de noms** entre différents sous-réseaux

## 📁 Contenu du projet

- `ip_dhcp_routage_dns.mar` : fichier de topologie Marionnet contenant toute la configuration réseau

## 🔧 Fonctionnalités implémentées

✅ **Attribution automatique d’adresses IP** via un serveur **DHCP**  
✅ **Configuration de plusieurs sous-réseaux** avec des **routes statiques**  
✅ **Serveur DNS local** pour la résolution de noms internes  
✅ **Tests de connectivité** entre les différentes machines virtuelles  
✅ Configuration manuelle des **interfaces réseau** et des **tables de routage**

## 🖥️ Outils utilisés

- 🧪 **Marionnet** – simulateur de réseaux virtuels basé sur OCaml
- 🐧 **GNU/Linux (Debian)** – pour l’ensemble des machines simulées
- 📝 **Fichiers de configuration** système (interfaces, resolv.conf, dhcpd.conf…)

## 🚀 Comment utiliser le projet

1. Ouvrir **Marionnet** sur un système compatible (Debian recommandé)
2. Charger le fichier `ip_dhcp_routage_dns.mar`
3. Lancer les machines virtuelles selon le plan de topologie
4. Vérifier :
   - que les machines reçoivent une IP automatiquement
   - que la communication entre sous-réseaux fonctionne
   - que les noms de domaine internes sont bien résolus

> 💡 Le projet est totalement autonome et peut être reproduit sans accès internet.

## 📌 Remarques

Ce projet a été conçu à des **fins d'apprentissage**.  
Il constitue une base pour comprendre la structure d’un **réseau local professionnel**.  
Il peut être étendu avec :
- des services supplémentaires (serveur Web, FTP…)
- du **NAT** ou **pare-feu** (iptables)
- ou une interface graphique de gestion

## 🏁 Projet universitaire

- 📍 IUT d'Orsay – BUT Informatique, 1ère année  
- 🗓️ Finalisé en **avril 2024**  
- 👨‍💻 Réalisé en binôme 

