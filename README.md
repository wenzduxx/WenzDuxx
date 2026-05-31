<div align="center">

# 👋 Halo, Saya WenzDuxx

### Full-Stack Engineer · AI Product Builder · Web GIS & EdTech Enthusiast

_Membangun produk yang menggabungkan **AI**, **data**, dan **desain editorial** untuk domain pendidikan, perpustakaan, pertanian presisi, dan portofolio digital._

<br>

[![Email](https://img.shields.io/badge/Email-haris.emailtugas@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:haris.emailtugas@gmail.com)
[![Stack](https://img.shields.io/badge/Stack-Full--Stack%20%2B%20AI-7B61FF?style=flat-square)]()
[![Region](https://img.shields.io/badge/Region-Indonesia-FF4B4B?style=flat-square)]()

</div>

---

## 🧠 Filosofi Engineering

> **Ship product, bukan tutorial.** Setiap repo di bawah ini adalah produk nyata — bukan boilerplate. Saya fokus pada **arsitektur yang masuk akal**, **AI yang punya guardrail** (RAG + multi-provider fallback, bukan halusinasi mentah), dan **UX yang tidak terasa di-generate**.

```
domain expertise → AI augmentation → production hardening → editorial polish
```

---

## 🛠️ Tech Stack

### Languages

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite_6-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP_3-88CE02?style=flat-square&logo=greensock&logoColor=black)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)

### Backend

![Node.js](https://img.shields.io/badge/Node.js_20-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express_4-000000?style=flat-square&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma_5-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io_4-010101?style=flat-square&logo=socketdotio&logoColor=white)
![PHP](https://img.shields.io/badge/PHP_8-777BB4?style=flat-square&logo=php&logoColor=white)

### Database & Infrastructure

![PostgreSQL](https://img.shields.io/badge/PostgreSQL_16-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

### AI / LLM

![Anthropic](https://img.shields.io/badge/Anthropic_Claude-D4A373?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=lightning&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)

---

## 📦 Project Portfolio

### 1. 🎓 **ExamHub** — Web Ujian Aman & Pintar

> Platform ujian online full-stack dengan **AI question generator**, **live anti-cheat monitoring**, dan **real-time WebSocket telemetry**.

| Layer      | Stack                                                                     |
| ---------- | ------------------------------------------------------------------------- |
| Frontend   | React 19 · TypeScript · Vite 6 · TailwindCSS 4 · Recharts · Motion        |
| Backend    | Express 4 · Node 20 · TypeScript · Zod · JWT + bcrypt                     |
| Realtime   | Socket.io 4 (room: `exam:{id}`, `monitor:{id}`, `student:{uid}`)          |
| Database   | PostgreSQL 14 · Prisma 5 (9 model: User/Exam/Question/Session/CheatLog/…) |
| AI         | Google Gemini 3.5 Flash — auto-generate MCQ + Question Polish             |
| Arsitektur | **Monolith** — Express serve React build, Vite HMR middleware saat dev    |

**Modul Inti:** Dashboard Pendidik · ExamMaker AI · Live Monitoring · 9 parameter anti-cheat per ujian · Audit log · Auto-grading · Multi-role (Teacher / Student / Admin).

---

### 2. 📚 **PerpusAI** — AI-Powered Digital Library Ecosystem

> Ekosistem perpustakaan AI dengan **RAG anti-halusinasi**, **multi-provider LLM fallback chain**, dan **sistem subscription Midtrans**.

| Sub-Project                    | Stack & Karakter                                                                                                                                             |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Smart Library AI – Groq** ⭐ | _Flagship._ Node + Express + Prisma + Postgres · Groq default → Claude/GPT/Gemini/DeepSeek fallback · Supabase Storage · Midtrans Snap · node-cron scheduler |
| **Smart Library AI**           | Varian Pinecone — vector DB eksternal · Gemini primary                                                                                                       |
| **perpusai-build**             | Frontend-only SPA · Claude opsional · Fallback mode offline · Citation generator (APA/IEEE/BibTeX)                                                           |
| **titik-baca-project**         | PWA offline-first untuk **Raspberry Pi** sebagai WiFi AP komunitas · PHP 8 + MariaDB · EPUB/PDF/MP3/MP4/CBZ reader · IndexedDB                               |

**AI Tools terintegrasi:** `/rangkum` · `/sitasi` · `/bandingkan` · `/kuis` · `/jelaskan` · `/terjemah` · Report Generator → DOCX/PDF.

---

### 3. 🌾 **SawahScan AI** — Web GIS Pemantauan Sawah

> Platform GIS untuk monitoring kesehatan padi dari **citra drone multispektral** (RGB + YOLO + NDVI Red/NIR).

| Komponen   | Detail                                                                                 |
| ---------- | -------------------------------------------------------------------------------------- |
| Backend    | Node 20 · Express 4 · TypeScript · Prisma · JWT                                        |
| Frontend   | React 19 · Vite 6 · Tailwind 4 · Leaflet + OpenStreetMap · GSAP + Lenis                |
| AI         | Pipeline eksternal (Kaggle/YOLO/NDVI) + Google Gemini untuk insight                    |
| Database   | PostgreSQL 16                                                                          |
| Deployment | **Docker Compose** — 3 service (db/backend/frontend) · volume persisten · auto-migrate |

```
┌──────────┐    ┌──────────┐    ┌──────────┐
  frontend  ───▶ backend  ───▶   db
   :3000          :8000           :5432
└──────────┘    └──────────┘    └──────────┘
              sawahscan_net (bridge)
```

**Fitur:** Dashboard agregat · Map interaktif per sektor · 4 jenis citra per upload · Diagnostik historis · Export CSV/JSON.

---

### 4. 🎫 **UniPortal** — Web Absensi Pintar Kampus

> Sistem absensi universitas berbasis **QR sesi waktu-terbatas** dengan analitik lengkap & RBAC.

| Varian                | Stack                                                                                                |
| --------------------- | ---------------------------------------------------------------------------------------------------- |
| **Advanced Ver.1**    | React 18 + Vite 6 · React Router 7 · GSAP · OGL WebGL · Recharts · jsPDF · SheetJS · Cloud Functions |
| **Firebase_BE Ver.1** | Next.js 16 (App Router) · React 19 · Framer Motion · SSR-first                                       |

**Backend:** Firebase Auth + Cloud Firestore · **RBAC:** Admin / Lecturer / Public / Student.

**Fitur:** QR check-in time-bound · Bulk CSV/Excel import · Calendar heatmap · KPI cards · Distribusi per jurusan · Export PDF/Excel · ⌘K command palette · WebGL landing.

---

### 5. 🎨 **Portfolio Sites** — Editorial & Cinematic Web

> Dua portofolio personal dengan pendekatan desain berbeda, keduanya **Supabase-backed CMS** + back-office terkustom.

| Project                         | Vibe & Tech Highlights                                                                                                                      |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **atelier-nocturne**            | Editorial · charcoal + gold · Noto Serif + Manrope · React 19 + Motion · admin `/atelier-studio`                                            |
| **dark-portfolio-landing-page** | Cinematic · WebGL aurora (Three.js + @react-three/fiber + OGL) · GSAP timelines · HLS streaming · ambient audio engine · admin `/bts-porto` |

Keduanya: Vercel deploy · Supabase Postgres + Auth + Storage + Realtime · live preview iframe untuk back-office.

---

## 🏗️ Arsitektur yang Saya Gunakan

```
┌─────────────────────────────────────────────────────────────┐
│  CLIENT  React 19 / Next.js · TypeScript · Tailwind v4      │
│          GSAP · Motion · Three.js · Lenis · shadcn-style    │
└──────────────────────────┬──────────────────────────────────┘
                           │  REST + WebSocket (Socket.io)
┌──────────────────────────▼──────────────────────────────────┐
│  API     Express 4 / Next.js Route Handlers · Zod · JWT     │
│          bcrypt · Helmet · Rate-limit · node-cron           │
└──────────────────────────┬──────────────────────────────────┘
                           │  Prisma 5  /  Firebase SDK
┌──────────────────────────▼──────────────────────────────────┐
│  DATA    PostgreSQL · Firestore · MariaDB · Supabase        │
│  STORE   Supabase Storage · local fs · IndexedDB (PWA)      │
└──────────────────────────┬──────────────────────────────────┘
                           │
┌──────────────────────────▼──────────────────────────────────┐
│  AI      Groq · Claude · GPT-4 · Gemini · DeepSeek          │
│  LAYER   Multi-provider fallback · Keyword/Pinecone RAG     │
└─────────────────────────────────────────────────────────────┘
```

**Pola arsitektur yang sering saya pakai:**

- 🧱 **Monolith TypeScript** (Express + Vite SSR-middleware) untuk produk solo/tim kecil
- 🐳 **Docker Compose** untuk reproducible local + deployable VPS
- 🔌 **Provider abstraction** untuk LLM — _tidak vendor-lock_, ada fallback chain
- 🛡️ **Guardrail-first AI** — RAG dengan retrieval keyword/vector sebelum hit LLM
- 🎨 **Design tokens** + Tailwind v4 + custom CSS variables untuk konsistensi visual

---

## 🎯 Domain Expertise

| Domain                 | Pengalaman                                                                |
| ---------------------- | ------------------------------------------------------------------------- |
| 🎓 **EdTech**          | Online assessment, anti-cheat telemetry, AI question generation           |
| 📚 **Digital Library** | RAG, citation engine, multi-format reader (PDF/EPUB/MP3/CBZ), offline PWA |
| 🌾 **AgriTech / GIS**  | Multispectral analysis, Leaflet GIS, sector diagnostics                   |
| 🎫 **Campus SaaS**     | RBAC, QR sessions, attendance analytics, bulk data ingestion              |
| 🎨 **Editorial Web**   | Cinematic UX, WebGL, headless CMS, motion-driven storytelling             |

---

## 📊 Stats Singkat

<div align="center">

| Metric                         | Count                                               |
| ------------------------------ | --------------------------------------------------- |
| Produk full-stack di portfolio | **5** project induk · **11** repo sub-project       |
| LLM provider terintegrasi      | **5** (Groq · Claude · GPT-4 · Gemini · DeepSeek)   |
| Stack utama                    | TypeScript · React · Node · Postgres · Prisma       |
| Pola backend                   | Monolith TS · Next.js SSR · PHP MVC · Firebase BaaS |

</div>

---

<div align="center">

### 📬 Mari Berkolaborasi

Punya ide produk yang butuh **AI grounding**, **arsitektur full-stack**, atau **UX editorial**?

**[haris.emailtugas@gmail.com](mailto:haris.emailtugas@gmail.com)**

<sub><i>README ini di-generate dari struktur folder kerja lokal — semua proyek di atas adalah implementasi nyata, bukan demo.</i></sub>

</div>
