<!-- =========================================================
     README.md — Sherbrooke RP (site web officiel)
     Repo PUBLIC : aucune info sensible ici (pas de token/clé).
     ========================================================= -->

<div align="center">

  <img src="https://cdn.discordapp.com/icons/1442003095377674414/9bf05f87fd91f1e20eafc6aa6e70ec03.webp?size=1024" alt="Logo Sherbrooke RP" width="140" />

  # 🚨 Sherbrooke RP — Site web officiel

  **Le site vitrine du serveur *Emergency Response: Liberty County* (ERLC)**
  **le plus immersif du Québec 🇨🇦 — axé sur la ville de Sherbrooke.**

  <a href="https://jacobin904.github.io/Sherbrooke-RP/">
    <img src="https://img.shields.io/badge/Voir_le_site_en_ligne-2563eb?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Site en ligne" />
  </a>
  <a href="https://discord.gg/JBND23V6q">
    <img src="https://img.shields.io/badge/Rejoindre_le_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  </a>

  <br/>

  <img src="https://img.shields.io/badge/Hébergé_sur-GitHub_Pages-222?style=flat-square&logo=github" alt="GitHub Pages" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Langue-Français-2563eb?style=flat-square" alt="Français" />
  <img src="https://img.shields.io/badge/Statut-En_ligne-16a34a?style=flat-square" alt="Statut" />

</div>

---

## 📖 À propos

**Sherbrooke RP** est un serveur de roleplay francophone sur **Roblox / Emergency Response: Liberty County (ERLC)**, recréant l'univers de la ville de **Sherbrooke (Québec)** : forces de l'ordre, services d'urgence, système judiciaire, économie, entreprises et gangs structurés.

Ce dépôt contient le **site web officiel** du serveur : une page unique (*single page*) moderne, immersive et entièrement responsive, pensée pour présenter la communauté, ses départements, ses règles et son histoire aux nouveaux venus.

> 🎮 **Code de jeu en ligne :** `SHERBRP`

---

## 🖼️ Aperçu

<div align="center">

<!-- Astuce optionnelle : ajoute un fichier preview.png à la racine pour afficher
     une vraie capture d'écran du site, puis retire les deux lignes de commentaire
     ci-dessous. Tant que le fichier n'existe pas, le logo ci-dessous s'affiche.
![Aperçu du site](preview.png)
-->

<img src="https://cdn.discordapp.com/icons/1442003095377674414/9bf05f87fd91f1e20eafc6aa6e70ec03.webp?size=1024" alt="Sherbrooke RP" width="220" />

*Identité visuelle alignée sur le logo officiel du serveur.*

</div>

---

## ✨ Ce que propose le site

### 🎭 Contenu
- **Présentation complète** du serveur et de son concept de roleplay réaliste.
- **9 atouts mis en avant** : RP structuré, staff professionnel, véhicules & équipements, radio Zello, événements, vérification sécurisée, système judiciaire, économie & entreprises, gangs & criminalité.
- **8 départements** détaillés : SQ, SPS, SPCIS, Ambulance d'Estrie, MTQ, CGA (911), Palais de Justice, Entreprises & Civils.
- **Règlement** clair, complété par des **explications en accordéon** (exemples concrets de FearRP, Metagaming, RDM/VDM…).
- **Équipe de direction** actuelle (propriétaires + développeur).
- **Historique de la direction** sous forme de **timeline** interactive (fondation → changements → rachat).
- **FAQ** et **guide « Comment rejoindre »** étape par étape.
- **Liens directs** vers les salons Discord utiles (tickets, règlement, annonces, recrutement, partenariats).

### 🛠️ Côté technique & expérience utilisateur
- 🎨 **Design premium** aux couleurs du logo (dégradés bleus, thème sombre).
- ⏳ **Preloader** animé avec barre de progression en pourcentage.
- ✨ **Particules** interactives sur canvas (effet « aimant » au survol de la souris).
- 🔦 **Halo lumineux** qui suit le curseur.
- 🔤 **Titre animé** lettre par lettre + sous-titre en *typewriter*.
- 📜 **Animations au scroll** (reveal, stagger, effets gauche/droite).
- 🧭 **Navigation sticky** avec indicateurs de progression latéraux + **menu mobile** coulissant.
- 🎴 **Cartes 3D** (effet *tilt* + *spotlight*) et **accordéons** FAQ.
- 📱 **100 % responsive** (mobile, tablette, desktop) + respect de `prefers-reduced-motion`.
- ⬆️ Bouton **retour en haut** et **scroll fluide** entre les sections.

---

## 🧱 Stack technique

| Technologie | Rôle |
|---|---|
| **HTML5** | Structure sémantique de la page |
| **CSS3** | Design, dégradés, animations, responsive (Grid / Flexbox) |
| **JavaScript (vanilla)** | Animations, particules, accordéons, navigation, preloader |
| **Font Awesome 6** | Icônes (aucun emoji dans l'interface) |
| **Google Fonts** | *Inter*, *Playfair Display*, *Cormorant Garamond*, *JetBrains Mono* |
| **GitHub Pages** | Hébergement gratuit du site |

> 💡 **Zéro framework, zéro dépendance à builder** : tout tient dans un seul fichier `index.html`.

---

## 🗂️ Structure du dépôt

```text
Sherbrooke-RP/
├── LICENSE       # Licence du code source
├── index.html    # Le site complet (HTML + CSS + JS)
└── README.md     # Ce fichier
