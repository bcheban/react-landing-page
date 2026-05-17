<p align="center">
  <img src="https://raw.githubusercontent.com/bcheban/react-landing-page/main/public/vite.svg" alt="EdgeAI Landing Page Logo" width="120" />
</p>

<h1 align="center">EdgeAI — React Landing Page</h1>

<p align="center">
  <strong>A modern, fully responsive AI-product landing page built with React 19, TypeScript, and Tailwind CSS 4.</strong>
</p>

<p align="center">
  <a href="https://react-landing-page-ivory-one.vercel.app">Live Demo</a> |
  <a href="https://github.com/bcheban/react-landing-page">GitHub Repo</a>
</p>

---

## 📌 Project Overview

**EdgeAI** is a polished single-page marketing site built with **React 19** and **TypeScript**, styled with **Tailwind CSS 4**, and powered by **Vite 7** for a fast dev experience.  
It is structured as a classic SaaS-style landing page with clearly defined sections — Hero, Brands, Services, About Us, Pricing, and a final Call-to-Action — wrapped in a shared layout with consistent header and footer.

Global theme state (light/dark) is managed with **Zustand**, and section data (services, pricing plans) is kept in dedicated TypeScript modules so content is easy to update without touching markup.

---

## 🚀 Features

- **🦸 Hero Section** – Headline, subheadline, and primary call-to-action to introduce the product.
- **🏢 Brands Section** – Logo strip highlighting partner / customer brands.
- **🧩 Services Section** – Cards describing core services, sourced from typed data (`services-data.tsx`).
- **👥 About Us Section** – Mission and value statement for the product.
- **💰 Pricing Section** – Tiered pricing plans rendered from typed config (`pricing-plan.ts`).
- **📣 Call-to-Action Section** – Final conversion-focused block before the footer.
- **🌗 Light / Dark Theme** – Global theme switching powered by Zustand store.
- **🧱 Shared Layout** – Reusable header, footer, and page shell via the `Layout` component.
- **🧰 Modular Architecture** – Split into `sections`, `cards`, `elements`, and `shared` component folders.
- **🔒 Type-Safe** – Written end-to-end in TypeScript with strict ESLint rules.
- **📱 Fully Responsive** – Mobile-first design, optimized for all screen sizes.

---

## 🛠 Tech Stack

### Core Framework & Build Tools
<p>
  <img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React 19" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Vite_7-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite 7" />
</p>

### Styling
<p>
  <img src="https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS 4" />
  <img src="https://img.shields.io/badge/@tailwindcss_vite-0A74DA?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="@tailwindcss/vite" />
</p>

### State Management
<p>
  <img src="https://img.shields.io/badge/Zustand-2C2C2C?style=for-the-badge&logo=react&logoColor=white" alt="Zustand" />
</p>

### Tooling
<p>
  <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" alt="ESLint" />
  <img src="https://img.shields.io/badge/typescript--eslint-1E293B?style=for-the-badge&logo=typescript&logoColor=white" alt="typescript-eslint" />
</p>

### Deployment
<p>
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
</p>
