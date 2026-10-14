# ⚡ Modern Web Animations & Geometric UI Showcase

[![Next.js](https://img.shields.io/badge/Next.js-16.0-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4.0-06B6D4?style=for-the-badge&logo=tailwindcss)](https://tailwindcss.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![FPS](https://img.shields.io/badge/Performance-60_FPS_GPU-brightgreen?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/Performance)

> A modern, interactive web application exploring **GPU-accelerated CSS animations**, kinetic geometry, and fluid micro-interactions built with **Next.js 16 (App Router)**, **React 19**, and **Tailwind CSS v4**.

---

## 🌟 Key Highlights & Engineering Features

- **⚡ 60 FPS Hardware Acceleration:** Leverages composite-only CSS properties (`transform`, `rotate`, `opacity`) to offload rendering directly to the GPU, preventing layout thrashing and main-thread CPU spikes.
- **📐 Kinetic Pendulum & Geometric Simulations:** Pure CSS keyframe physics simulating perpetual harmonic oscillation, mechanical pivot dynamics, and shape masking.
- **🚀 Next.js 16 & React 19 Architecture:** Built with the latest App Router paradigms, modern React component structures, and modular styling.
- **🎨 Tailwind CSS v4 Engine:** Powered by Tailwind v4's high-speed CSS compiler with modern CSS variable bindings and zero-runtime overhead.
- **📱 Fully Responsive Layouts:** Dynamic viewport scaling across mobile, tablet, and ultra-wide desktop displays.

---

## 🛠️ Tech Stack & Tooling

| Layer | Technology | Purpose |
| :--- | :--- | :--- |
| **Framework** | Next.js 16 (App Router) | Server-side rendering & client-side hydration |
| **UI Library** | React 19 | Modular component state & lifecycle |
| **Styling** | Tailwind CSS v4 + Pure CSS3 | Hardware-accelerated animations & responsive utility classes |
| **Language** | TypeScript 5 | End-to-end type safety & developer ergonomics |
| **Package Manager**| pnpm / npm | Fast, deterministic dependency management |

---

## 📂 Project Structure

```bash
animations-showcase/
├── app/
│   ├── globals.css      # Pure CSS keyframe animations & Tailwind v4 config
│   ├── layout.tsx       # Root layout & meta tags
│   └── page.tsx         # Interactive animation stage & geometry containers
├── public/              # Static assets & icons
├── next.config.ts       # Next.js 16 compiler configuration
├── tsconfig.json        # TypeScript configuration
└── package.json         # Project dependencies & scripts
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18.17+ or 20+
- pnpm / npm / yarn

### Installation & Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/dineshv-career/animations-showcase.git
   cd animations-showcase
   ```

2. **Install dependencies:**
   ```bash
   pnpm install
   # or
   npm install
   ```

3. **Start the development server:**
   ```bash
   pnpm dev
   # or
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to view the live animations.

---

## 👤 Author

**Dinesh V**  
*Front-End & Full-Stack Engineer (React.js, Next.js, TypeScript)*  
- 💼 **LinkedIn:** [@dineshv01](https://www.linkedin.com/in/dineshv01/)
- 🌐 **Portfolio:** [dineshv.dev](https://portfolio-two-nu-r4oabmptbo.vercel.app/)
- 🐙 **GitHub:** [@dineshv-career](https://github.com/dineshv-career)
- 📧 **Email:** [dineshv.career@gmail.com](mailto:dineshv.career@gmail.com)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
