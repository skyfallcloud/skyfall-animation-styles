# 07 · Plans & schémas

[← Tous les styles](../README.md#les-110-styles) · 8 styles

- [Plan d'ingénieur](#plan-dingénieur)
- [Infographie isométrique](#infographie-isométrique)
- [Vue éclatée technique](#vue-éclatée-technique)
- [Coupe technique en ligne](#coupe-technique-en-ligne)
- [Mécanisme à codes couleur](#mécanisme-à-codes-couleur)
- [Illustration de notice](#illustration-de-notice)
- [Traceur à plume](#traceur-à-plume)
- [Chaîne d'assemblage](#chaîne-dassemblage)

## Plan d'ingénieur

**Rendu :** lignes de construction bleues, cotes fictives signalées comme maquette et vues orthogonales.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Plan d'ingénieur » : lignes de construction bleues, cotes fictives signalées comme maquette et vues orthogonales.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] dessine le plan d'un portail imaginaire.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Plan d'ingénieur » (lignes de construction bleues, cotes fictives signalées comme maquette et vues orthogonales).
Action unique et complète : [PERSONNAGE] dessine le plan d'un portail imaginaire — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent.
Caméra : vue orthographique ou isométrique stable.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Plan d'ingénieur » : lignes de construction bleues, cotes fictives signalées comme maquette et vues orthogonales.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] dessine le plan d'un portail imaginaire (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent. Caméra : vue orthographique ou isométrique stable.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** éclatés, assemblages pas à pas, tracés qui se dessinent.  
**Caméra :** vue orthographique ou isométrique stable.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** vérifier l'exactitude technique ; un schéma inventé doit être présenté comme illustratif.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/blueprint/STYLE.md)

## Infographie isométrique

**Rendu :** petits modules isométriques, flèches et palette pédagogique.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Infographie isométrique » : petits modules isométriques, flèches et palette pédagogique.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] transporte une pièce d'un module à l'autre.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Infographie isométrique » (petits modules isométriques, flèches et palette pédagogique).
Action unique et complète : [PERSONNAGE] transporte une pièce d'un module à l'autre — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent.
Caméra : vue orthographique ou isométrique stable.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Infographie isométrique » : petits modules isométriques, flèches et palette pédagogique.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] transporte une pièce d'un module à l'autre (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent. Caméra : vue orthographique ou isométrique stable.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** éclatés, assemblages pas à pas, tracés qui se dessinent.  
**Caméra :** vue orthographique ou isométrique stable.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** vérifier l'exactitude technique ; un schéma inventé doit être présenté comme illustratif.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/iso-infographic/STYLE.md)

## Vue éclatée technique

**Rendu :** composants espacés selon leur assemblage, fond neutre et légendes manuelles.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Vue éclatée technique » : composants espacés selon leur assemblage, fond neutre et légendes manuelles.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] sépare les éléments fictifs d'une télécommande.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Vue éclatée technique » (composants espacés selon leur assemblage, fond neutre et légendes manuelles).
Action unique et complète : [PERSONNAGE] sépare les éléments fictifs d'une télécommande — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent.
Caméra : vue orthographique ou isométrique stable.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Vue éclatée technique » : composants espacés selon leur assemblage, fond neutre et légendes manuelles.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] sépare les éléments fictifs d'une télécommande (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent. Caméra : vue orthographique ou isométrique stable.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** éclatés, assemblages pas à pas, tracés qui se dessinent.  
**Caméra :** vue orthographique ou isométrique stable.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** vérifier l'exactitude technique ; un schéma inventé doit être présenté comme illustratif.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/teardown/STYLE.md)

## Coupe technique en ligne

**Rendu :** traits de coupe, surfaces hachurées et trajet mis en évidence.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Coupe technique en ligne » : traits de coupe, surfaces hachurées et trajet mis en évidence.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] révèle la coupe d'une machine imaginaire.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Coupe technique en ligne » (traits de coupe, surfaces hachurées et trajet mis en évidence).
Action unique et complète : [PERSONNAGE] révèle la coupe d'une machine imaginaire — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent.
Caméra : vue orthographique ou isométrique stable.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Coupe technique en ligne » : traits de coupe, surfaces hachurées et trajet mis en évidence.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] révèle la coupe d'une machine imaginaire (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent. Caméra : vue orthographique ou isométrique stable.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** éclatés, assemblages pas à pas, tracés qui se dessinent.  
**Caméra :** vue orthographique ou isométrique stable.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** vérifier l'exactitude technique ; un schéma inventé doit être présenté comme illustratif.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/hardcore-info/STYLE.md)

## Mécanisme à codes couleur

**Rendu :** engrenages schématiques colorés et flux illustrés sans donnée trompeuse.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Mécanisme à codes couleur » : engrenages schématiques colorés et flux illustrés sans donnée trompeuse.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] entraîne un engrenage qui actionne le prochain mécanisme.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Mécanisme à codes couleur » (engrenages schématiques colorés et flux illustrés sans donnée trompeuse).
Action unique et complète : [PERSONNAGE] entraîne un engrenage qui actionne le prochain mécanisme — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent.
Caméra : vue orthographique ou isométrique stable.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Mécanisme à codes couleur » : engrenages schématiques colorés et flux illustrés sans donnée trompeuse.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] entraîne un engrenage qui actionne le prochain mécanisme (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent. Caméra : vue orthographique ou isométrique stable.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** éclatés, assemblages pas à pas, tracés qui se dessinent.  
**Caméra :** vue orthographique ou isométrique stable.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** vérifier l'exactitude technique ; un schéma inventé doit être présenté comme illustratif.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/precise-mechanism/STYLE.md)

## Illustration de notice

**Rendu :** étapes numérotées, contours uniformes et gestes simplifiés.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Illustration de notice » : étapes numérotées, contours uniformes et gestes simplifiés.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] assemble un objet fictif en trois étapes.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Illustration de notice » (étapes numérotées, contours uniformes et gestes simplifiés).
Action unique et complète : [PERSONNAGE] assemble un objet fictif en trois étapes — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent.
Caméra : vue orthographique ou isométrique stable.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Illustration de notice » : étapes numérotées, contours uniformes et gestes simplifiés.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] assemble un objet fictif en trois étapes (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent. Caméra : vue orthographique ou isométrique stable.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** éclatés, assemblages pas à pas, tracés qui se dessinent.  
**Caméra :** vue orthographique ou isométrique stable.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** vérifier l'exactitude technique ; un schéma inventé doit être présenté comme illustratif.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/instruction-manual/STYLE.md)

## Traceur à plume

**Rendu :** trait mécanique progressif, angles mesurés et faible gamme chromatique.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Traceur à plume » : trait mécanique progressif, angles mesurés et faible gamme chromatique.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] regarde un plotter tracer sa silhouette.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Traceur à plume » (trait mécanique progressif, angles mesurés et faible gamme chromatique).
Action unique et complète : [PERSONNAGE] regarde un plotter tracer sa silhouette — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent.
Caméra : vue orthographique ou isométrique stable.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Traceur à plume » : trait mécanique progressif, angles mesurés et faible gamme chromatique.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] regarde un plotter tracer sa silhouette (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent. Caméra : vue orthographique ou isométrique stable.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** éclatés, assemblages pas à pas, tracés qui se dessinent.  
**Caméra :** vue orthographique ou isométrique stable.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** vérifier l'exactitude technique ; un schéma inventé doit être présenté comme illustratif.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/pen-plotter/STYLE.md)

## Chaîne d'assemblage

**Rendu :** modules alignés, déplacements précis sur tapis et flèches fonctionnelles.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Chaîne d'assemblage » : modules alignés, déplacements précis sur tapis et flèches fonctionnelles.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] fait avancer une petite pièce entre trois stations.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Chaîne d'assemblage » (modules alignés, déplacements précis sur tapis et flèches fonctionnelles).
Action unique et complète : [PERSONNAGE] fait avancer une petite pièce entre trois stations — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent.
Caméra : vue orthographique ou isométrique stable.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Chaîne d'assemblage » : modules alignés, déplacements précis sur tapis et flèches fonctionnelles.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] fait avancer une petite pièce entre trois stations (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : éclatés, assemblages pas à pas, tracés qui se dessinent. Caméra : vue orthographique ou isométrique stable.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** éclatés, assemblages pas à pas, tracés qui se dessinent.  
**Caméra :** vue orthographique ou isométrique stable.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** vérifier l'exactitude technique ; un schéma inventé doit être présenté comme illustratif.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/assembly-line-diagram/STYLE.md)

