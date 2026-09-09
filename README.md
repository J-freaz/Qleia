# Qleïa — Maquette lounge interactive

Proposition indépendante de modernisation de l’accueil de Qleïa.

## Fonctionnalités
- Zoom doux au survol des cinq membres de l’équipe.
- Fiches avec fonctions, descriptions et coordonnées professionnelles publiées sur https://www.qleia.com/equipe.
- Présentation automatique, sélection tactile et navigation au clavier.
- Réduction des animations.

Le salon et les poses sont une mise en scène générée à partir des portraits officiels. L’effet de profondeur anime une image ; il ne s’agit pas de personnages 3D. Les liens Acheter et Louer renvoient actuellement à l’accueil du site officiel. Aucun formulaire, agenda ou assistant conversationnel n’est connecté.

## Lancer le projet
Node.js >= 22.13 et pnpm 11.19.0.

```sh
pnpm install
pnpm run dev
```

Ouvrir l’adresse indiquée par le serveur.

```sh
pnpm run build
pnpm run start
```

Le projet utilise React, Vinext et Cloudflare Workers. Le dépôt GitHub conserve le code ; sa création ne publie pas automatiquement un site GitHub Pages.

## Hébergement existant
La configuration `.openai/hosting.json` identifie la maquette Sites existante. Cet identifiant n’est pas un secret et ne confère aucun accès. Ne pas le réutiliser pour créer un projet indépendant.

Aucun mot de passe, jeton, fichier .env, historique Git ou dépendance installée n’est inclus dans cet export.

## Contenu et droits
Les portraits et informations de l’équipe proviennent du site Qleïa, consulté le 9 septembre 2026. Cet export n’accorde aucune licence sur la marque ou les portraits. Proposition de présentation indépendante, non présentée comme un site officiel.
