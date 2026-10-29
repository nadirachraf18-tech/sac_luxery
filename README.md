# SAC LUXURY — Landing Page Template

Fichier principal : `index.html`

## Modifier le produit
Ouvrez `index.html` et cherchez `const CONFIG` vers la fin du fichier. Modifiez :
- `productName` : nom du produit
- `productDescription` : description
- `price` et `oldPrice` : prix
- `color`, `contents`, `reference`, `stock`
- `image` : URL publique de la photo ou chemin relatif, par exemple `images/sac-bleu.jpg`
- `whatsapp` : numéro marocain au format international sans + ni espaces, par exemple `2126XXXXXXXX`

Pour une photo locale, ajoutez le fichier image au dépôt et utilisez son chemin relatif dans `image`.

## Publier avec GitHub Pages
1. Ouvrez **Settings** du dépôt.
2. Dans le menu, ouvrez **Pages**.
3. Sous **Build and deployment**, choisissez **Deploy from a branch**.
4. Choisissez la branche `main` et le dossier `/ (root)), puis cliquez sur **Save**.
5. Attendez le déploiement. GitHub affichera l'URL dans la section Pages. Pour ce dépôt, elle devrait ressembler à `https://nadirachraf18-tech.github.io/sac_luxery/`.

## Important
- Le numéro WhatsApp est encore un numéro de démonstration (`212600000000`). Remplacez-le avant de partager la page.
- Remplacez `IMAGE_URL` par la vraie photo du produit.
- Confirmez les prix, la disponibilité, les caractéristiques et les frais de livraison.
- Le formulaire prépare un message WhatsApp : il ne stocke pas les commandes sur un serveur.
