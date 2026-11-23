# 03 · Croquis & tableaux

[← Tous les styles](../README.md#les-110-styles) · 7 styles

- [Dessin en un trait](#dessin-en-un-trait)
- [Tableau blanc](#tableau-blanc)
- [Tableau à la craie](#tableau-à-la-craie)
- [Notes visuelles](#notes-visuelles)
- [Personnage-bâton pédagogique](#personnage-bâton-pédagogique)
- [Croquis sur tablette](#croquis-sur-tablette)
- [Marqueur sur papier](#marqueur-sur-papier)

## Dessin en un trait

**Rendu :** un trait continu décrit silhouette et accessoires sans jamais quitter la feuille.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Dessin en un trait » : un trait continu décrit silhouette et accessoires sans jamais quitter la feuille.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] naît d'une ligne continue puis se retourne.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Dessin en un trait » (un trait continu décrit silhouette et accessoires sans jamais quitter la feuille).
Action unique et complète : [PERSONNAGE] naît d'une ligne continue puis se retourne — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : le trait apparaît sous la main, puis l'élément dessiné s'anime.
Caméra : caméra fixe, cadre de la feuille ou du tableau visible.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Dessin en un trait » : un trait continu décrit silhouette et accessoires sans jamais quitter la feuille.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] naît d'une ligne continue puis se retourne (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : le trait apparaît sous la main, puis l'élément dessiné s'anime. Caméra : caméra fixe, cadre de la feuille ou du tableau visible.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** le trait apparaît sous la main, puis l'élément dessiné s'anime.  
**Caméra :** caméra fixe, cadre de la feuille ou du tableau visible.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** le texte manuscrit généré est souvent illisible : ajouter les mots au montage.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/one-line/STYLE.md)

## Tableau blanc

**Rendu :** feutre net, révélations progressives, effacement intentionnel et mise en page simple.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Tableau blanc » : feutre net, révélations progressives, effacement intentionnel et mise en page simple.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] dessine trois étapes et encercle la dernière.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Tableau blanc » (feutre net, révélations progressives, effacement intentionnel et mise en page simple).
Action unique et complète : [PERSONNAGE] dessine trois étapes et encercle la dernière — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : le trait apparaît sous la main, puis l'élément dessiné s'anime.
Caméra : caméra fixe, cadre de la feuille ou du tableau visible.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Tableau blanc » : feutre net, révélations progressives, effacement intentionnel et mise en page simple.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] dessine trois étapes et encercle la dernière (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : le trait apparaît sous la main, puis l'élément dessiné s'anime. Caméra : caméra fixe, cadre de la feuille ou du tableau visible.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** le trait apparaît sous la main, puis l'élément dessiné s'anime.  
**Caméra :** caméra fixe, cadre de la feuille ou du tableau visible.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** le texte manuscrit généré est souvent illisible : ajouter les mots au montage.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/whiteboard/STYLE.md)

## Tableau à la craie

**Rendu :** poussière légère, traits de craie variables et fond noir-vert.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Tableau à la craie » : poussière légère, traits de craie variables et fond noir-vert.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] trace un portail à la craie puis le traverse.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Tableau à la craie » (poussière légère, traits de craie variables et fond noir-vert).
Action unique et complète : [PERSONNAGE] trace un portail à la craie puis le traverse — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : le trait apparaît sous la main, puis l'élément dessiné s'anime.
Caméra : caméra fixe, cadre de la feuille ou du tableau visible.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Tableau à la craie » : poussière légère, traits de craie variables et fond noir-vert.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] trace un portail à la craie puis le traverse (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : le trait apparaît sous la main, puis l'élément dessiné s'anime. Caméra : caméra fixe, cadre de la feuille ou du tableau visible.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** le trait apparaît sous la main, puis l'élément dessiné s'anime.  
**Caméra :** caméra fixe, cadre de la feuille ou du tableau visible.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** le texte manuscrit généré est souvent illisible : ajouter les mots au montage.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/chalkboard/STYLE.md)

## Notes visuelles

**Rendu :** petits croquis reliés, mots-clés courts et code couleur fonctionnel.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Notes visuelles » : petits croquis reliés, mots-clés courts et code couleur fonctionnel.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] connecte des icônes par un trajet animé.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Notes visuelles » (petits croquis reliés, mots-clés courts et code couleur fonctionnel).
Action unique et complète : [PERSONNAGE] connecte des icônes par un trajet animé — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : le trait apparaît sous la main, puis l'élément dessiné s'anime.
Caméra : caméra fixe, cadre de la feuille ou du tableau visible.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Notes visuelles » : petits croquis reliés, mots-clés courts et code couleur fonctionnel.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] connecte des icônes par un trajet animé (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : le trait apparaît sous la main, puis l'élément dessiné s'anime. Caméra : caméra fixe, cadre de la feuille ou du tableau visible.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** le trait apparaît sous la main, puis l'élément dessiné s'anime.  
**Caméra :** caméra fixe, cadre de la feuille ou du tableau visible.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** le texte manuscrit généré est souvent illisible : ajouter les mots au montage.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/sketchnote/STYLE.md)

