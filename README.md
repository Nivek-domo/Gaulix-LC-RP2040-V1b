Version : Bêta. Elle est opérationnelle, mais proposée à titre de tests pour ses acquéreurs, pour le moment …

Résumé du projet

Ce projet vise à concevoir une carte basée sur le RP2040 LoRa, inspirée du modèle Waveshare, mais optimisée pour des performances accrues et une meilleure stabilité. L’objectif est d’offrir une solution modulaire et performante pour des applications LoRa à faible coût.

Caractéristiques principales :

Microcontrôleur : RP2040 et mémoire additionnel
Module LoRa : Version optimisée avec un véritable étage radio, incluant un TCXO pour une meilleure stabilité en fréquence. Avec le Ebyte e22-900m30s
Puissance de sortie : Jusqu’à 30dBm (1W), pouvant être bridée à 27dBm (0,5W) pour rester dans la légalité.
Alimentation :
Entrée 5V via USB-C (H13)
Possibilité d’alimentation via batterie lithium (H14) pour une autonomie accrue.
Interfaces accessibles :
I2C pour capteurs divers
UART pour GPS ou autres modules de communication
SPI pour Ethernet (W5500) ou écrans e-paper
GPIO analogiques et numériques
Firmware : Compatible avec un firmware custom pour maximiser les performances et les options de configuration.
Options d’alimentation autonome :

Panneau solaire + régulateur de tension à 5 V.
Batterie lithium avec gestion de charge intégrée.
Options de connectivité réseau :

Connexion directe au smartphone via OTG USB-C
Extension réseau via module Ethernet W5500
Choix du module LoRa : E22-900M30S

Cette carte est idéale pour une installation en point haut et un usage longue durée sans maintenance fréquente. Son coût maîtrisé et sa modularité en font un choix optimal pour les expérimentateurs LoRa et les radioamateurs souhaitant un réseau performant et fiable.

Ses caractéristiques:

Microprocesseur	RP2040
Partie LoRa	
Module	Ebyte 850~930 MHz E22-900M30S
Puissance max	30 dBm
Sensibilité	-150 dBm
TCXO	Oui
Alimentation de la carte	
Par port USB-C	Oui
Directe	5 Volts (5,5 Volts Max) Bornier à Vis
Batterie	un élément lithium 2500mA/H Bornier à Vis

Connectivité

Wifi	Non
Bluetooth	Non
USB	Oui type C
UART 1	Disponible sur broche Dupont
UART 2	Disponible sur broche Dupont
I2C	Disponible sur broche Dupont
SPI	Disponible sur broche Dupont
GPIO Disponible	3 x entrée Analogique
2 x entrée ou sortie numérique
Ethernet	Compatible carte W5500 sur le bus SPI à ajouter.
Fonctionnalités

Alimentation	Entrée fixe 5 Volts // USB C
Gestion panneau solaire	Non
Gestion batterie	Chargeur simple élément
POE	En développement
Firmware

Meshtatic	Version Bêta officielle en cours	Custom
