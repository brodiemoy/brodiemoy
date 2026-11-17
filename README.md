
# Hi! 👋 I'm Brodie Moy

I'm a **Computer Science student at UMass Amherst (B.S. May 2028)** focused on **software engineering**.

## 🚀 Projects

### 🎨 WhatColorAreHue? (HackUMass XIV)
*🏆 Best Domain Name from GoDaddy Registry*

**AI-powered color accessibility assistant that helps people identify, find, and work with colors using a live camera.**

WhatColorAreHue? turns a phone camera or webcam into a **See → Find → Do → Remember** workflow, helping people with color-vision deficiencies identify shades, locate matching colors, follow guided tasks, and save useful information.

<p>
  <img src="https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-Express-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-AI-4285F4?style=flat-square&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-Database-47A248?style=flat-square&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/WebRTC-Camera-444444?style=flat-square" />
</p>

**Key engineering highlights**
- Built **HueSee and HueFind** for real-time color identification, perceptual shade matching, stabilized readings, and high-contrast detection of matching regions.
- Integrated **Gemini-powered HueDo** for image-aware task guidance, using local object tracking to maintain responsive feedback between AI requests.
- Developed **MongoDB-backed HueMemory** for account-scoped colors and reusable guides, secured with authenticated sessions and protected API routes.

**[Live Demo](https://whatcolorarehue.us/) · [Source Code](https://github.com/Yackers-26/what-color-are-hue)**

---

### 🌱 Sprout (Hackachusetts @ MIT + The Engine)

**AI-verified climate-action rewards platform that turns real-world cleanups into sponsor-funded rewards.**

Sprout lets participants submit cleanup evidence, verifies the action with AI and metadata checks, and converts approved impact into campaign progress, points, and rewards.

<p>
  <img src="https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude-Vision-D97757?style=flat-square" />
  <img src="https://img.shields.io/badge/Supabase-Postgres-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
</p>

**Key engineering highlights**
- Built an **AI verification pipeline** combining Claude Vision, GPS, timestamps, and perceptual hashing with **Sharp + Hamming distance** to validate cleanup evidence and detect duplicates.
- Designed **atomic, idempotent PostgreSQL updates** to award campaign credit and reward points exactly once per verified action.
- Secured the submission and sponsor-funded rewards workflow with **Supabase Auth, private Storage, and server-side authorization**.

**[Live Demo](https://hackachusetts-build.vercel.app/) · [Source Code](https://github.com/suri-ng/hackachusetts-build)**

---

### 🧠 Mentaur (Hack-Nation 7 MIT Hub)
*🏆 Go Viral Award (Global)*

**Screen-aware AI apprenticeship platform that captures expert knowledge while people work and turns it into reusable training.**

Mentaur observes meaningful changes on a shared screen, asks context-aware questions about decisions and edge cases, and converts the session into a structured **Work Map** that learners can study, practice, and query later.

<p>
  <img src="https://img.shields.io/badge/Node.js-22-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude-AI-D97757?style=flat-square" />
  <img src="https://img.shields.io/badge/Supabase-Postgres-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/ElevenLabs-Voice-000000?style=flat-square" />
  <img src="https://img.shields.io/badge/SSE-Realtime-444444?style=flat-square" />
</p>

**Key engineering highlights**
- Built a **Capture → Map → Teach pipeline** using Claude Vision and local visual-change detection to transform expert screen activity into structured training while reducing redundant AI calls.
- Implemented **context-aware question scheduling** and authenticated Teacher/Learner rooms using Supabase Auth, server-side authorization, and **Server-Sent Events**.
- Developed a **learner-scoped RAG system** using PostgreSQL full-text search and GIN indexing to retrieve knowledge from captured Work Maps.

**[Live Demo](https://hacknation-30mb.onrender.com/) · [Source Code](https://github.com/Farmer-Nation/Mentaur)**

---

### 🎓 Plan-it (Hack(H)er413 2026)

**Prerequisite-aware course planner for building and sharing multi-semester academic plans.**

Plan-it lets students define their own courses, prerequisites, terms, and graduation targets while automatically preventing invalid course placements.

<p>
  <img src="https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Auth.js-Google_OAuth-444444?style=flat-square" />
</p>

**Key engineering highlights**
- Built a **rule-driven scheduling engine** that validates course prerequisites and prevents invalid same-term or out-of-order placements.
- Designed **compressed, URL-safe planner serialization** to share complete multi-semester academic plans without a backend database.
- Implemented **guest and Google-authenticated persistence** using account-scoped `localStorage` namespaces and migration logic for legacy and guest data.

**[Live Demo](https://plan-it-planner.vercel.app) · [Source Code](https://github.com/Yack-H-er413/Plan-it)**

---

### 🍽️ Food4U (HackUMass XIII)

**Chat-style AI meal recommendations for UMass dining.**

Instead of searching through static dining menus, Food4U lets students describe what they want — such as *“high protein but not too heavy”* — and returns ranked menu recommendations.

<p>
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Vite-5-646CFF?style=flat-square&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-Node.js-339933?style=flat-square&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI-AI-412991?style=flat-square&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-Database-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-Scraping-3776AB?style=flat-square&logo=python&logoColor=white" />
</p>

**Key engineering highlights**
- Built a **natural-language recommendation pipeline** using OpenAI to semantically rank structured dining menus against student preferences.
- Developed **Python data ingestion pipelines** with Playwright, BeautifulSoup, and Requests to scrape menus, normalize inconsistent metadata, and estimate missing calorie information.
- Implemented **natural-key de-duplication and bulk Supabase upserts** for reliable menu storage, with fallback recommendations when AI ranking is unavailable.

**[Source Code](https://github.com/Team-Food4U/Food4U)**

---

## Contact

- **Email:** [brodiemoy@outlook.com](mailto:brodiemoy@outlook.com)
- **LinkedIn:** [linkedin.com/in/brodiemoy](https://www.linkedin.com/in/brodiemoy)
- **GitHub:** [github.com/brodiemoy](https://github.com/brodiemoy)
