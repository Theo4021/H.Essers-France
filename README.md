# Dashboard H.ESSERS

Dashboard statique compatible avec GitHub Pages.

## Publication sur GitHub Pages

1. Créer un dépôt GitHub **privé**.
2. Copier le contenu de ce dossier dans le dépôt.
3. Vérifier que `Data/` et `Sauvegardes_dashboard/` ne sont pas envoyés.
4. Dans **Settings > Pages**, choisir **Deploy from a branch**, puis la branche `main` et le dossier `/ (root)`.
5. Ouvrir l'URL fournie par GitHub Pages : le fichier d'entrée est `index.html`.

## Données et sécurité

Les données de l'application sont enregistrées localement dans le navigateur. Le mode
de partage utilise l'autorisation du dossier `Data` via le sélecteur de dossiers du
navigateur. GitHub Pages ne fournit pas de base de données ni de serveur de
synchronisation.

Ne jamais publier les fichiers du dossier `Data/` dans un dépôt public : ils peuvent
contenir des informations personnelles et des pièces jointes.

Le navigateur doit être à jour et le site doit être ouvert en HTTPS pour utiliser le
partage de dossier. Pour plusieurs utilisateurs avec des données centralisées, il
faudra ultérieurement remplacer le stockage par un service serveur sécurisé.
