# 👨‍💼 Guide Administrateur – Système de Gestion Clinique

Ce document décrit les responsabilités, fonctionnalités et bonnes pratiques associées au rôle **Administrateur** du système de gestion clinique *Clinique Rabat*.

---

## 🎯 Rôle de l’Administrateur

L’administrateur est responsable de la gestion globale du système.  
Il dispose d’un accès complet aux fonctionnalités de la plateforme et assure :

- la gestion des utilisateurs et des rôles,
- l’administration des patients,
- la supervision de l’activité de la clinique,
- la sécurité, l’audit et la configuration du système.

---

## 🔐 Connexion au système

1. Accéder à la page de connexion
2. Saisir les identifiants administrateur
3. Redirection automatique vers le **tableau de bord administrateur**

---

## 📊 Tableau de bord (Dashboard)

### Vue d’ensemble
Le tableau de bord fournit une vision globale de l’activité de la clinique :

- **Statistiques en temps réel** : patients, rendez-vous, consultations
- **Graphiques** : évolution des activités, répartition par service
- **Alertes** : notifications importantes et actions en attente

### Fonctions principales
- Suivi des indicateurs clés
- Monitoring de l’activité des médecins
- Accès rapide aux fonctionnalités critiques

---

## 👥 Gestion des utilisateurs

### Consultation des utilisateurs
- Liste complète des comptes (administrateurs, médecins, secrétaires)
- Filtrage par rôle et statut (actif / inactif)
- Recherche rapide par nom ou email

### Création d’un utilisateur
1. Cliquer sur **Ajouter un utilisateur**
2. Renseigner :
   - informations personnelles (nom, prénom, email, téléphone)
   - rôle (ROLE_ADMIN, ROLE_MEDECIN, ROLE_SECRETAIRE)
   - mot de passe temporaire
3. Valider la création

### Modification et suivi
- Mise à jour des informations utilisateur
- Consultation du profil détaillé
- Historique des actions et connexions
- Gestion des permissions associées

---

## 🏥 Gestion des patients

### Consultation des patients
- Recherche par nom, numéro de dossier ou date d’inscription
- Filtres avancés (médecin traitant, âge, statut)
- Tri par date ou dernière consultation

### Création d’un patient
1. Accéder au formulaire **Nouveau patient**
2. Renseigner :
   - informations personnelles
   - coordonnées
   - données médicales (antécédents, allergies, groupe sanguin)
   - médecin traitant
3. Valider l’enregistrement

### Dossier patient
- Historique médical et consultations
- Gestion des rendez-vous
- Suivi des factures et paiements

---

## 📈 Statistiques et rapports

### Rapports disponibles
- Activité quotidienne et périodique
- Performance des médecins
- Indicateurs financiers
- Analyse des tendances

### Export des données
- PDF : rapports synthétiques
- Excel : données exploitables
- Graphiques personnalisables

---

## 💬 Messagerie interne

- Communication entre utilisateurs
- Messages individuels ou de groupe
- Notifications en temps réel
- Historique des échanges

---

## ⚙️ Configuration du système

### Paramètres généraux
- Informations de la clinique
- Paramètres de sécurité
- Gestion des notifications

### Gestion des rôles et permissions
- Création de rôles personnalisés
- Attribution fine des droits
- Audit régulier des permissions

---

## 🔍 Surveillance et audit

### Logs d’activité
- Connexions des utilisateurs
- Actions critiques (création, modification, suppression)
- Tentatives d’accès non autorisées

### Sécurité
- Détection d’actions suspectes
- Alertes de sécurité
- Traçabilité complète des opérations

---

## 🚨 Sauvegarde et gestion des incidents

### Gestion des incidents
1. Identification du problème
2. Évaluation de l’impact
3. Application des procédures de récupération
4. Communication aux utilisateurs concernés

### Sauvegarde et restauration
- Sauvegardes automatiques
- Procédures de restauration
- Tests périodiques de récupération

---

## 🔐 Bonnes pratiques de sécurité

- Politique de mots de passe stricte
- Principe du moindre privilège
- Audit régulier des accès
- Déconnexion automatique des sessions
- Authentification JWT sécurisée

---

## 🔗 Références techniques

### Sécurité
- Authentification JWT
- Spring Security (RBAC)
- Hachage des mots de passe
- Validation des données côté frontend et backend

### Entités principales
- **Utilisateur** : gestion des comptes et rôles
- **Patient** : dossier médical et informations personnelles
- **HistoriqueAction** : traçabilité des actions
- **Message** : communication interne

---

> **Note importante** :  
> Toutes les actions administrateur sont tracées et auditables afin de garantir la sécurité et l’intégrité du système.