## Personnage-bâton pédagogique

**Rendu :** gestes lisibles, formes simples et silhouettes de bâtons sans complexité.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Personnage-bâton pédagogique » : gestes lisibles, formes simples et silhouettes de bâtons sans complexité.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] devient une silhouette-bâton et monte trois marches.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Personnage-bâton pédagogique » (gestes lisibles, formes simples et silhouettes de bâtons sans complexité).
Action unique et complète : [PERSONNAGE] devient une silhouette-bâton et monte trois marches — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : le trait apparaît sous la main, puis l'élément dessiné s'anime.
Caméra : caméra fixe, cadre de la feuille ou du tableau visible.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Personnage-bâton pédagogique » : gestes lisibles, formes simples et silhouettes de bâtons sans complexité.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] devient une silhouette-bâton et monte trois marches (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : le trait apparaît sous la main, puis l'élément dessiné s'anime. Caméra : caméra fixe, cadre de la feuille ou du tableau visible.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** le trait apparaît sous la main, puis l'élément dessiné s'anime.  
**Caméra :** caméra fixe, cadre de la feuille ou du tableau visible.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** le texte manuscrit généré est souvent illisible : ajouter les mots au montage.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/stick-explainer/STYLE.md)

## Croquis sur tablette

**Rendu :** pointe numérique, traits qui apparaissent sous le stylet et gestes précis.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Croquis sur tablette » : pointe numérique, traits qui apparaissent sous le stylet et gestes précis.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] dessine sur une tablette dont le contenu s'anime.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Croquis sur tablette » (pointe numérique, traits qui apparaissent sous le stylet et gestes précis).
Action unique et complète : [PERSONNAGE] dessine sur une tablette dont le contenu s'anime — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : le trait apparaît sous la main, puis l'élément dessiné s'anime.
Caméra : caméra fixe, cadre de la feuille ou du tableau visible.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Croquis sur tablette » : pointe numérique, traits qui apparaissent sous le stylet et gestes précis.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] dessine sur une tablette dont le contenu s'anime (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : le trait apparaît sous la main, puis l'élément dessiné s'anime. Caméra : caméra fixe, cadre de la feuille ou du tableau visible.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** le trait apparaît sous la main, puis l'élément dessiné s'anime.  
**Caméra :** caméra fixe, cadre de la feuille ou du tableau visible.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** le texte manuscrit généré est souvent illisible : ajouter les mots au montage.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/ipad-sketch/STYLE.md)

## Marqueur sur papier

**Rendu :** larges marqueurs opaques, texture de fibre et couches de couleur.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Marqueur sur papier » : larges marqueurs opaques, texture de fibre et couches de couleur.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] passe un marqueur, révélant une nouvelle porte.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Marqueur sur papier » (larges marqueurs opaques, texture de fibre et couches de couleur).
Action unique et complète : [PERSONNAGE] passe un marqueur, révélant une nouvelle porte — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : le trait apparaît sous la main, puis l'élément dessiné s'anime.
Caméra : caméra fixe, cadre de la feuille ou du tableau visible.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Marqueur sur papier » : larges marqueurs opaques, texture de fibre et couches de couleur.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] passe un marqueur, révélant une nouvelle porte (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : le trait apparaît sous la main, puis l'élément dessiné s'anime. Caméra : caméra fixe, cadre de la feuille ou du tableau visible.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** le trait apparaît sous la main, puis l'élément dessiné s'anime.  
**Caméra :** caméra fixe, cadre de la feuille ou du tableau visible.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** le texte manuscrit généré est souvent illisible : ajouter les mots au montage.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/marker-paper/STYLE.md)

