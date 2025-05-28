
# 🌸 WuluAnime

A full-featured, sakura-themed anime & manga platform inspired by MyAnimeList and Azuki, built with Next.js, Tailwind CSS, Prisma, and PostgreSQL.

## 🌟 Features
- Email/password authentication
- Anime & Manga catalog (via Jikan API)
- Streaming mock view
- Rating and comment system
- Custom mascot and Sakura background
- Ready for deployment on Vercel

## 🚀 Deploy Instructions
1. Set up PostgreSQL (e.g., Railway)
2. Add `.env` with:
   ```
   DATABASE_URL=postgresql://...
   NEXTAUTH_SECRET=...
   NEXTAUTH_URL=http://localhost:3000
   ```
3. Run:
   ```bash
   npx prisma db push
   npm run dev
   ```

## 📸 Preview
![](public/screenshot.jpg)
