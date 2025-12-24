# Full-Stack Recipe App
## Tech Stack

- Frontend: React Native, Expo

- Backend: Express

- Database: PostgreSQL

- Authentication: Clerk
---
## Summary

- Secure user authentication with signup, login, and email verification (Clerk)

- Browse featured recipes and filter by categories

- Search recipes with detailed step-by-step instructions

- Integrated YouTube video tutorials on recipe pages

- Save and access favorite recipes via a dedicated Favorites tab

- Built with React Native, Express, PostgreSQL, and Expo

- Supports 8 customizable color themes

- Fully free tools, no paid services required

- Environment configuration via .env file

---
## .env Setup

## Backend (/backend)
```bash
PORT=5001
DATABASE_URL=your_neon_db_url
NODE_ENV=development
```
## Mobile App (/mobile)
```bash
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```
---
## Running the Backend
```bash
cd backend
npm install
npm run dev
```
## Running the Mobile App
```bash
cd mobile
npm install
npx expo start
```

