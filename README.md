# Hi! 👋 I'm Brodie Moy

I'm a **Computer Science student at UMass Amherst (B.S. May 2028)** focused on **software engineering**.

## 🚀 Projects

### 🌱 Sprout (Hackachusetts @ MIT + The Engine)

**Verified climate-action rewards platform that turns sponsor funding into provable, AI-verified real-world cleanups.**

Sprout connects sponsors and participants through a **mission → proof → verification → reward** workflow. Participants submit before-and-after cleanup photos, Sprout verifies the evidence, and each accepted action advances a sponsor-funded campaign while earning the participant points and rewards.

<p>
  <img src="https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude-Vision-D97757?style=flat-square" />
  <img src="https://img.shields.io/badge/Supabase-Postgres-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/Sharp-Image_Processing-444444?style=flat-square" />
</p>

**Key engineering highlights**
- Built a **server-authoritative verification pipeline** combining Claude Vision with geographic, timestamp, and duplicate-image integrity signals before awarding campaign credit.
- Implemented **perceptual hashing with Sharp + Hamming distance** to detect reused or recompressed evidence that ordinary file hashes can miss.
- Designed **atomic, idempotent sponsor accounting** in PostgreSQL so a verified cleanup can advance campaign progress and award points exactly once.
- Uses **EXIF GPS and capture-time analysis** as additional anti-fraud signals while gracefully handling photos with missing metadata.
- Secured cleanup evidence with **Supabase Auth, private Storage, server-side identity checks, and scoped data access**.
- Built an impact ledger connecting individual verified actions to sponsor-funded campaign progress and participant rewards.
- Added automatic **live/demo runtime fallback**, allowing the full workflow to remain demonstrable without Supabase or Claude credentials.

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
- Built a **Capture → Map → Teach** workflow for turning tacit expert knowledge into structured training.
- Uses **Claude Vision** to understand arbitrary shared screens while local visual-change detection avoids redundant model calls.
- Separates AI **question generation from question timing** so prompts appear naturally when the teacher pauses.
- Implements authenticated Teacher/Learner rooms with **Supabase Auth, server-side authorization, and Server-Sent Events**.
- Built a learner-scoped **RAG system using PostgreSQL full-text search + GIN indexing** without requiring a paid embeddings provider.
- Added OCR-based privacy controls, off-the-record responses, multilingual translation, and ElevenLabs voice output.

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
- Built a **rule-driven scheduling engine** that validates prerequisites and rejects invalid same-term or out-of-order placements.
- Supports multiple independent degree-planning workspaces with course, term, credit, and completion tracking.
- Designed **shareable planner state without a backend database** by compressing complete plans into URL-safe payloads.
- Implemented guest and Google-authenticated persistence with account-scoped `localStorage` namespaces.
- Added migration logic for moving legacy and guest data safely into authenticated workspaces.
- Built with reusable UI primitives, Motion animations, responsive layouts, and dark/light themes.

**[Live Demo](https://plan-it-planner.vercel.app) · [Source Code](https://github.com/brodiemoy/Plan-it)**

---

### 🍽️ Food4U (HackUMass XIII)

**AI-powered natural-language meal discovery for UMass dining.**

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
- Created a conversational **natural-language recommendation pipeline** over structured dining data.
- Uses OpenAI for semantic ranking while keeping storage, normalization, and ranking concerns separated.
- Built Python ingestion pipelines using **Playwright, BeautifulSoup, and Requests** to collect dining data.
- Normalizes inconsistent menu metadata and enriches missing calorie information with fallback heuristics.
- Uses natural-key de-duplication and bulk **Supabase upserts** to handle noisy scraped data.
- Designed graceful fallback behavior so recommendations still work when the AI ranking service is unavailable.
- Prototyped an embeddings-based retrieval path for future hybrid search and reranking.

**[Source Code](https://github.com/brodiemoy/Food4U)**

---

## Contact

- **Email:** [brodiemoy@outlook.com](mailto:brodiemoy@outlook.com)
- **LinkedIn:** [linkedin.com/in/brodiemoy](https://www.linkedin.com/in/brodiemoy)
- **GitHub:** [github.com/brodiemoy](https://github.com/brodiemoy)
