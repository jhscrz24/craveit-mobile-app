# CraveIt - Recipe Finder Mobile App

![Demo App](/mobile/assets/images//for-readme.png)

Highlights:

- Secure signup, login, and 6-digit email verification powered by Clerk
- Explore featured recipes and filter them by category
- Easily search for recipes and view step-by-step cooking instructions
- Each recipe includes an embedded YouTube tutorial
- Offers 8 customizable color themes
- Built with React Native, Express, PostgreSQL, and Expo
  
---

## .env Setup

### Backend

```bash
PORT=5001
DATABASE_URL=your_neon_db_url
NODE_ENV=development
```

### Mobile App

```bash
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

---

## Run the Backend

```bash
cd backend
npm install
npm run dev
```

## Run the Mobile App

```bash
cd mobile
npm install
npx expo start
```
