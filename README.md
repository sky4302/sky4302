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

- **[StyleSync](https://afif-portfolio-ten.vercel.app/)** — AI wardrobe manager & outfit generator with weather adaptation, powered by Google Gemini AI and computer vision.
- **[Media Hub](https://afif-portfolio-ten.vercel.app/)** — No-watermark video/audio downloader with multi-tier API fallback routing and local history persistence.
- **[CaféCash](https://afif-portfolio-ten.vercel.app/)** — Cloud POS system with role-based auth, thermal receipt previews, and Google Sheets-backed analytics.
- **[Digital Class Yearbook](https://afif-portfolio-ten.vercel.app/)** — Interactive memories portal with serverless proxy routing to Google Apps Script.
- **[Skyaether](https://afif-portfolio-ten.vercel.app/)** — Premium coffee brand landing page with glassmorphism UI and single-file bundle optimization.

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
