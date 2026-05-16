# 📱 Ayman — PWA (Application installable)

## Qu'est-ce que c'est ?

Votre site **Ayman** transformé en **Progressive Web App** (PWA) — installable comme une vraie app sur :
- ✅ **PC Windows / Mac / Linux** (via Chrome, Edge)
- ✅ **Android** (via Chrome)
- ✅ **iPhone / iPad** (via Safari)

---

## 🚀 Comment déployer (mettre en ligne)

> **Important** : La PWA nécessite d'être hébergée en ligne (HTTPS) pour fonctionner. Voici les options gratuites :

### Option 1 — GitHub Pages (recommandé, gratuit)
1. Créez un compte sur [github.com](https://github.com)
2. Créez un nouveau dépôt (`ayman-site`)
3. Uploadez tous les fichiers du dossier `ayman-pwa/`
4. Allez dans **Settings > Pages > Deploy from branch > main**
5. Votre site sera sur : `https://votre-pseudo.github.io/ayman-site`

### Option 2 — Netlify (glisser-déposer, 30 secondes)
1. Allez sur [netlify.com](https://netlify.com)
2. Faites glisser le dossier `ayman-pwa/` dans la zone de dépôt
3. C'est en ligne immédiatement !

### Option 3 — Vercel
1. Allez sur [vercel.com](https://vercel.com)
2. Importez votre projet ou uploadez les fichiers

---

## 📲 Comment installer l'app (côté utilisateurs)

### Sur PC (Chrome / Edge)
1. Ouvrez le site dans **Chrome** ou **Edge**
2. Une notification apparaît en bas : **"Installer Ayman"**
3. Cliquez sur **Installer** → l'app s'ouvre comme une vraie application !
4. Ou : cliquez sur l'icône ⊕ dans la barre d'adresse

### Sur Android (Chrome)
1. Ouvrez le site dans **Chrome**
2. Le banner d'installation apparaît automatiquement
3. Appuyez sur **Installer** → l'icône Ayman apparaît sur l'écran d'accueil

### Sur iPhone / iPad (Safari)
1. Ouvrez le site dans **Safari** (important : pas Chrome !)
2. Appuyez sur le bouton **Partager** (carré avec flèche ↑)
3. Sélectionnez **"Sur l'écran d'accueil"**
4. Appuyez sur **Ajouter**

---

## 📁 Structure des fichiers

```
ayman-pwa/
├── index.html       ← Votre site (modifié pour PWA)
├── manifest.json    ← Configuration de l'app (nom, icônes, couleurs)
├── sw.js            ← Service Worker (cache, mode hors-ligne)
└── icons/
    ├── icon-192.png ← Icône app (Android, PWA)
    └── icon-512.png ← Icône app (splash screen)
```

---

## ✨ Fonctionnalités PWA ajoutées

- 🔔 **Banner d'installation** automatique sur Chrome/Android
- ⬇️ **Bouton "Installer l'app"** dans le hero de votre site
- 📵 **Mode hors-ligne** : le site fonctionne même sans internet
- 🖼️ **Icônes** sur l'écran d'accueil et le bureau
- 🎨 **Splash screen** aux couleurs de votre marque
- 🔗 **Raccourcis** YouTube et TikTok depuis l'icône de l'app

---

*© 2026 Ayman — Antoine*
