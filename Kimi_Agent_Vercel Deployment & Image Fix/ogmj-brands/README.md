# OGMJ BRANDS - Vercel Deployment Ready

A self-service platform for founders, creators, and teams to build their brand globally.

## Features

- Business registration guidance
- Document checklists & links
- Brand identity tools
- AI content & automation
- Global launch readiness
- Secure dashboard tracking
- Social Media Auto-Booster (YouTube, Instagram, Facebook, Twitter/X, LinkedIn, TikTok)

## Deploy to Vercel

### Option 1: Deploy via Vercel CLI

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Login to Vercel:
```bash
vercel login
```

3. Deploy:
```bash
cd ogmj-brands
vercel --prod
```

### Option 2: Deploy via Git (Recommended)

1. Create a new GitHub repository
2. Push these files to the repository:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ogmj-brands.git
git push -u origin main
```

3. Import the project on [Vercel Dashboard](https://vercel.com/new)
4. Select your repository
5. Click "Deploy"

### Option 3: Deploy via Vercel Dashboard (Drag & Drop)

1. Go to [Vercel Dashboard](https://vercel.com/new)
2. Drag and drop the `ogmj-brands` folder
3. Click "Deploy"

## Project Structure

```
ogmj-brands/
├── index.html              # Main entry point
├── assets/
│   ├── index-DcB1PkSk.js   # Main JavaScript bundle
│   └── index-DDGdSTqv.css  # Main CSS bundle
├── vercel.json             # Vercel configuration
└── README.md               # This file
```

## Configuration

The `vercel.json` file includes:
- Proper routing for SPA (Single Page Application)
- Asset caching headers for optimal performance
- Framework-agnostic static deployment

## Live Website

Visit the live website at: https://adxadpnbobdju.ok.kimi.link/

## Support

- Email: ogmjbrandingagency@gmail.com
- WhatsApp: +234 810 972 0301
- Phone: +234 810 972 0301
