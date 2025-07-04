
# 🔒 **Smart Lock**  
*Un système de verrouillage intelligent pour la sécurité domestique*

Ce projet, développé par Hamza Chehaibi, ingénieur en systèmes embarqués, réseaux et télécommunications, propose une solution de verrouillage intelligent basée sur une plateforme embarquée. Il combine capteurs, communication sans fil et authentification pour sécuriser une porte de manière autonome et connectée.

---

## 🧠 **Présentation du Projet**  
- 🎓 **Auteur** : Hamza Chehaibi, ingénieur en systèmes embarqués, réseaux et télécommunications.  
- 📅 **Date** : Dernière mise à jour : 04/07/2025, 17:07 CEST.  
- 🔐 **Objectif** : Développer un système de verrouillage intelligent avec authentification sécurisée et contrôle à distance pour des applications domestiques ou professionnelles.  

Ce projet met en œuvre des concepts de systèmes embarqués et de communication IoT pour une sécurité moderne.

---

## ✨ **Fonctionnalités**  
- 🔑 **Authentification biométrique** : Reconnaissance d’empreintes digitales ou code PIN.  
- 📡 **Connexion Wi-Fi** : Contrôle à distance via une application mobile.  
- 🚨 **Alerte de sécurité** : Notification en cas de tentative d’intrusion.  
- ⏰ **Journal d’accès** : Enregistrement des entrées/sorties.  
- 🔋 **Mode basse consommation** : Optimisation pour les systèmes embarqués.  

---

## 🛠️ **Prérequis**  
Pour faire fonctionner le projet, assurez-vous d’avoir :  
- **Matériel** :  
  - Microcontrôleur (ex. ESP32 ou Arduino avec module Wi-Fi).  
  - Capteur d’empreintes digitales (ex. AS608).  
  - Servo-moteur ou verrou électromagnétique.  
- **Logiciels** :  
  - **Arduino IDE** ou **PlatformIO** pour le développement embarqué.  
  - **Python 3.x** (pour l’interface ou le serveur, si applicable).  
- **Bibliothèques** :  
  - `ESPAsyncWebServer` (pour ESP32).  
  - `Adafruit_Fingerprint` (pour le capteur d’empreintes).  
- **Réseau** : Connexion Wi-Fi stable.  

---

## 🚀 **Installation et Mise en Marche**  
### Étapes :  
1. **Cloner le dépôt** :  
   ```bash  
   git clone https://github.com/HaMzaCheh/Smart-Lock.git  
   cd Smart-Lock  
    ````

2. **Installer les dépendances** :

   ```bash
   pip install -r requirements.txt  
   ````

   *(Créez un fichier `requirements.txt` avec les bibliothèques Python si nécessaire.)*
3. **Configurer le matériel** :

   * Connectez le capteur d’empreintes, le servo-moteur et le microcontrôleur selon le schéma fourni.
   * Mettez à jour les identifiants Wi-Fi dans `config.h`.
4. **Compiler et téléverser le code** :

   * Ouvrez le projet dans Arduino IDE ou PlatformIO.
   * Sélectionnez votre carte (ex. ESP32) et téléversez le code.
5. **Lancer le système** :

   * Branchez l’alimentation et testez l’authentification locale.

---

## 🖥️ **Utilisation**

* **Authentification locale** : Placez votre empreinte sur le capteur ou entrez un code PIN via un clavier connecté.
* **Contrôle à distance** : Utilisez l’application mobile (à développer) ou accédez à l’IP locale (ex. `192.168.1.x`) pour déverrouiller.
* **Consultation du journal** : Vérifiez les logs via l’interface série ou une API (si implémentée).
* **Arrêt d’urgence** : Déconnectez l’alimentation ou utilisez un interrupteur dédié.

---

## 🧩 **Architecture et Fonctionnement**

* **Matériel** : Un microcontrôleur gère le capteur d’empreintes et le servo-moteur.
* **Logiciel** : Code embarqué pour l’authentification et un serveur léger pour la communication Wi-Fi.
* **Flux** : Capteur → Vérification → Action (verrouillage/déverrouillage) → Notification.

---

## 🎥 **Simulation / Démo**

* Testez avec une empreinte enregistrée pour déverrouiller le verrou.
* Simulez une connexion Wi-Fi avec un smartphone pour un contrôle à distance.
* Captures d’écran ou vidéos disponibles dans le dossier `demo/` (à ajouter).

---

## 🤝 **Contribution**

Les contributions sont les bienvenues !

1. Forkez le dépôt :

   ```bash
   git clone https://github.com/HaMzaCheh/Smart-Lock.git  
   ```
2. Créez une branche :

   ```bash
   git checkout -b nouvelle-fonctionnalite  
   ```
3. Soumettez une pull request après tests.

---

## 📄 **Licence**

Distribué sous **licence MIT**. Voir [LICENSE](LICENSE) pour détails.

---

## 👨‍💻 **Auteur**

* **Hamza Chehaibi** – Ingénieur en systèmes embarqués, réseaux et télécommunications.

---

## 📬 **Contact**

* 🌐 GitHub : [https://github.com/HaMzaCheh](https://github.com/HaMzaCheh)
* 📧 Email : [contactchehaibi@gmail.com](mailto:contactchehaibi@gmail.com)

---

## 🙏 **Remerciements**

Merci d’explorer ce projet ! Vos retours et suggestions sont précieux. Contactez-moi pour des collaborations ou des améliorations. 🎉🔧

---

