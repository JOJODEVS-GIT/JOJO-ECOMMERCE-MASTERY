# Jojo E-Commerce Mastery

Plateforme de formation e-commerce complète. Dashboard interactif, modules de cours, quiz, système de progression et intégration IA.

Développé par **[@JOJODEVS-GIT](https://github.com/JOJODEVS-GIT)**

---

## Fonctionnalités

- **Dashboard** personnalisé avec suivi de progression
- **Modules de formation** : Fondations, Shopify, Facebook Ads, Marketing, Sourcing
- **Quiz** interactifs avec scoring
- **Leaderboard** et classement
- **Certificats** de complétion
- **Ressources** : Outils, APIs, Prompts, Produits Gagnants, Cas Pratiques, Checklists
- **Workspace** collaboratif avec CRM intégré
- **Plan d'étude** et roadmap personnalisés
- **Notes** et favoris
- **Intégration Gemini AI** pour l'assistance
- **Système d'abonnement** et tarification
- **Panel admin**
- Dark mode

## Stack

- **React 19** + **TypeScript**
- **Vite** — Build tool
- **React Router 7** — Routing
- **Zustand** — State management
- **Tailwind CSS** — Styling
- **Lucide React** — Icônes
- **Google Gemini AI** — Assistant IA
- **Vitest** — Tests unitaires

## Architecture

```
src/
├── app/          # Router, routes, guards
├── components/   # UI, layout, features
├── features/     # Auth, workspace
├── pages/        # Toutes les pages (20+)
├── services/     # Auth, analytics, Gemini, storage
├── stores/       # Zustand stores (progress, subscription, theme...)
├── types/        # TypeScript types
└── utils/        # Constants, helpers
```

## Lancer le projet

```bash
npm install
npm run dev
```

## Tests

```bash
npm test
npm run test:unit
npm run test:coverage
```

## Licence

Tous droits réservés.
