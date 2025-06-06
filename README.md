# Projet Fil Rouge - Spécialité Cybersécurité
## Sécurisation d'un hôpital contre les cyberattaques

### 🏥 Contexte du projet
**Entreprise fictive :** CHU de Ynov  
**Formation :** Ynov Informatique - Bachelor 3  
**UF :** Spécialité Cybersécurité  
**Équipe :** 3 personnes : Nils JAUDON Clement GARCIA Yann BLANC


### 📋 Description
Les hôpitaux représentent des cibles privilégiées pour les cyberattaques en raison de la nature critique et sensible de leurs données. Ce projet vise à sécuriser l'infrastructure d'un hôpital fictif contre les cybermenaces modernes.

### 🎯 Objectifs pédagogiques

#### 1. Gouvernance de la sécurité
- Élaborer une Politique de Sécurité des Systèmes d'Information (PSSI)
- Assurer la conformité avec les normes (RGPD, ISO 27001)

#### 2. Sécurité réseau
- Mise en place de mesures de protection des réseaux
- Utilisation d'outils de détection et de prévention des intrusions

#### 3. Sécurité des OS et services
- Sécurisation des serveurs et applications critiques
- Configuration sécurisée et gestion des correctifs

#### 4. Tests d'intrusion
- Réalisation de pentests sur les systèmes de sécurité
- Identification des vulnérabilités et mesures correctives

### 🔧 Technologies utilisées
- **SIEM** (Security Information and Event Management)
- **IDS/IPS** (Intrusion Detection/Prevention Systems)
- **Outils de pentest** (Nessus, OpenVAS, etc.)
- **Pare-feu** et solutions de protection réseau
- **Outils de virtualisation** (VirtualBox, GNS3)

### 📋 Tâches réalisées

#### Analyse des risques et vulnérabilités
- Identification des actifs critiques
- Scan de vulnérabilités avec Nessus/OpenVAS
- Évaluation des risques

#### Mise en place de mesures de sécurité
- Configuration de pare-feu
- Déploiement d'IDS/IPS
- Politiques d'accès strictes (2FA, gestion des rôles)

#### Protection des données
- Chiffrement des données sensibles
- Sauvegardes régulières et sécurisées
- Tests du plan de récupération

#### Gestion de crise
- Plan de réponse aux incidents
- Plan de continuité et de reprise d'activité
- Procédures d'escalade

#### Tests et validation
- Simulation d'attaques
- Tests d'intrusion
- Validation des mesures de sécurité

#### Sensibilisation
- Formation du personnel
- Présentation de sensibilisation à la cybersécurité

### 🖥️ Prérequis techniques

#### Connaissances requises
- Administration système (Windows/GNU-Linux)
- Architecture de systèmes d'information
- Services réseau (DHCP, DNS, etc.)
- Hygiène informatique
- MOOC CyberEdu ANSSI

#### Environnement technique
- **GNU/Linux :** 4 Go RAM minimum
- **Windows :** 16 Go RAM minimum
- **Outils :** VirtualBox, GNS3
- **Optionnel :** Raspberry Pi pour environnement réel

### 📁 Structure du projet

```
__Document_Architectur_Technique.pdf

__Guide_Exploitation_Infrastructure IT.pdf

__PSSI___CHYNOV.pdf

__README.md

```

### 📊 Livrables

#### Documentation technique
- **Architecture :** Définition du réseau, hosts, répartition des services
- **Configuration :** Détail des configurations système, réseau et services
- **Exploitation :** Guide d'utilisation des outils et services
- **PSSI :** Politique de sécurité complète

### 🎖️ Bonus
Attestation de suivi SecNumAcadémie avec succès de 4 modules du MOOC ANSSI et scores obtenus.

### ⚡ Installation et déploiement

1. **Cloner le repository**
   ```bash
   git clone [https://github.com/M1ck3y-ru/PROJET_FILE_ROUGE.git]
   cd PROJET_FILE_ROUGE
   ```

2. **Configuration de l'environnement**
   ```bash
   # Configuration des machines virtuelles
   # Voir docs/installation/setup-guide.md
   ```

3. **Déploiement des services**
   ```bash
   # Scripts de déploiement automatisé
   ./scripts/deploy-security-stack.sh
   ```

### 📈 Évaluation
L'évaluation porte sur :
- Qualité technique des solutions déployées
- Conformité aux bonnes pratiques de sécurité
- Documentation et architecture
- Présentation orale et démonstration
- Capacité à répondre aux questions techniques

### 👥 Équipe
- **Membre 1 :** [BLANC YANN] - [Bachelor 3 Cybersécurité]
- **Membre 2 :** [GARCIA CLEMENT] - [Bachelor 3 Cybersécurité]
- **Membre 3 :** [NILS JAUDON] - [Bachelor 3 Cybersécurité]

### 📞 Contact
Pour toute question concernant ce projet, contactez l'équipe via [clement.garcia@ynov.com].

---
**Projet réalisé dans le cadre de la formation Bachelor 3 Informatique - Spécialité Cybersécurité - Ynov Campus**
