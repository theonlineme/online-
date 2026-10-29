# BashaVara.com — Demo Web App

A responsive Bengali rental-property marketplace demo built with React, Vite, and Lucide icons.

## Features
- Responsive landing page with rental search
- Filters for area, budget, bedrooms, and listing category
- Property cards and details view
- Favorites (in-memory for current session)
- Listing submission form (in-memory demo only)
- Bengali-first design, mobile bottom navigation, safety guidance

## Run locally
Requires Node.js 20+.

```bash
npm install
npm run dev
```

Open the local URL shown by Vite.

## Build
```bash
npm run build
npm run preview
```

## Important limitations
This is a front-end prototype. Listings and favorites are held in browser memory and reset on reload. Login, real contact/messaging, image uploads, admin moderation, database persistence, and AI features are not connected yet. Sample properties are illustrative demo listings and should not be presented as verified real-world rental offers. Before production, connect Firebase Authentication, Firestore, Cloud Storage, server-side validation, restrictive Security Rules, and an authorized admin workflow. Replace or verify all sample imagery and listing facts before public launch.
