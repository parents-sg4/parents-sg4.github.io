# Maintenance du site

## Où se trouve le site

- Dépôt GitHub : [`parents-sg4/parents-sg4.github.io`](https://github.com/parents-sg4/parents-sg4.github.io)
- Branche de publication : `main`
- Source GitHub Pages : racine du dépôt
- Adresse publique : <https://parents-sg4.github.io/>
- La page est un fichier HTML statique, sans outil de compilation ni dépendance.

## Fichiers

- `index.html` contient la page, son texte et ses styles CSS intégrés.
- `lycee-sophie-germain-1773416.webp` est l’image décorative d’arrière-plan référencée depuis `index.html`.
- Garder les deux fichiers à la racine du dépôt. Le chemin de l’image dans le CSS est relatif au fichier HTML.
- Ne publier que les fichiers nécessaires au site. Le reste du dossier AssoParents contient des documents de travail qui n’ont pas vocation à être publiés.

## Règles de modification

- Le texte est soigneusement pesé. Ne pas le reformuler, corriger ou raccourcir sans demande explicite.
- Dans le workspace AssoParents, le texte de référence du flyer est `Communication/Flyers/Markdown/flyer_asso.md`. Si ce fichier n’est pas accessible, demander le texte de référence avant une modification éditoriale.
- Reprendre les formulations du flyer validé, notamment « association indépendante » et « collectif indépendant ».
- L’adresse de contact affichée est `parents.sg4@gmail.com`. Ne pas la remplacer sans instruction.
- L’image est décorative : la traiter comme un arrière-plan, pas comme une illustration porteuse d’information.
- Conserver un fort contraste. Le CSS applique un voile blanc de 88 % au-dessus de la photo ; ne pas le réduire sans vérifier la lisibilité du texte.
- Sur les petits écrans, l’arrière-plan utilise le défilement normal plutôt que `fixed`.

## Mise à jour et vérification

1. Modifier `index.html` et, si nécessaire, remplacer l’image en gardant à jour son nom et son chemin relatif.
2. Relire le texte dans le navigateur et vérifier que l’image se charge.
3. Vérifier le rendu sur grand écran et sur téléphone, surtout le contraste derrière le titre, les paragraphes et le contact.
4. Publier les fichiers modifiés sur la branche `main`. GitHub Pages lance alors automatiquement son déploiement.
5. Vérifier que le workflow Pages a réussi et que la page publique affiche bien la modification.
