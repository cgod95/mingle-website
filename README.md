# Mingle Website

Marketing website for [Mingle](https://github.com/cgod95/mingle-synergy) - the dating app that gets you off the app.

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start dev server (port 4000)
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 🌐 Deployment

This site is designed for easy deployment to [Vercel](https://vercel.com):

1. Connect your GitHub repo to Vercel
2. Vercel auto-detects Astro and configures build settings
3. Deploy!

### Custom Domain

After deployment, add a custom domain in Vercel Dashboard → Settings → Domains.

## 📁 Structure

```
src/
├── components/     # Reusable components
│   ├── Header.astro
│   ├── Hero.astro
│   ├── HowItWorks.astro
│   ├── Features.astro
│   ├── Safety.astro
│   ├── FAQ.astro
│   ├── Waitlist.astro
│   └── Footer.astro
├── layouts/        # Page layouts
│   └── Layout.astro
├── pages/          # Route pages
│   ├── index.astro
│   ├── privacy.astro
│   ├── terms.astro
│   └── contact.astro
└── styles/         # Global styles
    └── global.css
```

## 🎨 Brand

- **Primary Color:** `#7C3AED` (Purple/Violet)
- **Background:** `#0A0A0F` (Dark)
- **Font:** Inter

## 📝 Pages

- `/` - Landing page with hero, features, FAQ, waitlist
- `/privacy` - Privacy Policy
- `/terms` - Terms of Service
- `/contact` - Contact information

## 🛠 Tech Stack

- [Astro](https://astro.build) - Static site generator
- [Tailwind CSS](https://tailwindcss.com) - Styling
- [TypeScript](https://www.typescriptlang.org) - Type safety

## 📄 License

Proprietary - All rights reserved.
