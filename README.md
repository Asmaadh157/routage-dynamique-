Projet de Routage Dynamique avec le protocole RIP
Ce projet met en œuvre le protocole de routage dynamique RIP (Routing Information Protocol) au sein d’un réseau composé de trois routeurs interconnectés.  
L’objectif principal est de permettre la communication entre plusieurs réseaux locaux (LAN) en utilisant un protocole de routage automatique, sans configuration manuelle des routes.

Le protocole RIP a été choisi pour sa simplicité de configuration et sa capacité à propager automatiquement les tables de routage à travers les routeurs.  
Chaque routeur connaît ainsi les chemins vers les réseaux distants grâce à l’échange périodique des informations de routage.

Architecture du réseau
La topologie est organisée de la manière suivante :

- **Router0** relie le premier réseau local contenant **PC0** et **PC1**.  
- **Router1** joue le rôle de **routeur central**, interconnectant les trois routeurs.  
- **Router3** relie un troisième réseau local contenant **PC4** et **PC5**.  
- Chaque routeur est connecté à un **switch** qui dessert les postes clients.  
- Les liens entre les routeurs sont établis via des interfaces **GigabitEthernet**.
