# Frost Esports Tournament Signup

Deployable React/Vite website for Frost Esports Overwatch tournament registration.

## Run locally

```bash
npm install
npm run dev
```

## Build for production

```bash
npm run build
```

## Deploy

Upload this folder to Vercel, Netlify, or any host that supports Vite/React.

## Current features

- Frost Esports Overwatch signup page
- Team details section
- Required field validation
- Player roster fields
- Add/remove substitutes
- Add/remove coach
- Exclusive captain logic
  - Add only one separate captain
  - Mark only one player/substitute as captain
  - Cannot use separate captain and player captain at the same time
- Required acknowledgements
- Substitute acknowledgement disappears once a substitute is added
- Submitted confirmation page
- Frost Discord help link
