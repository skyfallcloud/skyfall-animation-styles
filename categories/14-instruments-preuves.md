# 14 · Instruments & preuves

[← Tous les styles](../README.md#les-110-styles) · 8 styles

- [Briefing satellite](#briefing-satellite)
- [Panneau d'ingénierie](#panneau-dingénierie)
- [Nuage de points LiDAR](#nuage-de-points-lidar)
- [Observation microscopique](#observation-microscopique)
- [Table lumineuse d'archives](#table-lumineuse-darchives)
- [Vue aux rayons X](#vue-aux-rayons-x)
- [Radar documentaire](#radar-documentaire)
- [Caméra thermique](#caméra-thermique)

## Briefing satellite

**Rendu :** vues aériennes de démonstration, tracés d'annotation non factuels.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Briefing satellite » : vues aériennes de démonstration, tracés d'annotation non factuels.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] zoome sur une carte clairement imaginaire.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Briefing satellite » (vues aériennes de démonstration, tracés d'annotation non factuels).
Action unique et complète : [PERSONNAGE] zoome sur une carte clairement imaginaire — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : relevés et calques qui se superposent, mesures qui défilent.
Caméra : caméra d'instrument (fixe, vue technique).
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Briefing satellite » : vues aériennes de démonstration, tracés d'annotation non factuels.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] zoome sur une carte clairement imaginaire (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : relevés et calques qui se superposent, mesures qui défilent. Caméra : caméra d'instrument (fixe, vue technique).
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** relevés et calques qui se superposent, mesures qui défilent.  
**Caméra :** caméra d'instrument (fixe, vue technique).  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** ne jamais présenter des mesures simulées comme réelles.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/satellite-briefing/STYLE.md)

## Panneau d'ingénierie

**Rendu :** panneaux de schéma technique de fiction et repères nets.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Panneau d'ingénierie » : panneaux de schéma technique de fiction et repères nets.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] révèle étape par étape une maquette de système.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Panneau d'ingénierie » (panneaux de schéma technique de fiction et repères nets).
Action unique et complète : [PERSONNAGE] révèle étape par étape une maquette de système — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : relevés et calques qui se superposent, mesures qui défilent.
Caméra : caméra d'instrument (fixe, vue technique).
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Panneau d'ingénierie » : panneaux de schéma technique de fiction et repères nets.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] révèle étape par étape une maquette de système (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : relevés et calques qui se superposent, mesures qui défilent. Caméra : caméra d'instrument (fixe, vue technique).
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** relevés et calques qui se superposent, mesures qui défilent.  
**Caméra :** caméra d'instrument (fixe, vue technique).  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** ne jamais présenter des mesures simulées comme réelles.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/briefing-board/STYLE.md)

## Nuage de points LiDAR

**Rendu :** points 3D dessinant une scène synthétique, coupes et balayage.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Nuage de points LiDAR » : points 3D dessinant une scène synthétique, coupes et balayage.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] passe un scanner sur un objet synthétique.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Nuage de points LiDAR » (points 3D dessinant une scène synthétique, coupes et balayage).
Action unique et complète : [PERSONNAGE] passe un scanner sur un objet synthétique — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : relevés et calques qui se superposent, mesures qui défilent.
Caméra : caméra d'instrument (fixe, vue technique).
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Nuage de points LiDAR » : points 3D dessinant une scène synthétique, coupes et balayage.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] passe un scanner sur un objet synthétique (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : relevés et calques qui se superposent, mesures qui défilent. Caméra : caméra d'instrument (fixe, vue technique).
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** relevés et calques qui se superposent, mesures qui défilent.  
**Caméra :** caméra d'instrument (fixe, vue technique).  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** ne jamais présenter des mesures simulées comme réelles.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/lidar-survey/STYLE.md)

## Observation microscopique

**Rendu :** lentilles circulaires et particules artistiques signalées comme simulation.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Observation microscopique » : lentilles circulaires et particules artistiques signalées comme simulation.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] règle une lentille qui révèle un motif imaginaire.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Observation microscopique » (lentilles circulaires et particules artistiques signalées comme simulation).
Action unique et complète : [PERSONNAGE] règle une lentille qui révèle un motif imaginaire — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : relevés et calques qui se superposent, mesures qui défilent.
Caméra : caméra d'instrument (fixe, vue technique).
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Observation microscopique » : lentilles circulaires et particules artistiques signalées comme simulation.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] règle une lentille qui révèle un motif imaginaire (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : relevés et calques qui se superposent, mesures qui défilent. Caméra : caméra d'instrument (fixe, vue technique).
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** relevés et calques qui se superposent, mesures qui défilent.  
**Caméra :** caméra d'instrument (fixe, vue technique).  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** ne jamais présenter des mesures simulées comme réelles.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/microscope/STYLE.md)

## Table lumineuse d'archives

**Rendu :** diapositives fictives sous éclairage diffus et verre texturé.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Table lumineuse d'archives » : diapositives fictives sous éclairage diffus et verre texturé.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] pose deux diapositives illustrées puis les superpose.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Table lumineuse d'archives » (diapositives fictives sous éclairage diffus et verre texturé).
Action unique et complète : [PERSONNAGE] pose deux diapositives illustrées puis les superpose — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : relevés et calques qui se superposent, mesures qui défilent.
Caméra : caméra d'instrument (fixe, vue technique).
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Table lumineuse d'archives » : diapositives fictives sous éclairage diffus et verre texturé.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] pose deux diapositives illustrées puis les superpose (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : relevés et calques qui se superposent, mesures qui défilent. Caméra : caméra d'instrument (fixe, vue technique).
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** relevés et calques qui se superposent, mesures qui défilent.  
**Caméra :** caméra d'instrument (fixe, vue technique).  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** ne jamais présenter des mesures simulées comme réelles.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/archive-lighttable/STYLE.md)

## Vue aux rayons X

**Rendu :** couleurs artificielles d'imagerie X fictive et silhouettes d'objets.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Vue aux rayons X » : couleurs artificielles d'imagerie X fictive et silhouettes d'objets.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] passe sa boîte d'accessoires à travers un scanner de démonstration.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Vue aux rayons X » (couleurs artificielles d'imagerie X fictive et silhouettes d'objets).
Action unique et complète : [PERSONNAGE] passe sa boîte d'accessoires à travers un scanner de démonstration — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : relevés et calques qui se superposent, mesures qui défilent.
Caméra : caméra d'instrument (fixe, vue technique).
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Vue aux rayons X » : couleurs artificielles d'imagerie X fictive et silhouettes d'objets.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] passe sa boîte d'accessoires à travers un scanner de démonstration (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : relevés et calques qui se superposent, mesures qui défilent. Caméra : caméra d'instrument (fixe, vue technique).
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** relevés et calques qui se superposent, mesures qui défilent.  
**Caméra :** caméra d'instrument (fixe, vue technique).  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** ne jamais présenter des mesures simulées comme réelles.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/security-xray/STYLE.md)

## Radar documentaire

**Rendu :** rayon de balayage, grille de fond et points clairement simulés.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Radar documentaire » : rayon de balayage, grille de fond et points clairement simulés.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] suit un signal sur un écran de fiction.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Radar documentaire » (rayon de balayage, grille de fond et points clairement simulés).
Action unique et complète : [PERSONNAGE] suit un signal sur un écran de fiction — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : relevés et calques qui se superposent, mesures qui défilent.
Caméra : caméra d'instrument (fixe, vue technique).
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Radar documentaire » : rayon de balayage, grille de fond et points clairement simulés.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] suit un signal sur un écran de fiction (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : relevés et calques qui se superposent, mesures qui défilent. Caméra : caméra d'instrument (fixe, vue technique).
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** relevés et calques qui se superposent, mesures qui défilent.  
**Caméra :** caméra d'instrument (fixe, vue technique).  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** ne jamais présenter des mesures simulées comme réelles.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/dark-documentary/STYLE.md)

## Caméra thermique

**Rendu :** palette thermique illustrative, zones colorées et légende 'simulation'.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Caméra thermique » : palette thermique illustrative, zones colorées et légende 'simulation'.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] observe une tasse fictive devenir rouge puis bleue.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Caméra thermique » (palette thermique illustrative, zones colorées et légende 'simulation').
Action unique et complète : [PERSONNAGE] observe une tasse fictive devenir rouge puis bleue — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : relevés et calques qui se superposent, mesures qui défilent.
Caméra : caméra d'instrument (fixe, vue technique).
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Caméra thermique » : palette thermique illustrative, zones colorées et légende 'simulation'.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] observe une tasse fictive devenir rouge puis bleue (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : relevés et calques qui se superposent, mesures qui défilent. Caméra : caméra d'instrument (fixe, vue technique).
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** relevés et calques qui se superposent, mesures qui défilent.  
**Caméra :** caméra d'instrument (fixe, vue technique).  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** ne jamais présenter des mesures simulées comme réelles.  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/thermal-camera/STYLE.md)

