# Võ Văn Việt

Mobile and full-stack developer in Đà Nẵng, Việt Nam. React Native on the front, Laravel behind it.

Close to three years of continuous commercial experience. Sole author of four shipped React Native
codebases — one of them live today on both the App Store and Google Play. I build the mobile client
end to end and contribute the API behind it, so I can own a product surface from schema to store
release without the work being split up first.

[Portfolio](https://wdevvn.vercel.app/about) ·
[Blog](https://wdevvn.vercel.app/blog) ·
[Email](mailto:vietvo371@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/vo-van-viet-3b54a5266)

---

## Experience

### Full-Stack Developer — DZFULLSTACK Joint Stock Company
**Jul 2026 – present** · `React Native 0.80` `React 19` `Laravel 13` `PHP 8.3` `Stripe` `Firebase` `AWS`

**VietEntry** — Vietnam e-visa and travel app, [live on the App Store and Google Play](https://vietentry.com).
Sole developer of the mobile client; co-own the Laravel API with one other engineer.

- Stripe payments, Firebase Cloud Messaging with Notifee for push, Google and Apple sign-in
- On-device passport OCR via ML Kit that auto-fills the e-visa form, offline-first document storage
- Full localisation across English, Vietnamese, Japanese, Korean and Chinese
- Backend: JWT and Sanctum auth, Stripe integration, translatable content models, Excel export,
  AWS services, and AI-assisted features on the Anthropic API
- Took the product from first commit to published release on both stores in under two months

### Full-Stack Developer — DragonLab (subsidiary of DZFULLSTACK)
**May 2025 – May 2026** · `React Native 0.81` `React 19` `Laravel Echo` `React Navigation` `i18next`

**Mimo** — wallet and payments app. Sole developer of the mobile client, owning the entire
application from navigation shell to release build.

- Realtime balance and transaction updates over Laravel Echo WebSockets
- QR payment flows end to end — both scanning and code generation — plus in-app transaction charts
- Multi-language support, network-state awareness, offline behaviour, permissions, geolocation
- Also sole developer of DragonStatisticals, an internal reporting app, and VipMiMo

### Software Developer — DZFULLSTACK Joint Stock Company
**Jan 2024 – Apr 2025** · `Laravel` `PHP` `Vue.js` `MySQL` `Docker`

Built and shipped Laravel backends for client web projects, owning database schema design,
the REST API layer and deployment. Delivered internal Laravel and Vue.js training for junior
developers and students.

---

## Selected projects

### [wdev.vn](https://wdevvn.vercel.app) — publishing platform
*Solo project · `Next.js 14` `TypeScript` `Supabase` `Notion API` `three.js`*

Full publishing and agency platform built solo on the Next.js 14 App Router: blog, project case
studies, tools directory, hiring and newsletter flows across 83 modules. Notion serves as a headless
CMS through a protected on-demand revalidation endpoint, so editors publish without triggering a
redeploy.

### [Mua Đất Quảng Ngãi](https://github.com/vietvo371/muadatquangngai) → [muadatquangngai.com](https://muadatquangngai.com)
*`Next.js` `TypeScript` `Prisma` `PostgreSQL + PostGIS` `Google Maps` `Playwright`*

Real-estate marketplace for land in Quảng Ngãi, live in production. Map-based search over a
PostGIS-backed schema, listing management for agencies, saved listings, price history per property
and buyer–seller messaging.

### [AI-powered movie streaming platform](https://github.com/Khoa-CNTT/XDHTXPDN7168)
*University capstone, sole developer · Jan – May 2025 · `Laravel` `Vue.js` `MySQL` `Python` `Gemini API`*

Laravel backend with REST APIs for authentication, content catalogue and streaming session
management; MySQL schema design and query tuning for a large media catalogue. Integrated MB Bank
payments, a Python TF-IDF recommendation service and a Gemini-based in-app assistant; validated with
Postman and load-tested with JMeter. **Scored 9.5/10 — highest in the department.**

### [Disaster resource management platform](https://github.com/Truongpyeo/DTUDZ2_Admin)
*Informatics Olympiad 2024, team of 3 · `Appsmith` `MongoDB` `Docker` `OpenStreetMap` `Socket.io`*

Open-source logistics platform for allocating relief resources during disasters: resource-tracking
dashboards, live geographic visualisation and real-time updates over Socket.io.

---

## More work

| Project | What it is | Stack |
|---|---|---|
| [AgriMRV](https://github.com/vietvo371/AgriMRV) | Carbon MRV for smallholder farmers — turns sustainable practice into carbon credits and green financing, with blockchain-backed reports, credit scoring and loan suggestions | Laravel · React Native |
| [GreenEduMap](https://github.com/vietvo371/GreenEduMap) | Smart-city open data platform: realtime 3D map of air quality, temperature and green energy, with a personalised advisory bot | TypeScript · 3D mapping |
| [SmartReportAI](https://github.com/vietvo371/SmartReportAI_Web) | Civic incident reporting and resolution, with separate citizen and administrator consoles | Next.js · TypeScript |
| [AegisFlowAI](https://github.com/vietvo371/AegisFlowAI) | Autonomous agent platform for enterprise workflow automation and decision support | TypeScript · Python · LLM |
| [CivicTwinAI](https://github.com/vietvo371/CivicTwinAI) | Disaster response and community resilience with real-time incident tracking | React Native · Google Maps |
| [AuraClip-AI](https://github.com/vietvo371/AuraClip-AI) | Automates short-form video production from script through to publishing | TypeScript |
| [VIBE_EDITER](https://github.com/vietvo371/VIBE_EDITER) | AI video editing toolkit for automated content creation and scene composition | Python · FFmpeg · Remotion |
| [dzacademy](https://github.com/vietvo371/dzacademy) | Vietnamese programming school — learn by shipping real projects | Next.js · TypeScript |

**Open data for Vietnam entry compliance**, published under the
[vietentry](https://github.com/vietentry) organisation: the
[41 designated entry ports with eVisa photo specs and stay-duration rules](https://github.com/vietentry/awesome-vietnam-travel-compliance)
as CSV and JSON, a [link-checked index of entry and visa resources](https://github.com/vietentry/awesome-vietnam-travel),
and [reference guides on border checkpoints, airport transfers and eSIM coverage](https://github.com/vietentry/vietnam-travel-reference-guides).

---

## Technical skills

| | |
|---|---|
| **Mobile** | React Native, Expo, Firebase Cloud Messaging, Notifee, ML Kit, TanStack Query |
| **Backend** | Laravel 12/13, PHP 8.2–8.3, Sanctum, JWT, Laravel Reverb (WebSockets), Node.js, Python |
| **Frontend** | TypeScript, React 19, Next.js 14 (App Router, server actions, ISR), Vue.js, Tailwind, three.js |
| **Data** | MySQL, PostgreSQL / Supabase, MongoDB, SQL Server |
| **Payments** | Stripe, PayOS, MB Bank; on-chain integration with Solana and TRON |
| **Infrastructure** | Docker, GitHub Actions, GitLab CI, AWS, Google Cloud Secret Manager |
| **Testing & QA** | PHPUnit, Postman, JMeter, Zod |
| **AI tooling** | Claude Code integrated into build, test and review workflow |

---

## Education

**B.Sc. Software Engineering** — Duy Tan University, Đà Nẵng, 2021–2025
Thesis: AI-powered recommendation system for streaming platforms (9.5/10)
