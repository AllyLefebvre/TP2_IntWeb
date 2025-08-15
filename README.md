# 🩸 TP2 - FRIDAY THE 13TH — Site Vitrine

> *« Au bord du lac, la nuit tombe… et le masque se relève. »*  
Un site vitrine immersif dédié à la saga culte **Friday the 13th**, réalisé en **HTML5** + **SASS**.  
Ambiance sombre, visuels saignants, UX tranchante. 🔪

---

## 🕯️ Aperçu

- Fiches **tous les films** (année, synopsis, casting, affiche, BA)
- **Galerie** d’affiches & moments cultes

---

## 🧱 Stack & outils

- **HTML5** sémantique  
- **SASS (SCSS)** modulaires (variables, mixins, partials)  
- **CSS Grid / Flexbox** responsive

---

## 🗂️ Architecture

```
friday-the-13th/
│
├─ index.html              # Accueil
├─ tournage.html           # Fait divers sur le tournage         
│
├─ /sass
│  ├─ style.scss           # Point d'entrée
│  └─ style.css            # CSS generer
│
├─ /images                 # Images pour les deux pages web 
│
└─ /fonts                  # Font pour le theme
```

---

## ⚙️ Installation

```bash
# 1) Cloner
git clone https://github.com/AllyLefebvre/TP2_IntWeb.git
cd friday-the-13th

# 2) Compiler (watch)
sass sass/main.scss css/main.css --watch

# 3) Lancer Live server
```

---

## 🧭 Navigation & pages

- **Accueil** : hero plein écran, CTA « Explorer la saga »
- **Tournage** : Fait divers avec images et présentation de la direction artistique

---

## 📜 Licence

```
MIT License — Faites-en bon usage et citez l’auteur.
```

---

## 🧑‍💻 Auteur

- **Allyson Lefebvre** — Développeuse Web
- **Jérémy Rioux** — Développeur Web

---

> *« Chuuut… entends-tu l’eau clapoter ? Mieux vaut compiler avant la nuit. »* 🌙
