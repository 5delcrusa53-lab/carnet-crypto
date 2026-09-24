# Carnet Crypto — installation

## 1. Mettre en ligne (GitHub Pages)
1. Créez un dépôt GitHub (ex. `carnet-crypto`) et déposez-y tous les fichiers de ce dossier.
2. Settings → Pages → Branch `main` / dossier racine → Save.
3. L'appli est disponible sur `https://<votre-pseudo>.github.io/carnet-crypto/`.

## 2a. Installer directement (le plus simple)
Ouvrez l'URL dans Chrome sur Android → menu ⋮ → « Installer l'application ».

## 2b. Générer un vrai APK
1. Allez sur https://www.pwabuilder.com et collez l'URL GitHub Pages.
2. « Package for stores » → Android → « Generate » (options par défaut ou « Other Android » pour un APK non signé Play Store).
3. Téléchargez le zip, récupérez le fichier `.apk`, copiez-le sur le téléphone et installez-le
   (autoriser « Sources inconnues » pour le gestionnaire de fichiers).
4. Pour que la barre d'adresse disparaisse dans l'APK, déposez le fichier `assetlinks.json` fourni par PWABuilder
   dans `.well-known/assetlinks.json` de votre dépôt.

## Données
Tout est stocké localement sur l'appareil. Exportez régulièrement une sauvegarde (Réglages → Exporter).
Seuls les prix (DexScreener) et le taux EUR (Frankfurter) sont récupérés en ligne.
