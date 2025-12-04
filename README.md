# Site Web - Pétition Toulouse-Tlemcen

## 🚀 Déploiement sur Netlify Drop

### Étapes simples :

1. **Télécharger ce dossier complet** `site_web_petition`
2. Aller sur **https://app.netlify.com/drop**
3. **Glisser-déposer** tout le dossier `site_web_petition` sur Netlify Drop
4. Votre site sera en ligne en 30 secondes !
5. Netlify vous donnera une URL type : `https://votre-site-123456.netlify.app`

## 📝 Personnalisation obligatoire

Avant de déployer, ouvrez `index.html` et modifiez :

**Ligne ~580** - Remplacer le lien de la pétition :
```html
<!-- Actuellement (ligne 580) : -->
<a href="#" class="btn btn-primary" onclick="alert...

<!-- Remplacer par : -->
<a href="https://www.change.org/VOTRE-PETITION" class="btn btn-primary">
    ✍ Signer la pétition maintenant
</a>
```

## 📂 Contenu du dossier

- `index.html` - Le site web complet
- `carte_geographique_professionnelle.png` - Carte Toulouse-Tlemcen
- `graphique_croissance_trafic.png` - Graphique +126%
- `graphique_demographie.png` - Bassin 500K+
- `infographie_comparaison.png` - Avant/Après
- `README.md` - Ce fichier

## ✅ Le site inclut

✅ Design responsive (mobile/tablette/desktop)
✅ Animations fluides
✅ SEO optimisé
✅ Chargement ultra-rapide
✅ Prêt pour partage réseaux sociaux

## 🎨 Personnalisation des couleurs (optionnel)

Dans `index.html`, lignes 14-21, vous pouvez modifier :
```css
:root {
    --primary: #1F4788;      /* Bleu principal */
    --accent: #C45A00;       /* Orange */
    --success: #006400;      /* Vert */
}
```

## 📱 Partage

Une fois en ligne, partagez votre URL sur :
- Facebook
- Twitter/X
- LinkedIn
- Instagram (lien dans bio)
- WhatsApp
- Email

## 🆘 Besoin d'aide ?

Si problème avec Netlify, alternatives gratuites :
- **Vercel** : https://vercel.com (même principe drag & drop)
- **GitHub Pages** : https://pages.github.com (nécessite compte GitHub)
- **Surge.sh** : https://surge.sh (via ligne de commande)

## 📊 Statistiques (optionnel)

Pour suivre les visites, ajoutez Google Analytics :
1. Créer compte sur https://analytics.google.com
2. Obtenir votre ID (ex: G-XXXXXXXXXX)
3. Ajouter avant `</head>` dans index.html :

```html
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

---

**Bonne chance pour votre campagne ! 🎉✈️**

#ToulouseTlemcen #LiaisonDirecte
