# Portfolio (HTML + CSS)

Ce dépôt contient un exemple simple de site portfolio en HTML et CSS.

Fichiers importants :
- `index.html` — la page principale.
- `css/styles.css` — les styles.

Comment voir les changements localement

1) Méthode simple (double-clic)
- Ouvrez l'explorateur Windows et double-cliquez sur `index.html` : il s'ouvrira dans votre navigateur par défaut.
- Après modification dans VS Code, enregistrez (`Ctrl+S`) puis rafraîchissez la page (F5) pour voir les changements.

2) Méthode recommandée : extension "Live Server" (VS Code)
- Dans VS Code, ouvrez l'espace de travail (le dossier `site portfolio`).
- Allez dans Extensions (icône carrée) et installez "Live Server" par Ritwick Dey.
- Ouvrez `index.html`, puis cliquez sur "Go Live" en bas à droite. Le site s'ouvrira dans le navigateur et se rafraîchira automatiquement quand vous enregistrez.

3) Méthode terminal (serveur HTTP simple)
- Si vous avez Python installé, ouvrez un terminal (PowerShell) dans le dossier `site portfolio` et lancez :

```powershell
python -m http.server 8000
```

- Ouvrez `http://localhost:8000` dans votre navigateur.
- Après modification, enregistrez et rafraîchissez le navigateur.

Conseils rapides
- Pour voir les changements en direct sans rafraîchir, utilisez Live Server.
- Organisez vos images dans un dossier `assets/` et mettez à jour les balises `<img>` ou les backgrounds CSS.
- Si vous voulez déployer facilement : GitHub Pages est une option gratuite (je peux vous montrer la procédure si vous le souhaitez).

Souhaitez-vous que je :
- personnalise le design (couleurs, typo, sections) ?
- ajoute un exemple d'image `assets/` et un fichier `manifest` ?
- ou vous montre comment déployer sur GitHub Pages ?

Dites-moi ce que vous voulez modifier en premier et je l'implémente.