
# Hi there, I'm Bashar Maaz 👋

### 🚀 Full-Stack Software Engineer & Systems Architect

[![Next.js](https://img.shields.io/badge/Next.js-16-black?style=for-the-badge&logo=next.js&logoColor=white)](https://github.com/NinjaStackX)
[![TypeScript](https://img.shields.io/badge/TypeScript-Strict-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/NinjaStackX)
[![Linux Enthusiast](https://img.shields.io/badge/Linux-Enthusiast-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://github.com/NinjaStackX)

---

## 💫 About Me

- 🎓 **Informatics Engineering Student** based in **Aleppo, Syria**, specializing in **Full-Stack Software Engineering**.
- 🏗️ Focused on architecting scalable, enterprise-grade applications using **Layered Architecture (Repository-Service-Action)** and **Event-Driven Patterns**.
- ⚡ Deep passion for **Performance Engineering (100/100 Lighthouse scores)**, zero-CLS strategies, and type-safe systems.
- 🧩 Competitive programmer solving algorithmic challenges on **Codeforces** using **Python**.
- 🐧 **Linux Enthusiast** driven by clean architecture, strict type safety, and continuous technical growth.

---
## 🧠 Technical Arsenal
<h3><b>Frontend & UI Engineering</b></h3>
<p>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Shadcnui-000000?style=for-the-badge&logo=shadcnui&logoColor=white" />
  <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white" />
</p>

<h3><b>Backend, Database & State</b></h3>
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Zustand-443e38?style=for-the-badge&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/TanStack_Query_v5-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" />
</p>

<h3><b>DevOps, Tools & Architecture</b></h3>
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
</p>

---

## 🛠️ Featured Engineering Projects

### 🛒 [HQ-Store | Enterprise E-Commerce Platform](https://github.com/NinjaStackX/HQ_Store)
> Strict Service-Repository pattern built with Next.js 15 & Prisma to decouple Business Logic from Data Access.
- **Financial Integrity:** Precision pricing engine using `Decimal.js` and PostgreSQL `Decimal` types to eliminate floating-point calculation errors.
- **Concurrency Control:** Atomic Transactions on checkout preventing race conditions and guaranteeing 100% inventory accuracy under load.
- **Performance:** 100/100 Lighthouse scores achieved by tuning Critical Rendering Paths and building custom CSS-only UI primitives.

### 🍽️ [Bm.resto | DineOS | Real-Time Restaurant Management](https://github.com/NinjaStackX/DineOS)
> Full-stack event-driven management dashboard featuring WebSockets and persistent server hooks.
- **Event-Driven Workflow:** Node.js `EventEmitter` pipeline decoupling order transactions from side effects.
- **Real-Time Engine:** Integrated Pusher Channels with `Howler.js` to bypass browser autoplay constraints for instant order alerts.
- **Server Instrumentation:** Configured Next.js `instrumentation.ts` for server background initialization.

### 🌐 [Syrian Platform | Dynamic Multilingual Web Platform](https://github.com/NinjaStackX/sy-platform)
> RTL-First internationalization pipeline with zero layout shift during locale detection.
- **Localization:** Automated `i18next` integration with native RTL/LTR CSS switching and mirrored Framer Motion animations.
- **SSR & Hydration:** Resolved client/server hydration mismatches in Next.js layout layers, eliminating CLS completely.

### 🍫 [Melt-Choco | Animated Landing Page](https://github.com/NinjaStackX/Melt-Choco)
> A high-end, immersive landing page built with React, Tailwind CSS, and GSAP.
- **Advanced Animations:** Scroll-triggered dynamic image swapping, "hand-drawn" SVG path drawing, and precise letter-by-letter writing effects using SplitText.
- **Visual Depth:** Implemented smooth parallax depth effects and a physical stacking UI using React Array Refs and GSAP Stagger.

---

## 📐 Architectural Blueprint

```text
Client Session ➔ Server Action ➔ Business Service ➔ Database Transaction (Prisma) ➔ EventEmitter ➔ WebSockets (Pusher) ➔ Real-Time UI Update
