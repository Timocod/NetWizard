1. Présentation du projet
   1.1 Contexte
La configuration d'un réseau d'entreprise (routeurs, switchs, VLANs, adressage IP, routage inter VLAN, DHCP) est une tâche répétitive, longue et source d'erreurs lorsqu'elle est faite à la main en ligne de commande. Une faute peut rendre le réseau inutilisable, et chaque équipement oblige à retaper les mêmes commandes.
  1.2 Objectif
Développer un outil portbale, lancé depuis une clé USB, qui :
  1. Pose des questions à l'utilisateurs sur le réseau souhaité;
  2. Vérifications des réponses;
  3. Calcule le plan d'adressage;
  4. Génère la configuration de chaque équipement
  5. L'applique automatiquement sur les équipements
  6. Vérifie que le réseau fonctionne et produit un rapport
