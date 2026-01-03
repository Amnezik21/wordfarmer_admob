# WordFarmer — Site développeur (GitHub Pages)

Ce dépôt héberge le **site développeur officiel** de **WordFarmer** via **GitHub Pages**.

Il sert à :
- fournir une page publique de présentation (référencée dans la fiche Google Play),
- héberger le fichier **`app-ads.txt`** à la racine (exigence **AdMob / app-ads.txt**),
- publier des liens importants :
  - **Politique de confidentialité**
  - **Suppression de compte**

---

## 🌐 URL du site

Une fois GitHub Pages activé, le site est accessible ici :

- **Site** : `https://Amnezik21.github.io/wordfarmer_admob/`
- **app-ads.txt** : `https://Amnezik21.github.io/wordfarmer_admob/app-ads.txt`

> ⚠️ Le fichier `app-ads.txt` doit **rester à la racine** (pas dans un sous-dossier).

---

## 📌 Liens “conformité” (déjà en ligne)

- **Page de suppression de compte** : `https://amnezik21.github.io/contact_suppression_compte_wordfarmer/`
- **Politique de confidentialité** : `https://amnezik21.github.io/wordfarmer_privacy/`

Ces liens sont intégrés dans `index.html` (CTA + footer).

---

## 📁 Structure du dépôt

À la racine :
- `index.html` → page principale du site développeur
- `app-ads.txt` → fichier obligatoire AdMob (à la racine)
- `.github/workflows/static.yml` → workflow de déploiement GitHub Pages
- `README.md` → documentation (ce fichier)

---

## ✅ Configuration GitHub Pages (recommandée)

1. Ouvrir : **Settings → Pages**
2. Dans **Build and deployment** :
   - **Source** : `GitHub Actions`
3. Utiliser le workflow **Static HTML** (via GitHub Pages) ou conserver `static.yml` déjà présent.
4. Aller dans **Actions** et vérifier que le workflow termine en ✅

Une fois déployé, GitHub affiche une URL “Your site is live at …” dans **Settings → Pages**.

---

## ✅ Vérification app-ads.txt (indispensable)

Ouvrir dans un navigateur :

`https://Amnezik21.github.io/wordfarmer_admob/app-ads.txt`

Le contenu doit être **exactement** une ou plusieurs lignes au format IAB, par exemple :

