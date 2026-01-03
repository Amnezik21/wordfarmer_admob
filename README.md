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
google.com, pub-3399222389109799, DIRECT, f08c47fec0942fa0


### Erreurs fréquentes
- ❌ fichier déplacé dans un dossier
- ❌ extension incorrecte (ex: `app-ads.txt.txt`)
- ❌ contenu entouré d’HTML ou de texte additionnel
- ❌ URL qui redirige bizarrement ou renvoie 404

---

## 🎯 Intégration Google Play Console

Dans la fiche Play Store :
- **Paramètres de la fiche Play Store → Coordonnées → Site Web**
  - renseigner : `https://Amnezik21.github.io/wordfarmer_admob/`

Cela permet à Google/AdMob de retrouver le fichier `app-ads.txt`.

---

## ✏️ Modifier le contenu du site

Le site est volontairement **sans dépendances** (HTML/CSS “pur”) pour être robuste.

Pour modifier :
1. Ouvrir `index.html`
2. Modifier le texte / liens / sections
3. Commit sur `main`
4. Le workflow Pages redéploie automatiquement

> Conseil : **ne modifie pas** l’emplacement de `app-ads.txt`.

---

## 🧩 Roadmap “site dev” (optionnel)
Idées simples, sans complexifier :
- ajouter un lien direct vers la page Play Store (quand publique)
- ajouter 2–3 screenshots du jeu (optimisés en WebP)
- ajouter une section “FAQ support” (connexion / pubs / sauvegarde)
- ajouter un bouton “Nous contacter” (mailto)

---

## 📄 Licence
Ce dépôt contient une page statique et de la documentation.  
Utilisation interne liée au projet WordFarmer.


