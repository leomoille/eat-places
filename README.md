# Eat Places

Modernisation d'un projet de recherche de lieux où manger, pensé à l'origine pour une soutenance OpenClassrooms et désormais remis au goût du jour avec l'écosystème Next.js 15.

## Objectifs

- Moderniser l'application en utilisant les versions récentes de React et Next.js.
- Consolider l'intégration avec l'écosystème Google Cloud (Maps & Places).
- Poser les bases d'une vitrine technique facilement déployable.

## Stack & services

- Next.js 15 (App Router, TypeScript)
- shadcn/ui
- Google Cloud Platform
  - Google Maps JavaScript API
  - Google Places API

## Prérequis

- Node.js 20 LTS recommandé (min. 18.18 pour Next.js 15)
- npm 10+
- Un compte Google Cloud avec une clé API Maps/Places (une fois l'intégration activée)

## Installation

```bash
git clone https://github.com/leomoille/eat-places.git
cd eat-places
npm install
```

Créez ensuite un fichier `.env.local` :

```env
GOOGLE_MAPS_API_KEY=your-api-key
GOOGLE_PLACES_API_KEY=your-api-key
```

## Commandes disponibles

- `npm run dev` : lance le serveur de développement Next.js (Turbopack).
- `npm run build` : génère la version de production.
- `npm start` : démarre l'application en production après un `build`.

## Ressources

- [Documentation Next.js](https://nextjs.org/docs)
- [Google Maps JavaScript API](https://developers.google.com/maps/documentation/javascript?hl=fr)
- [Google Places API](https://developers.google.com/maps/documentation/places/web-service?hl=fr)
