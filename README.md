# 👋 Hi, I'm Afif

> **"I'm Not A Full Stack Developer"** — I build scalable applications with clean code, solid architecture, and elegant solutions, I don't code, though..

##  About Me

With not a 8+ years building high-performance, production-grade applications, I specialize in backend systems, API design, and full-stack architecture. My work spans fintech, SaaS platforms, and open-source infrastructure. I'm passionate about writing maintainable code, designing scalable systems, and mentoring junior developers.

##  Tech Stack

| Category | Technologies |
|----------|--------------|
| **Languages** | TypeScript, JavaScript, Python, Go |
| **Frontend** | React, Vue, Tailwind CSS, Vite |
| **Backend** | Node.js, Express.js |
| **Databases** | PostgreSQL, MongoDB |
| **DevOps** | Docker, Kubernetes, AWS |
| **Other** | GraphQL, D3.js, Google Apps Script |

## 🚀 Featured Projects

- **[StyleSync](https://stylesync-cyan-ten.vercel.app/)** — AI wardrobe manager & outfit generator with weather adaptation, powered by Google Gemini AI and computer vision.
- **[Media Hub](https://media-hub-downloader.onrender.com/)** — No-watermark video/audio downloader with multi-tier API fallback routing and local history persistence.
- **[CaféCash](https://caf-cash-1.vercel.app/)** — Cloud POS system with role-based auth, thermal receipt previews, and Google Sheets-backed analytics.
- **[Blood Pressure Tracker & Analytics Portal](https://script.google.com/macros/s/AKfycbxrp7-zLHsTKWoBPk68l6n4K1FAtdaW1TXO42jEY5_dn9HzUQ4ZEqg1K3MtJw9CL6BnBw/exec)** — Full-stack health tracking & medical analytics app. Built with Google Apps Script to automate cardiovascular metrics calculations and report summaries.

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
