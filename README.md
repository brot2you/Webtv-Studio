# WEBTV STUDIO by BROT2YOU — V1 autonome

Application web sans compilation, pour GitHub Pages. Ouvrir `index.html` via un serveur local ou publier le dossier à la racine du dépôt `WebTV-Studio` avec GitHub Pages. L'adresse sera `https://<utilisateur>.github.io/WebTV-Studio/`.

## Fonctionnalités présentes
- Rédaction d'articles avec mise en forme, sauvegarde IndexedDB, aide journalistique par règles, durée estimée.
- Bibliothèque, recherche, filtres, duplication, corbeille, commentaires et validation locale.
- Import/export JSON individuel ou collectif, détection des doublons.
- Conducteur avec séquences, déplacement, articles validés, export JSON.
- Prompteur plein écran, défilement `requestAnimationFrame`, commandes clavier et tactiles, miroir, police, vitesse, repère, compte à rebours.
- PWA hors ligne après premier chargement sur HTTPS.

## Limites connues / non inclus
- Pas de synchronisation Firebase ni d'authentification sécurisée dans cette livraison. L'espace professeur local n'est pas protégé par un rôle.
- Pas de télécommande réseau, ni de vraie fenêtre de régie double écran.
- Pas d'export PDF natif, d'images jointes, de commentaires ancrés à des passages ou de restauration intégrale des émissions à partir d'un backup (l'import ne restaure que les articles).
- L'historique des versions est limité et enregistré lors des sauvegardes manuelles.
- Les tests navigateur automatisés et tests multi-appareils restent à effectuer avant usage en production.

## Confidentialité
Les données sont stockées localement dans IndexedDB. Ne pas publier des données personnelles d'élèves sur un dépôt public. Pour une collaboration connectée, il faudra configurer un fournisseur d'authentification, les règles de sécurité et vérifier le cadre RGPD avec l'établissement.
