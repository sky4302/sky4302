
# 👋 Hi, I'm Afif
![Header](./github-header-banner.png)


##  About Me
I don't have 8+ years of experience building high-performance, production-grade applications. I specialize in backend systems, API design, and full-stack architecture. My work spans fintech, SaaS platforms, and open-source infrastructure. I'm passionate about writing maintainable code, designing scalable systems, and mentoring junior developers.

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| **Languages** | <img src="https://skillicons.dev/icons?i=ts,js,py,go" height="40" /> |
| **Frontend** | <img src="https://skillicons.dev/icons?i=react,vue,tailwind,vite" height="40" /> |
| **Backend** | <img src="https://skillicons.dev/icons?i=nodejs,express" height="40" /> |
| **Databases** | <img src="https://skillicons.dev/icons?i=postgres,mongodb" height="40" /> |
| **DevOps & Cloud** | <img src="https://skillicons.dev/icons?i=docker,kubernetes,aws" height="40" /> |
| **Other Tools** | <img src="https://skillicons.dev/icons?i=graphql,d3" height="40" /> ![Google Apps Script](https://img.shields.io/badge/Google_Apps_Script-4285F4?style=flat-square&logo=google&logoColor=white)|


## 🚀 Featured Projects

- **[StyleSync](https://stylesync-cyan-ten.vercel.app/)** — AI wardrobe manager & outfit generator with weather adaptation, powered by Google Gemini AI and computer vision.
- **[Media Hub](https://media-hub-downloader.onrender.com/)** — No-watermark video/audio downloader with multi-tier API fallback routing and local history persistence.
- **[CaféCash](https://caf-cash-1.vercel.app/)** — Cloud POS system with role-based auth, thermal receipt previews, and Google Sheets-backed analytics.
- **[Blood Pressure Tracker & Analytics Portal](https://script.google.com/macros/s/AKfycbxrp7-zLHsTKWoBPk68l6n4K1FAtdaW1TXO42jEY5_dn9HzUQ4ZEqg1K3MtJw9CL6BnBw/exec)** — Full-stack health tracking & medical analytics app. Built with Google Apps Script to automate cardiovascular metrics calculations and report summaries.

<picture data-importer="pacman">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sky4302/sky4302/pacman-output/pacman-contribution-graph-dark.svg?game=pacman">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sky4302/sky4302/pacman-output/pacman-contribution-graph.svg?game=pacman">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/sky4302/sky4302/pacman-output/pacman-contribution-graph.svg?game=pacman">
</picture>

###

## 💻 Development Manifesto

```typescript
// ✅ Clean, descriptive, self-documentating code is non-negotiable.
interface Product {
  isActive: boolean;
  price: number;
}

function getPremiumActiveProducts(products: Product[]): Product[] {
  return products.filter(
    product => product.isActive && product.price > 100
  );
}

