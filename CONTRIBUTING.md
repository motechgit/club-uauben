# Règles de contribution

1. **Jamais de commit sur `main`.** Travaillez uniquement sur votre branche `feature/<page>`.
2. **Un seul fichier par étudiant** : `pages/<page>.html` (+ vos images dans `images/`).
   Ne modifiez pas `index.html` ni `css/style.css` (sauf exercice de conflit).
3. **Partez du gabarit** `pages/_modele.html`.
4. **Au moins 3 commits**, au format *Conventional Commits* :
   - `feat(contact): ajout du formulaire`
   - `fix(contact): correction du lien mailto`
   - `docs: mise à jour du README`
5. **Pull Request vers `main`** avec :
   - un titre clair (`Ajout de la page Contact`) ;
   - une description et une capture d'écran ;
   - `Closes #N` si une Issue existe ;
   - un camarade désigné comme *Reviewer*.
6. **Revue obligatoire** : au moins une approbation avant fusion.
7. **Restez à jour** : `git pull origin main` sur votre branche avant la relecture finale.

## Check-list avant la PR

- [ ] Page accessible depuis le menu, liens fonctionnels
- [ ] `<title>`, `<h1>` et nom de l'auteur renseignés
- [ ] `git status` ne montre que mes fichiers
- [ ] Code validé sur https://validator.w3.org
