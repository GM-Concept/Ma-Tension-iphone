# Ma Tension — GitHub Pages

## Publier depuis l’iPhone
1. Dans Safari, ouvre https://github.com/new et crée un dépôt nommé `ma-tension-iphone`. Pour GitHub Pages gratuit, choisis Public. Ne mets aucune donnée de santé dans le dépôt.
2. Dans le dépôt, choisis **Add file → Upload files**. Ajoute `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png` et `icon-512.png` depuis ce dossier ZIP décompressé dans Fichiers. Si le mobile ne permet pas plusieurs fichiers, ajoute-les un par un.
3. Valide avec **Commit changes**.
4. Ouvre **Settings → Pages**. Dans **Build and deployment**, choisis **Deploy from a branch**, branche `main`, dossier `/(root)`, puis **Save**.
5. Attends la publication. L’adresse sera du type `https://TON-PSEUDO.github.io/ma-tension-iphone/`. Utilise l’adresse exacte affichée dans Settings → Pages.
6. Dans Safari, ouvre cette adresse → bouton **Partager** → **Sur l’écran d’accueil** → **Ajouter**.
7. Ouvre l’icône, saisis un relevé de test, ferme puis rouvre l’app pour vérifier que l’historique est présent.

## Données et confidentialité
Les relevés restent dans IndexedDB sur l’appareil et ne sont pas envoyés à GitHub. Le dépôt public ne contient que le code. Exporte régulièrement une sauvegarde JSON et conserve-la dans Fichiers : supprimer les données du site/Safari peut supprimer les données locales. Ne partage pas la sauvegarde JSON, elle contient des données de santé. L’app n’est pas synchronisée avec Apple Santé et ne remplace pas un avis médical.
