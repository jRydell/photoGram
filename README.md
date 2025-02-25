# React, TypeScript & Firebase - Social Media App

## Om projektet

Detta projekt är baserat på en tutorial av Dipesh Malvia och demonstrerar hur man bygger en fullstack social media-app med React, TypeScript och Firebase.

## Teknologier och verktyg

- **React**
- **TypeScript**
- **Firebase**
  - Authentication
  - Firestore Database
  - Hosting
  - Firestore Rules
- **ShadCN UI**
- **TailwindCSS**
- **Uploadcare**

## Funktionalitet

- Användarautentisering med Firebase Authentication
- CRUD-operationer med Firestore
- Uppladdning och hämtning av bilder via Uploadcare
- Regler för dataskydd i Firestore
- Deployment och hosting med Firebase

## Installation och körning

1. Klona repot:
   ```bash
   git clone <repo-url>
   cd <projektmapp>
   ```
2. Installera dependencies:
   ```bash
   npm install
   ```
3. Konfigurera Firebase:
   - Skapa ett Firebase-projekt
   - Aktivera Authentication och Firestore
   - Lägg till konfigurationsuppgifterna i en `.env`-fil
4. Starta utvecklingsservern:
   ```bash
   npm run dev
   ```

## Deployment

För att deploya till Firebase Hosting:

```bash
npm run build
firebase deploy
```

## 📜 Källa

Tutorial: [YouTube-video](https://www.youtube.com/watch?v=<tutorial-video-url>)

---
