# 15 · Données & cartes

[← Tous les styles](../README.md#les-110-styles) · 6 styles

- [Visualisation de données](#visualisation-de-données)
- [Projection sur maquette blanche](#projection-sur-maquette-blanche)
- [Données matérialisées](#données-matérialisées)
- [Plan de transport graphique](#plan-de-transport-graphique)
- [Carte explicative 3D](#carte-explicative-3d)
- [Simulation de petits agents](#simulation-de-petits-agents)

## Visualisation de données

**Rendu :** graphiques de données d'exemple signalées comme démonstration.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Visualisation de données » : graphiques de données d'exemple signalées comme démonstration.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] fait apparaître deux barres de données fictives.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Visualisation de données » (graphiques de données d'exemple signalées comme démonstration).
Action unique et complète : [PERSONNAGE] fait apparaître deux barres de données fictives — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : données qui se construisent, cartes qui se déplient, trajets animés.
Caméra : vue de dessus ou 3/4, mouvements lents.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Visualisation de données » : graphiques de données d'exemple signalées comme démonstration.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] fait apparaître deux barres de données fictives (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : données qui se construisent, cartes qui se déplient, trajets animés. Caméra : vue de dessus ou 3/4, mouvements lents.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** données qui se construisent, cartes qui se déplient, trajets animés.  
**Caméra :** vue de dessus ou 3/4, mouvements lents.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** utiliser des données réelles et citer la source, ou indiquer « simulation fictive ».  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/dataviz/STYLE.md)

## Projection sur maquette blanche

**Rendu :** modèle blanc éclairé par des couches de projection géométriques.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Projection sur maquette blanche » : modèle blanc éclairé par des couches de projection géométriques.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] projette un motif sur une ville miniature générique.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Projection sur maquette blanche » (modèle blanc éclairé par des couches de projection géométriques).
Action unique et complète : [PERSONNAGE] projette un motif sur une ville miniature générique — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : données qui se construisent, cartes qui se déplient, trajets animés.
Caméra : vue de dessus ou 3/4, mouvements lents.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Projection sur maquette blanche » : modèle blanc éclairé par des couches de projection géométriques.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] projette un motif sur une ville miniature générique (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : données qui se construisent, cartes qui se déplient, trajets animés. Caméra : vue de dessus ou 3/4, mouvements lents.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** données qui se construisent, cartes qui se déplient, trajets animés.  
**Caméra :** vue de dessus ou 3/4, mouvements lents.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** utiliser des données réelles et citer la source, ou indiquer « simulation fictive ».  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/white-model/STYLE.md)

## Données matérialisées

**Rendu :** quantités fictives traduites en objets physiques à échelle constante.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Données matérialisées » : quantités fictives traduites en objets physiques à échelle constante.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] empile des cubes à partir d'un jeu de données d'exemple.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Données matérialisées » (quantités fictives traduites en objets physiques à échelle constante).
Action unique et complète : [PERSONNAGE] empile des cubes à partir d'un jeu de données d'exemple — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : données qui se construisent, cartes qui se déplient, trajets animés.
Caméra : vue de dessus ou 3/4, mouvements lents.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Données matérialisées » : quantités fictives traduites en objets physiques à échelle constante.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] empile des cubes à partir d'un jeu de données d'exemple (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : données qui se construisent, cartes qui se déplient, trajets animés. Caméra : vue de dessus ou 3/4, mouvements lents.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** données qui se construisent, cartes qui se déplient, trajets animés.  
**Caméra :** vue de dessus ou 3/4, mouvements lents.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** utiliser des données réelles et citer la source, ou indiquer « simulation fictive ».  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/data-physical/STYLE.md)

## Plan de transport graphique

**Rendu :** lignes schématiques de réseau inventé, stations et correspondances lisibles.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Plan de transport graphique » : lignes schématiques de réseau inventé, stations et correspondances lisibles.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] suit une ligne entre trois stations imaginaires.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Plan de transport graphique » (lignes schématiques de réseau inventé, stations et correspondances lisibles).
Action unique et complète : [PERSONNAGE] suit une ligne entre trois stations imaginaires — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : données qui se construisent, cartes qui se déplient, trajets animés.
Caméra : vue de dessus ou 3/4, mouvements lents.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Plan de transport graphique » : lignes schématiques de réseau inventé, stations et correspondances lisibles.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] suit une ligne entre trois stations imaginaires (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : données qui se construisent, cartes qui se déplient, trajets animés. Caméra : vue de dessus ou 3/4, mouvements lents.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** données qui se construisent, cartes qui se déplient, trajets animés.  
**Caméra :** vue de dessus ou 3/4, mouvements lents.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** utiliser des données réelles et citer la source, ou indiquer « simulation fictive ».  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/transit-map/STYLE.md)

