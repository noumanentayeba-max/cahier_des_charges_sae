# Cahier des charges – SAÉ BUT3 GEII 2026-2027

Site statique du cahier des charges (IUT de Troyes) : kart électrique autonome, recharge solaire et domotique du département GEII.

## Contenu du dossier

- `index.html` : la page du cahier des charges
- `assets/style.css` : la mise en page
- `assets/fig/` : les 9 schémas (SVG)
- `assets/img/` : les photos

Aucune installation n'est nécessaire : il suffit d'ouvrir `index.html` dans un navigateur.

## Mettre en ligne sur Netlify (le plus simple)

1. Aller sur https://app.netlify.com/drop
2. Glisser-déposer le dossier entier (celui qui contient `index.html`).
3. Netlify donne une adresse du type `https://nom-au-hasard.netlify.app`, modifiable dans *Site configuration > Change site name*.

## Mettre en ligne sur GitHub Pages

1. Créer un dépôt sur GitHub (par exemple `cahier-des-charges-sae`).
2. Envoyer le contenu du dossier à la racine du dépôt (bouton *Add file > Upload files*, ou avec git).
3. Dans le dépôt : *Settings > Pages > Build and deployment*, choisir *Deploy from a branch*, branche `main`, dossier `/ (root)`, puis *Save*.
4. Après une ou deux minutes, le site est disponible à l'adresse `https://<votre-pseudo>.github.io/cahier-des-charges-sae/`.

## Modifier le contenu

Le texte se trouve directement dans `index.html`. Pour changer un schéma, remplacer le fichier SVG correspondant dans `assets/fig/` en gardant le même nom.
