# Projet-Création-Infrastructure-Sécurisé-d'Entreprise
Afin de développe mes compétences en Réseau & Sécurité j'ai décider de créer une infrastructure Réseau complète pour une entreprise fictive afin d'apprendre l'implémentation de toutes les solutions réseau de A à Z

- Tout d'abord on va installer le logiciel EVE-NG Community Edition
![image](https://github.com/user-attachments/assets/f9b9e933-d1e4-4680-976a-bcab38dd2a64)


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