## Carte explicative 3D

**Rendu :** relief simplifié, caméra topographique et annotations neutres.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Carte explicative 3D » : relief simplifié, caméra topographique et annotations neutres.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] fait tourner une carte d'un archipel fictif.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Carte explicative 3D » (relief simplifié, caméra topographique et annotations neutres).
Action unique et complète : [PERSONNAGE] fait tourner une carte d'un archipel fictif — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : données qui se construisent, cartes qui se déplient, trajets animés.
Caméra : vue de dessus ou 3/4, mouvements lents.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Carte explicative 3D » : relief simplifié, caméra topographique et annotations neutres.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] fait tourner une carte d'un archipel fictif (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : données qui se construisent, cartes qui se déplient, trajets animés. Caméra : vue de dessus ou 3/4, mouvements lents.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** données qui se construisent, cartes qui se déplient, trajets animés.  
**Caméra :** vue de dessus ou 3/4, mouvements lents.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** utiliser des données réelles et citer la source, ou indiquer « simulation fictive ».  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/map-explainer/STYLE.md)

## Simulation de petits agents

**Rendu :** multiples personnages abstraits suivant règles explicites simulées.

**1. Prompt image** (remplace les crochets)

```text
Image verticale 9:16. Style « Simulation de petits agents » : multiples personnages abstraits suivant règles explicites simulées.
Sujet : [PERSONNAGE — décris-le en une phrase : silhouette, couleurs, vêtements, signe distinctif], dans [SCÈNE — lieu, moment, lumière].
Moment représenté : juste avant l'action — [PERSONNAGE] lance deux populations de petits points et compare leur parcours.
Composition lisible sur téléphone : personnage entier ou jusqu'aux genoux, mains visibles, silhouette claire, décor et objets originaux, éclairage cohérent avec le style.
À éviter : texte ou lettres générés, logos et marques, personnages existants, membres en trop, visage déformé.
```

**2. Prompt animation** (à partir de l'image obtenue)

```text
À partir de l'image fournie, crée un plan vertical de 3 à 5 secondes dans le style « Simulation de petits agents » (multiples personnages abstraits suivant règles explicites simulées).
Action unique et complète : [PERSONNAGE] lance deux populations de petits points et compare leur parcours — avec une préparation du geste, le contact, la conséquence visible et une réaction.
Mouvement : données qui se construisent, cartes qui se déplient, trajets animés.
Caméra : vue de dessus ou 3/4, mouvements lents.
Garde le même personnage, les mêmes couleurs et les mêmes proportions du début à la fin ; aucun texte, aucun logo.
```

**3. Prompt pour l'animer en code** (Claude Code, ChatGPT, Codex…)

```text
Tu es un développeur d'animation. Avec Remotion (React) ou Three.js, crée une animation verticale 1080×1920 de 5 secondes à 30 i/s dans le style « Simulation de petits agents » : multiples personnages abstraits suivant règles explicites simulées.
Personnage : [PERSONNAGE — formes simples à construire en code, couleurs principales]. Scène : [SCÈNE].
Action : [PERSONNAGE] lance deux populations de petits points et compare leur parcours (préparation, geste, conséquence, réaction ; le personnage se déplace et ses membres bougent, pas seulement la caméra).
Mouvement : données qui se construisent, cartes qui se déplient, trajets animés. Caméra : vue de dessus ou 3/4, mouvements lents.
Contraintes : rendu déterministe (aucun Math.random non initialisé), aucune ressource payante ni téléchargement, pas de texte généré dans l'image, code commenté et une commande pour exporter le MP4.
```

**Mouvement :** données qui se construisent, cartes qui se déplient, trajets animés.  
**Caméra :** vue de dessus ou 3/4, mouvements lents.  
**Outils :** générateur d'images puis image-vers-vidéo, ou motion design / 3D.  
**Limites :** utiliser des données réelles et citer la source, ou indiquer « simulation fictive ».  
**Statut :** prompt préparé, non testé.  
**Référence de style :** [Lemo-Opuscar](https://github.com/lemomo-ai/lemo-opuscar/blob/main/styles/pip-simulation/STYLE.md)

