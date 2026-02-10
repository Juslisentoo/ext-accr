# Accrocher — Extension Navigateur

**Partagez des liens vers [Accrocher](https://accrocher-psi.vercel.app) en un clic depuis votre navigateur.**

L'extension ajoute un bouton dans la barre d'outils de votre navigateur. Quand vous êtes sur une page web intéressante, cliquez dessus, choisissez une catégorie, et c'est partagé !

---

## 📥 Télécharger

| Navigateur | Fichier |
|---|---|
| **Google Chrome** | [📦 accrocher-chrome.zip](chrome/accrocher-chrome.zip) |
| **Mozilla Firefox** | [📦 accrocher-firefox.zip](firefox/accrocher-firefox.zip) |

> **Cliquez sur le lien** correspondant à votre navigateur ci-dessus, puis suivez les instructions ci-dessous.

---

## 🟢 Installation sur Google Chrome

### Étape 1 — Télécharger

Cliquez sur le lien **accrocher-chrome.zip** ci-dessus, puis sur le bouton **"Download raw file"** (icône ⬇️) sur la page GitHub.

### Étape 2 — Dézipper le fichier

1. Allez dans votre dossier **Téléchargements**
2. **Double-cliquez** sur `accrocher-chrome.zip` pour le décompresser
3. Vous obtenez un dossier `accrocher-chrome` (ou similaire)

### Étape 3 — Ouvrir la page des extensions

1. Ouvrez Chrome
2. Dans la barre d'adresse, tapez : **`chrome://extensions`** puis Entrée
3. En haut à droite, **activez le "Mode développeur"** (le bouton bascule)

> 💡 C'est normal, ce mode permet simplement de charger des extensions qui ne viennent pas du Chrome Web Store.

### Étape 4 — Charger l'extension

1. Cliquez sur **"Charger l'extension non empaquetée"** (en haut à gauche)
2. Sélectionnez le **dossier décompressé** (celui qui contient `manifest.json`)
3. Cliquez **"Sélectionner"**

### Étape 5 — C'est installé ! 🎉

L'icône 📎 apparaît dans la barre d'outils Chrome. Si vous ne la voyez pas :
1. Cliquez sur l'icône **puzzle** 🧩 (à droite de la barre d'adresse)
2. Trouvez **"Accrocher — Partager un lien"**
3. Cliquez sur l'icône **épingle** 📌 pour la garder visible

### Première utilisation

1. Cliquez sur l'icône 📎
2. Cliquez **"Se connecter avec Google"**
3. Connectez-vous avec votre compte Google habituel
4. C'est prêt ! Naviguez sur un site et cliquez sur 📎 pour le partager

> ⚠️ **Note :** À chaque mise à jour de Chrome, vous pourriez voir un message "Extensions du mode développeur désactivées". Cliquez simplement sur les 3 points → Extensions → réactivez Accrocher. C'est la seule limite de la méthode gratuite.

---

## 🦊 Installation sur Mozilla Firefox

### Étape 1 — Télécharger

Cliquez sur le lien **accrocher-firefox.zip** ci-dessus, puis sur le bouton **"Download raw file"** (icône ⬇️) sur la page GitHub.

### Étape 2 — Dézipper le fichier

1. Allez dans votre dossier **Téléchargements**
2. **Double-cliquez** sur `accrocher-firefox.zip` pour le décompresser
3. Vous obtenez un dossier `accrocher-firefox` (ou similaire)

### Étape 3 — Ouvrir la page de débogage

1. Ouvrez Firefox
2. Dans la barre d'adresse, tapez : **`about:debugging#/runtime/this-firefox`** puis Entrée

### Étape 4 — Charger l'extension

1. Cliquez sur **"Charger un module complémentaire temporaire…"**
2. Naviguez dans le **dossier décompressé**
3. Sélectionnez le fichier **`manifest.json`** (pas le dossier, le fichier à l'intérieur)
4. Cliquez **"Ouvrir"**

### Étape 5 — C'est installé ! 🎉

L'icône 📎 apparaît dans la barre d'outils Firefox.

### Première utilisation

1. Cliquez sur l'icône 📎
2. Cliquez **"Se connecter avec Google"**
3. Une fenêtre Google s'ouvre — connectez-vous
4. **Important sur Firefox** : après la connexion Google, la fenêtre se ferme. **Recliquez sur l'icône 📎** pour accéder au formulaire.
5. C'est prêt !

> ⚠️ **Note Firefox :** L'extension est "temporaire" — elle sera supprimée quand vous fermerez Firefox. Il faudra la recharger au prochain démarrage via `about:debugging`. Une version permanente pourra être disponible bientôt via le Firefox Add-ons Store (gratuit).

---

## 🔄 Mise à jour

Pour mettre à jour l'extension :

1. Retéléchargez le zip depuis cette page
2. Dézippez-le
3. **Chrome** : allez dans `chrome://extensions` → cliquez sur 🔄 (recharger) sur la carte Accrocher
4. **Firefox** : allez dans `about:debugging` → cliquez sur **"Actualiser"**

---

## ❓ FAQ

<details>
<summary><strong>L'extension ne marche pas / je vois un message d'erreur</strong></summary>

Vérifiez que vous êtes bien connecté(e) avec un compte Google autorisé sur Accrocher. Seuls les comptes invités peuvent utiliser l'extension.
</details>

<details>
<summary><strong>Je ne vois pas l'icône 📎 dans Chrome</strong></summary>

Cliquez sur l'icône puzzle 🧩 à droite de la barre d'adresse, puis épinglez "Accrocher".
</details>

<details>
<summary><strong>Chrome me dit "mode développeur désactivé"</strong></summary>

C'est un avertissement normal. Cliquez simplement sur les 3 points en haut à droite → Extensions → réactivez Accrocher. Ça n'affecte pas la sécurité.
</details>

<details>
<summary><strong>Firefox : "extension temporaire supprimée"</strong></summary>

C'est une limitation de Firefox pour les extensions non signées. Il faut la recharger via `about:debugging` après redémarrage du navigateur.
</details>

<details>
<summary><strong>Sur Firefox, rien ne se passe après la connexion Google</strong></summary>

C'est normal ! Firefox ferme le popup pendant l'authentification. Recliquez simplement sur l'icône 📎 — vous serez connecté(e).
</details>

---

## 🛡️ Confidentialité

Cette extension :
- **Ne collecte aucune donnée** personnelle
- **Ne contient pas de tracker** ni de publicité
- Communique uniquement avec votre instance Accrocher
- Le code source est ouvert et consultable ci-dessus

---

*Fait avec 💜 par l'équipe Accrocher*
