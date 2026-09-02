# Portfolio — Brayan Campion

Portfolio personnel présentant mon profil, mon parcours, mes projets et mes passions. Développé en HTML/CSS/JavaScript pur (sans framework), sur le thème visuel d'un éditeur de code.

🔗 **Site en ligne :** _à compléter avec ton lien GitHub Pages (ex : https://bray293.github.io/portfolio/)_

## Structure du site

| Page | Description |
|---|---|
| `index.html` | Accueil — présentation rapide et liens vers les autres sections |
| `about.html` | Parcours — formation, compétences, langues, expérience |
| `projects.html` | Liste des projets, avec accès aux pages détaillées |
| `passions.html` | Liste des passions, avec accès aux pages détaillées |
| `contact.html` | Formulaire de contact (via Formspree) et coordonnées |

### Pages détaillées

```
projets/
├── project-withoff.html          → Jeu de Wythoff (Java)
└── project-site-personnel.html   → Site Historium Legacy

passions/
├── passion-programmation.html
├── passion-jeux-video.html
└── passion-automobile.html
```

Chaque page projet contient une explication, des captures d'écran et un extrait de code réel. Chaque page passion a sa propre ambiance de couleur (thème CSS dédié).

## Fonctionnalités

- **Navigation** : menu avec sous-menus déroulants pour les pages projets et passions, transformé en menu hamburger sur tous les écrans
- **Images cliquables** : chaque image s'agrandit en plein écran au clic (lightbox), et se referme au reclic
- **Formulaire de contact** fonctionnel via [Formspree](https://formspree.io)
- **CV téléchargeable** directement depuis la page Contact

## Technologies utilisées

- HTML5 / CSS3 (variables CSS, Grid, Flexbox)
- JavaScript vanilla (menu hamburger, lightbox)
- Polices : Space Grotesk, IBM Plex Sans, JetBrains Mono (Google Fonts)
- Hébergement : GitHub Pages

## Voir le site en local

Aucune installation nécessaire — c'est un site statique. Il suffit d'ouvrir `index.html` dans un navigateur, ou de servir le dossier avec un petit serveur local, par exemple :

```bash
python3 -m http.server
```

puis d'aller sur `http://localhost:8000`.

## Contact

- Email : brayan.campion1@gmail.com
- GitHub : [github.com/Bray293](https://github.com/Bray293)
- LinkedIn : [brayan-campion](https://www.linkedin.com/in/brayan-campion-440994294/)

## Auteur

Brayan Campion — Développeur Junior, Rosporden (29140)
