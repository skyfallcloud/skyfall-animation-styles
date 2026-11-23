# 01 · Montage & documentaire

[← Tous les styles](../README.md#les-110-styles) · 8 styles

- [Flash info sous-titré](#flash-info-sous-titré)
- [Actualités des années 1920](#actualités-des-années-1920)
- [Décompte en écrans partagés](#décompte-en-écrans-partagés)
- [Symphonie urbaine](#symphonie-urbaine)
- [Enquête visuelle](#enquête-visuelle)
- [Montage constructiviste](#montage-constructiviste)
- [Analyse sportive dessinée](#analyse-sportive-dessinée)
- [Habillage journal télévisé](#habillage-journal-télévisé)

## Flash info sous-titré

**Rendu :** cadres de reportage sobres, bandeau de titre net et hiérarchie de l'information.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Flash info sous-titré » : cadres de reportage sobres, bandeau de titre net et hiérarchie de l'information.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] pousse un carton titre sur l'écran puis indique la donnée d'exemple.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Flash info sous-titré » (cadres de reportage sobres, bandeau de titre net et hiérarchie de l'information).
Action unique et complète : [PERSONNAGE] pousse un carton titre sur l'écran puis indique la donnée d'exemple — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois.
Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Flash info sous-titré » : cadres de reportage sobres, bandeau de titre net et hiérarchie de l'information.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] pousse un carton titre sur l'écran puis indique la donnée d'exemple (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois. Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** coupes franches sur le rythme, titres qui glissent, une information à la fois.  
**Caméra :** caméra fixe ou travelling lent pour que le texte reste lisible.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** les chiffres et faits affichés doivent être réels ; sinon, écrire « simulation fictive » à l'écran.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/caption-news/STYLE.md)

## Actualités des années 1920

**Rendu :** grain de pellicule monochrome, iris optique et cartons typographiques anciens.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Actualités des années 1920 » : grain de pellicule monochrome, iris optique et cartons typographiques anciens.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] fait tourner une manivelle et déclenche le cadre suivant.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Actualités des années 1920 » (grain de pellicule monochrome, iris optique et cartons typographiques anciens).
Action unique et complète : [PERSONNAGE] fait tourner une manivelle et déclenche le cadre suivant — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois.
Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Actualités des années 1920 » : grain de pellicule monochrome, iris optique et cartons typographiques anciens.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] fait tourner une manivelle et déclenche le cadre suivant (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois. Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** coupes franches sur le rythme, titres qui glissent, une information à la fois.  
**Caméra :** caméra fixe ou travelling lent pour que le texte reste lisible.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** les chiffres et faits affichés doivent être réels ; sinon, écrire « simulation fictive » à l'écran.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/newsreel/STYLE.md)

## Décompte en écrans partagés

**Rendu :** grille multi-écrans synchronisée, chiffres lisibles et rupture sur zéro.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Décompte en écrans partagés » : grille multi-écrans synchronisée, chiffres lisibles et rupture sur zéro.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] appuie sur un gros bouton, les écrans décomptent ensemble.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Décompte en écrans partagés » (grille multi-écrans synchronisée, chiffres lisibles et rupture sur zéro).
Action unique et complète : [PERSONNAGE] appuie sur un gros bouton, les écrans décomptent ensemble — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois.
Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Décompte en écrans partagés » : grille multi-écrans synchronisée, chiffres lisibles et rupture sur zéro.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] appuie sur un gros bouton, les écrans décomptent ensemble (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois. Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** coupes franches sur le rythme, titres qui glissent, une information à la fois.  
**Caméra :** caméra fixe ou travelling lent pour que le texte reste lisible.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** les chiffres et faits affichés doivent être réels ; sinon, écrire « simulation fictive » à l'écran.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/countdown/STYLE.md)

## Symphonie urbaine

**Rendu :** montage rythmique de silhouettes urbaines et changements d'échelle.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Symphonie urbaine » : montage rythmique de silhouettes urbaines et changements d'échelle.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] traverse trois plans d'une ville stylisée par raccord de mouvement.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Symphonie urbaine » (montage rythmique de silhouettes urbaines et changements d'échelle).
Action unique et complète : [PERSONNAGE] traverse trois plans d'une ville stylisée par raccord de mouvement — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois.
Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Symphonie urbaine » : montage rythmique de silhouettes urbaines et changements d'échelle.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] traverse trois plans d'une ville stylisée par raccord de mouvement (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois. Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** coupes franches sur le rythme, titres qui glissent, une information à la fois.  
**Caméra :** caméra fixe ou travelling lent pour que le texte reste lisible.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** les chiffres et faits affichés doivent être réels ; sinon, écrire « simulation fictive » à l'écran.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/city-symphony/STYLE.md)

## Enquête visuelle

**Rendu :** documents reliés, zooms sur indices explicitement fictifs et annotation précise.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Enquête visuelle » : documents reliés, zooms sur indices explicitement fictifs et annotation précise.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] relie trois indices fictifs par un fil lumineux.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Enquête visuelle » (documents reliés, zooms sur indices explicitement fictifs et annotation précise).
Action unique et complète : [PERSONNAGE] relie trois indices fictifs par un fil lumineux — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois.
Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Enquête visuelle » : documents reliés, zooms sur indices explicitement fictifs et annotation précise.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] relie trois indices fictifs par un fil lumineux (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois. Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** coupes franches sur le rythme, titres qui glissent, une information à la fois.  
**Caméra :** caméra fixe ou travelling lent pour que le texte reste lisible.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** les chiffres et faits affichés doivent être réels ; sinon, écrire « simulation fictive » à l'écran.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/visual-investigation/STYLE.md)

## Montage constructiviste

**Rendu :** diagonales, silhouettes en contreplongée, typographie géométrique et cuts percussifs.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Montage constructiviste » : diagonales, silhouettes en contreplongée, typographie géométrique et cuts percussifs.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] fait basculer une forme rouge qui devient l'écran suivant.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Montage constructiviste » (diagonales, silhouettes en contreplongée, typographie géométrique et cuts percussifs).
Action unique et complète : [PERSONNAGE] fait basculer une forme rouge qui devient l'écran suivant — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois.
Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Montage constructiviste » : diagonales, silhouettes en contreplongée, typographie géométrique et cuts percussifs.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] fait basculer une forme rouge qui devient l'écran suivant (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois. Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** coupes franches sur le rythme, titres qui glissent, une information à la fois.  
**Caméra :** caméra fixe ou travelling lent pour que le texte reste lisible.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** les chiffres et faits affichés doivent être réels ; sinon, écrire « simulation fictive » à l'écran.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/kino-montage/STYLE.md)

## Analyse sportive dessinée

**Rendu :** tracés tactiques par-dessus une séquence d'exemple sans sportifs réels.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Analyse sportive dessinée » : tracés tactiques par-dessus une séquence d'exemple sans sportifs réels.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] dessine une trajectoire qui se matérialise.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Analyse sportive dessinée » (tracés tactiques par-dessus une séquence d'exemple sans sportifs réels).
Action unique et complète : [PERSONNAGE] dessine une trajectoire qui se matérialise — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois.
Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Analyse sportive dessinée » : tracés tactiques par-dessus une séquence d'exemple sans sportifs réels.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] dessine une trajectoire qui se matérialise (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois. Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** coupes franches sur le rythme, titres qui glissent, une information à la fois.  
**Caméra :** caméra fixe ou travelling lent pour que le texte reste lisible.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** les chiffres et faits affichés doivent être réels ; sinon, écrire « simulation fictive » à l'écran.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/telestrator/STYLE.md)

## Habillage journal télévisé

**Rendu :** plateau graphique, lower thirds propres, ouverture animée et synthés légers.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Habillage journal télévisé » : plateau graphique, lower thirds propres, ouverture animée et synthés légers.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] ouvre un journal fictif puis lance un sujet sur les styles.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Habillage journal télévisé » (plateau graphique, lower thirds propres, ouverture animée et synthés légers).
Action unique et complète : [PERSONNAGE] ouvre un journal fictif puis lance un sujet sur les styles — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois.
Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Habillage journal télévisé » : plateau graphique, lower thirds propres, ouverture animée et synthés légers.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] ouvre un journal fictif puis lance un sujet sur les styles (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : coupes franches sur le rythme, titres qui glissent, une information à la fois. Caméra : caméra fixe ou travelling lent pour que le texte reste lisible.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** coupes franches sur le rythme, titres qui glissent, une information à la fois.  
**Caméra :** caméra fixe ou travelling lent pour que le texte reste lisible.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** les chiffres et faits affichés doivent être réels ; sinon, écrire « simulation fictive » à l'écran.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/news-package/STYLE.md)

