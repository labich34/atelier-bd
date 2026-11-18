# Atelier BD

Logiciel web de création de bandes dessinées : planches, cases, images et bulles de dialogue.
Un seul fichier (`index.html`), sans installation ni dépendance à compiler.

## Fonctions

- **Planches** : ajout, duplication, réorganisation, suppression ; 12 mises en page (dont *Pleine page* pour importer une planche déjà dessinée).
- **Images** : import multiple, remplissage automatique des cases vides, bibliothèque d'images.
- **Échange d'images** : glisser une image d'une case à une autre pour les permuter (ou bouton *Échanger*).
- **Recadrage** : déplacement et zoom de l'image dans sa case.
- **Bulles** : Parole, Pensée, Cri, Cartouche, Texte seul — déplacement, redimensionnement, orientation de la queue, taille du texte, majuscules, couleur de fond.
- **Annuler / Rétablir** (Ctrl+Z / Ctrl+Maj+Z).
- **Export** : planche en PNG, BD complète en PDF (petit format 15 × 20 cm ou A4).
- **Sauvegarde automatique** dans le navigateur (IndexedDB).
- **Sauvegarde fichier** (bouton disquette) : enregistre toute la BD (planches, textes, images) dans un fichier `.json`, et la rouvre sur n'importe quel appareil.

## Utilisation

Ouvrir `index.html` dans un navigateur, ou publier via GitHub Pages :
*Settings → Pages → Branch `main` / root*. L'appli sera disponible sur `https://<utilisateur>.github.io/atelier-bd/`.

> La sauvegarde est locale à chaque navigateur/appareil.
