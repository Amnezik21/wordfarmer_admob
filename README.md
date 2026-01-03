# WordFarmer — Site développeur (GitHub Pages)

Ce dépôt héberge le **site développeur officiel** de **WordFarmer** via **GitHub Pages**.

Objectifs :
- page publique de présentation (référencée dans la fiche Google Play),
- liens de conformité (confidentialité + suppression de compte),
- hébergement du fichier **`app-ads.txt`** à la racine (exigence AdMob).

---

## 🌐 Liens officiels

- **Google Play (WordFarmer)** : https://play.google.com/store/apps/details?id=com.wordfarmers.jeu  
- **Page Facebook** : https://www.facebook.com/profile.php?id=61580777663836  
- **Politique de confidentialité** : https://amnezik21.github.io/wordfarmer_privacy/  
- **Suppression de compte** : https://amnezik21.github.io/contact_suppression_compte_wordfarmer/

---

## ✅ URL GitHub Pages

Une fois GitHub Pages activé, le site est accessible ici :

- **Site** : `https://Amnezik21.github.io/wordfarmer_admob/`
- **app-ads.txt** : `https://Amnezik21.github.io/wordfarmer_admob/app-ads.txt`

> Le fichier `app-ads.txt` doit **rester à la racine** (pas dans un sous-dossier).

---

## 🧩 Contenu du dépôt

À la racine :
- `index.html` → page principale (présentation + liens)
- `app-ads.txt` → fichier obligatoire AdMob (racine)
- `.github/workflows/static.yml` → workflow de déploiement GitHub Pages
- `Admin.png` → avatar (affiché dans le header)
- `README.md` → documentation (ce fichier)

---

## 🚀 Déploiement (GitHub Pages)

1. Ouvrir : **Settings → Pages**
2. Dans **Build and deployment** :
   - **Source** : `GitHub Actions`
3. Vérifier dans **Actions** que le workflow termine en ✅

---

## 🔍 Vérification app-ads.txt (indispensable)

Ouvrir dans un navigateur :

`https://Amnezik21.github.io/wordfarmer_admob/app-ads.txt`

Le contenu doit être strictement conforme au format IAB, par exemple : google.com, pub-3399222389109799, DIRECT, f08c47fec0942fa0 .


Erreurs fréquentes :
- fichier déplacé dans un dossier,
- extension incorrecte (`app-ads.txt.txt`),
- contenu entouré d’HTML/texte,
- URL en 404 ou redirection non voulue.

---

## 🎯 Intégration Google Play Console

Dans la fiche Play Store :
- **Paramètres de la fiche Play Store → Coordonnées → Site Web**
  - renseigner : `https://Amnezik21.github.io/wordfarmer_admob/`

---

## ✏️ Modifier le site

Le site est volontairement **sans dépendances** (HTML/CSS pur) :
1. Modifier `index.html`
2. Commit sur `main`
3. Le déploiement se fait automatiquement via GitHub Actions



