# Maison Intelligente

## Description

Ce projet consiste en la conception et la réalisation d'une **maison intelligente (Smart Home)** basée sur la carte ESP32, permettant d'intégrer plusieurs fonctionnalités de sécurité, de surveillance et d'automatisation.

Le système combine différents capteurs et actionneurs afin de surveiller l'environnement de la maison, détecter les situations dangereuses et faciliter la gestion des accès.

Il permet notamment la détection des incendies avec envoi automatique d'alertes par e-mail via le protocole SMTP, la surveillance de la température et de l'humidité avec stockage des données sur un serveur web, ainsi que le contrôle intelligent de l'ouverture d'une porte grâce à la reconnaissance faciale.

L'objectif principal est de proposer une solution connectée améliorant la sécurité, le confort et l'autonomie d'une habitation moderne.

## Technologies utilisées

### ESP32

Microcontrôleur principal du système, assurant la collecte des données des capteurs et le contrôle des actionneurs.

### IoT (Internet des Objets)

Technologie permettant la connexion et l'échange de données entre les différents composants du système.

### Capteur de flamme

Utilisé pour détecter la présence d'un feu ou d'une flamme dans la maison.

### Capteur DHT11

Utilisé pour mesurer la température et l'humidité de l'environnement.

### Protocole SMTP

Utilisé pour envoyer automatiquement des e-mails d'alerte en cas de détection d'incendie.

### Protocole HTTP

Utilisé pour transmettre les données vers un serveur web.

### Serveur Web / Base de données

Utilisé pour stocker et consulter l'historique des mesures environnementales.

### Caméra avec reconnaissance faciale

Utilisée pour identifier les personnes devant la porte.

### Servo-moteur

Utilisé pour commander l'ouverture et la fermeture automatique de la porte.

### Buzzer et LED rouge

Utilisés comme système d'alerte local en cas de danger.

## Fonctionnalités principales

### Détection automatique d'incendie

Le capteur de flamme détecte la présence d'un feu ou d'une flamme dans la maison.

### Alerte locale en cas de danger

Activation d'un buzzer sonore et allumage d'une LED rouge pour avertir immédiatement les occupants.

### Envoi d'alertes par e-mail

L'ESP32 envoie automatiquement un message d'alerte au propriétaire via le protocole SMTP lorsqu'un incendie est détecté.

### Surveillance de la température et de l'humidité

Le capteur DHT11 mesure en continu les conditions environnementales de la maison.

### Stockage des données environnementales

Les mesures collectées sont envoyées vers un serveur web et enregistrées dans une base de données afin de conserver un historique.

### Consultation des données à distance

Possibilité de visualiser l'évolution de la température et de l'humidité à travers le serveur web.

### Reconnaissance faciale pour le contrôle d'accès

Identification des personnes devant la porte grâce à une caméra.

### Ouverture automatique de la porte

Activation du servo-moteur lorsque la personne est reconnue et autorisée.

### Amélioration de la sécurité et du confort

Automatisation des tâches quotidiennes et surveillance intelligente de l'habitation.

## Captures d'écran

### Architecture du projet

<img src="architecture%20de%20projet.png" width="350">

### Détection d'une menace d'incendie

<img src="Menace%20d'incendie.png" width="350">

### Surveillance de la température

<img src="temperature.png" width="350">

### Gestion des accès

<img src="gestion%20d'acces.png" width="350">
