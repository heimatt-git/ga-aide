# Gundam Assemble – Aide de jeu (non officielle)

Application web installable (PWA), 100 % statique, qui fonctionne hors ligne une fois ouverte une première fois.

## Héberger sur GitHub Pages
1. Créez un dépôt GitHub (par ex. `ga-aide`), public.
2. Envoyez-y tous les fichiers de ce dossier : bouton **Add file > Upload files** sur la page du dépôt, puis **Commit changes**.
3. **Settings > Pages** : Source = *Deploy from a branch*, branche `main`, dossier `/ (root)`, **Save**.
4. Après 1 à 2 minutes, le site est en ligne sur `https://VOTRE-PSEUDO.github.io/ga-aide/`.

## Installer sur téléphone
- **Android (Chrome)** : menu ⋮ > *Installer l'application* (ou *Ajouter à l'écran d'accueil*).
- **iPhone (Safari)** : bouton Partager > *Sur l'écran d'accueil*.

## Mettre à jour
Remplacez `index.html` dans le dépôt, puis changez `VERSION` dans `sw.js` (ex. `ga-aide-v2`) pour que les téléphones récupèrent la nouvelle version.

Les données de partie sont enregistrées dans le navigateur de chaque appareil (stockage local) ; elles ne sont pas synchronisées entre appareils.

Projet de fan, non affilié à Bandai. Les noms et données d'unités appartiennent à leurs ayants droit ; les traductions françaises et les textes d'effets sont des lectures non officielles à vérifier sur vos cartes.
