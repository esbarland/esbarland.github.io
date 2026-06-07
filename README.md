# Portfolio — Estéban Barland

Portfolio personnel d'Estéban Barland, développeur web fullstack **PHP / Angular** en montée en compétences sur **Java Spring Boot**.

🔗 **Site en ligne** : https://esbarland.github.io

## 🛠️ Stack

Site statique (HTML / CSS / JS), basé sur le template [Read Only](https://html5up.net/read-only) de HTML5 UP (licence CCA 3.0).

## 🚀 Lancer en local

Aucune dépendance à installer. Ouvre simplement `index.html` dans un navigateur, ou sers le dossier :

```bash
# avec Python
python3 -m http.server 8000
# puis ouvre http://localhost:8000
```

## 📦 Déploiement sur GitHub Pages

1. Crée un dépôt nommé **`esbarland.github.io`** sur GitHub (ce nom exact sert l'URL racine) et pousse ce code :
   ```bash
   git remote add origin https://github.com/esbarland/esbarland.github.io.git
   git push -u origin main
   ```
2. Sur GitHub : **Settings → Pages → Build and deployment → Source : GitHub Actions**.
3. À chaque `push` sur `main`, le workflow [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) publie automatiquement le site sur `https://esbarland.github.io`.

> Le nom du dépôt `esbarland.github.io` est ce qui donne l'URL racine. Pour une URL en sous-dossier (`…/portfolio/`), nomme le dépôt `portfolio`.

## ✏️ Personnalisation

- **Contenu** : tout est dans [`index.html`](index.html) (sections *À propos*, *Compétences*, *Projets*, *Contact*).
- **Projets** : les 3 projets sont des exemples — remplace les titres, descriptions et liens (`https://github.com/esbarland`) par tes vrais dépôts.
- **Images** : remplace `images/avatar.jpg`, `images/banner.jpg`, `images/pic01-03.jpg`.
- **Formulaire de contact** : GitHub Pages n'a pas de back-end. Crée un endpoint gratuit sur [Formspree](https://formspree.io) et remplace l'`action` du `<form>` dans `index.html`.
- **Liens sociaux** : vérifie/mets à jour les URLs GitHub et LinkedIn dans le header et la section Contact.

## 📄 Licence

Le code du template est sous licence [CCA 3.0](https://html5up.net/license) (HTML5 UP). Le contenu et les projets présentés appartiennent à Estéban Barland.
