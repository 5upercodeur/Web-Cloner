# 🤖 SCAMA SYSTEM v10.0
## Cloneur de sites web avancé + Injection Telegram Premium

---

## 📋 DESCRIPTION

**BlackHatMan Phishing System** est un outil de clonage de sites web avancé qui permet de copier fidèlement n'importe quelle page web avec tous ses assets (CSS, JS, images, polices, vidéos) et d'injecter automatiquement un système de capture de données via Telegram.

⚠️ **AVERTISSEMENT LÉGAL**  
Ce script est fourni à des fins éducatives uniquement. L'utilisation de ce script pour des activités illégales est strictement interdite. L'utilisateur est seul responsable de l'usage qu'il fait de cet outil.

---

## ✨ FONCTIONNALITÉS

| Catégorie | Fonctionnalités |
|-----------|-----------------|
| **Clonage** | Copie intégrale HTML/CSS/JS, Images (jpg, png, gif, svg, webp, ico), Polices (woff, woff2, ttf, eot, otf), Vidéos/Audios, Documents (pdf, xml, json), Support srcset responsive, Extraction backgrounds CSS |
| **Injection Telegram** | Capture automatique des formulaires, Envoi instantané vers bot, Détection OS/Navigateur, Capture IP, Support 2FA, Détection champs bancaires (cartes, IBAN), Messages stylisés Markdown |
| **Serveur** | Serveur HTTP intégré, Accès local instantané, Multi-plateforme |

---

## 📚 MANUEL D'UTILISATION COMPLET

### 1️⃣ INSTALLATION

```bash
# Vérifier Python
python --version  # Python 3.7+ requis

# Installer les dépendances
pip install requests beautifulsoup4

2️⃣ CRÉATION DU BOT TELEGRAM
Étape	Action
1	Ouvrez Telegram et cherchez @BotFather
2	Envoyez /newbot
3	Donnez un nom à votre bot (ex: MonBotPhishing)
4	Donnez un username unique se terminant par bot
5	Copiez le TOKEN (ex: 1234567890:ABCdefGHIjklMNOpqrsTUVwxyz)
6	Envoyez un message à votre bot
7	Visitez https://api.telegram.org/botVOTRE_TOKEN/getUpdates
8	Récupérez le chat_id dans la réponse JSON

3️⃣ UTILISATION DU SCRIPT
# Lancement
python site_cloner.py

Déroulement interactif :
============================================================
  🤖 BLACKHATMAN PHISHING SYSTEM v10.0
============================================================

🌐 URL du site à cloner: https://www.exemple.com

📁 Dossier (défaut: exemple_com): mon_site

============================================================
  🤖 CONFIGURATION TELEGRAM
============================================================

🤖 Token: 1234567890:ABCdefGHIjklMNOpqrsTUVwxyz
📱 Chat ID: 123456789

[*] Test de connexion... ✅ Bot connecté!
[*] Injection phishing... ✅ Page injectée!

============================================================
🚀 Lancer le serveur de test ? (o/n): o

📊 DONNÉES CAPTURÉES
Informations système
🌍 IP - Adresse publique de la victime

💻 OS - Windows, macOS, Linux, Android, iOS

🌐 Navigateur - Chrome, Firefox, Safari, Edge

🕐 Horodatage - Date et heure précises

Données formulaire
📧 Email / Login

🔑 Mot de passe

📱 Code 2FA

💳 Carte bancaire (numéro, expiration, CVV)

🏦 IBAN / BIC

### 📁 STRUCTURE DU DOSSIER CLONÉ
mon_site_clone/
├── index.html          # Page injectée
├── css/                # Feuilles de style
├── js/                 # Scripts
├── images/             # Images
├── fonts/              # Polices
├── videos/             # Vidéos
├── audios/             # Audios
├── docs/               # PDF, documents
├── data/               # JSON, XML
└── assets/             # Autres fichiers

🛡️ RECOMMANDATIONS DE SÉCURITÉ
✅ Utilisez un VPN pour masquer votre IP

✅ Testez uniquement sur vos propres sites

✅ Ne partagez jamais vos tokens Telegram

✅ Supprimez les fichiers après test

✅ Utilisez des machines virtuelles pour l'isolation

👨‍💻 AUTEUR
BlackHatMan - Supercodeur 2050

Cloneur de sites ultime

Injection Telegram premium

Capture de données avancée

⚖️ AVERTISSEMENT FINAL
Ce script est fourni à des fins éducatives et de test de sécurité. L'auteur décline toute responsabilité concernant l'utilisation illégale de cet outil. Respectez les lois en vigueur dans votre pays.

Utilisez ce script de manière responsable et éthique.

📞 SUPPORT
GitHub : Issues sur le dépôt

Telegram : @joskozvvz

*© 2026 JOSK0 - Tous droits réservés*
