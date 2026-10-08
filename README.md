# Võ Văn Việt

Full-stack engineer in Đà Nẵng, Việt Nam. I build and ship production web applications —
mostly TypeScript on Next.js with PostgreSQL behind them.

Software Engineering, Duy Tan University. Graduation thesis took the highest score in the
June 2025 competition.

[Portfolio](https://vietvo371.github.io/Portfolio/) ·
[Email](mailto:vietvo371@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/vo-van-viet-3b54a5266)

---

## Currently building

### [Mua Đất Quảng Ngãi](https://github.com/vietvo371/muadatquangngai) → [muadatquangngai.com](https://muadatquangngai.com)

A real-estate marketplace for land in Quảng Ngãi, live in production.

Map-based search over a PostGIS-backed schema, listing management for agencies,
saved listings, price history per property, and buyer–seller messaging. Around 49 tables
covering listings, media, agencies, subscriptions, transactions and notifications.

`Next.js (App Router)` `TypeScript` `Prisma` `PostgreSQL + PostGIS` `Google Maps` `Playwright`

### WDEV → [wdevvn.vercel.app](https://wdevvn.vercel.app)

Vietnamese technology publication and studio site. Notion as the content backend,
statically generated and revalidated hourly, with dynamic OG images and RSS.

The interesting part is the failure handling: Notion rate-limits at roughly 3 requests per
second, which a parallel Next.js build blows straight past. Request dedup, a short-lived memo
of successful results, and backoff on 429 keep builds from silently shipping empty pages.

`Next.js` `TypeScript` `Notion API` `Supabase` `Tailwind` `Framer Motion`

---

## Selected work

### [Multi-platform paid movie streaming with AI recommendations](https://github.com/Khoa-CNTT/XDHTXPDN7168)

Graduation thesis, highest score in the June 2025 competition at Duy Tan University.
Web, mobile and smart-TV clients, a content recommendation engine, and MB Bank payment
integration. `Vue` `Laravel` `MySQL` `Docker`

### [AegisFlowAI](https://github.com/vietvo371/AegisFlowAI)

Autonomous agent platform for enterprise workflow automation and decision support.
`TypeScript` `Python` `LLM` `Docker`

### [CivicTwinAI](https://github.com/vietvo371/CivicTwinAI)

Disaster response and community resilience platform with real-time incident tracking.
`TypeScript` `React Native` `Google Maps`

### [RELIEFLINK](https://github.com/vietvo371/RELIEFLINK_Web)

Emergency response coordination for disaster relief. Open Source Software Competition 2024.
`Node.js` `Socket.io` `MongoDB` `OpenStreetMap`

### [dzacademy](https://github.com/vietvo371/dzacademy)

Vietnamese programming education platform — learn by shipping real projects.
`TypeScript` `Next.js`

---

## Stack

TypeScript is where I spend most of my time — 32 of my 65 public repositories.

| | |
|---|---|
| **Frontend** | Next.js (App Router), React, React Native, Tailwind, Radix / shadcn |
| **Backend** | Node.js, Prisma, REST APIs, Laravel and PHP on older projects |
| **Data** | PostgreSQL + PostGIS, MySQL, MongoDB, Supabase, Notion as CMS |
| **Testing & Infra** | Playwright, Docker, Vercel, GitHub Actions |
| **Also** | Python for data and automation work, Unity and C# for 2D games |

---

## Working on next

Production reliability for the systems above — tightening build-time failure modes,
test coverage with Playwright, and geospatial query performance as listing volume grows.
Writing most of it up in Vietnamese at [WDEV](https://wdevvn.vercel.app).

---

<div align="center">

<img width="48%" src="https://github-readme-stats.vercel.app/api?username=vietvo371&show_icons=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" alt="GitHub statistics for vietvo371" />
<img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vietvo371&layout=compact&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" alt="Most used languages by vietvo371" />

</div>
