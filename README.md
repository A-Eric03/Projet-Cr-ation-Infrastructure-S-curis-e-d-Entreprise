# Projet-Création-Infrastructure-Sécurisé-d'Entreprise
Afin de développe mes compétences en Réseau & Sécurité j'ai décider de créer une infrastructure Réseau complète pour une entreprise fictive afin d'apprendre l'implémentation de toutes les solutions réseau de A à Z

🌐 Installation de EVE-NG Community Edition
💻 Contexte
Étant équipé d’un MacBook Air avec puce M4 (architecture ARM), je ne pouvais pas installer EVE-NG localement. J’ai donc opté pour une solution alternative, en installant EVE-NG sur un ordinateur fixe sous Windows, accessible à distance.

🔐 Accès à distance via VPN
J’ai utilisé Tailscale, un VPN personnel, pour établir une connexion sécurisée entre le PC Windows et mon Mac.

L’objectif était ensuite de me connecter au PC via Remote Desktop (RDP).

Cependant, RDP n’est disponible que sur Windows 11 Pro, alors que le PC tournait sous Windows 11 Famille.

J’ai donc acheté une clé d’activation Windows 11 Pro via ce lien : https://fr.shopping.rakuten.com/offer/buy/7318179737/windows-11-pro-cle-d-activation-livraison-email-2h-licence-a-vie-facture-avec-tva.html

👤 Gestion des comptes et accès
Création d’un compte utilisateur local en plus du compte administrateur.

Configuration des machines virtuelles en réseau public pour qu’elles soient accessibles depuis tous les comptes.



  Tout les liens neccessaire à ce projets
  - VMwareWorkStation : https://www.vmware.com/go/downloadplayer
  - EVE-NG : https://www.eve-ng.net/index.php/download/#DL-COMM
  - Windows Server 2022 (free 180 jours) : https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022
  - Windows 10 : https://www.microsoft.com/en-us/software-download/windows10
  - Windows 11 : https://www.microsoft.com/en-us/software-download/windows11
  - PfSense (firewall, routage, VPN) : https://www.pfsense.org/download/
  - Kali Linux (tests de sécurité, pentesting) : https://www.kali.org/get-kali/
  - Ubuntu Server (serveur Linux) : https://ubuntu.com/download/server

  
Plan d’action – Projet Réseau d’Entreprise Virtuel

  1. Préparation de l’environnement :
    Installation de la plateforme de virtualisation (VMware ou EVE-NG)
    Organisation des fichiers ISO et des dossiers de travail
    Téléchargement des systèmes (Windows Server, Windows 10, pfSense, etc.)

  2. Création et configuration des machines virtuelles :
  Création des VMs : pfSense, Windows Server, postes clients
  Attribution des ressources (RAM, CPU, disque, cartes réseau)
  Installation des systèmes d’exploitation

  3. Mise en place de l’infrastructure réseau :
    Création des VLANs simulés
    Configuration du routage inter-VLAN via pfSense
    Attribution des plages IP par VLAN
    Mise en place du serveur DHCP/DNS

  4. Déploiement d’Active Directory :
    Installation d’AD DS sur Windows Server
    Création du domaine (ex. : entreprise.local)
    Organisation des OU (RH, IT, Compta)
    Création des comptes utilisateurs et groupes de sécurité

  5. Configuration des stratégies de groupe (GPO) :
    Application de restrictions spécifiques à chaque service
    Scripts de connexion : montage de lecteurs, restrictions d’accès
    Tests de connexion des utilisateurs

  6. Mise en place du VPN :
    Installation et configuration du serveur VPN (OpenVPN via pfSense)
    Création des certificats et comptes VPN
    Tests de connexion depuis un poste distant

  7. Tests et validation du réseau :
    Tests des accès selon les VLANs
    Vérification des droits utilisateurs et GPO
    Simulation de scénarios de connexion, blocage, autorisation

  8. Documentation et livrables :  
    Schéma réseau final (topologie complète)
    Captures d’écran de chaque étape importante
    Fiche technique et compte-rendu de configuration
    Rapport ou présentation PowerPoint du projet
