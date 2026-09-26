### Hi, I'm Adrian Iulian Antal 👋

**Unity / Mobile Developer · C# · Android · AI-assisted product development** — Neamț, Romania · open to remote

I ship **complete products**, from specification to store listing: architecture, implementation, UI, testing,
deployment, monetisation and release. I published an Android game on Google Play on my own, built a health app
with OCR and a conversational AI assistant, and build open-source projects in the open. I've run my own technical
businesses since 2012, so client communication, fixed deadlines and working without supervision are how I work.

📫 [portaldesignstudios@gmail.com](mailto:portaldesignstudios@gmail.com) · [LinkedIn](https://www.linkedin.com/in/antal-adrian-iulian/)

---

### 🚀 What I've built

#### [Onyx Flow](https://play.google.com/store/apps/details?id=com.portaldesignstudio.onyxflow) — block puzzle for Android · *live on Google Play*

**[Google Play](https://play.google.com/store/apps/details?id=com.portaldesignstudio.onyxflow)** · **[Website](https://portalstudiodesign.github.io/onyx-flow-site/)**

- **Unity 6 · C#** — designed, built and published solo: engineering, visual direction, monetisation, compliance, release
- An original **Flow multiplier**: charged only by line clears, weighted by the open space you leave, up to ×2.25
- Every block, effect and board skin is **generated procedurally at runtime** — 33 MB download, 60 FPS on mid-range Android
- Deterministic daily challenges and runs stored as *seed + moves*, so any game replays move for move
- Game rules live in engine-free C# assemblies, unit-tested without opening Unity

#### [Echoboard](https://github.com/portalstudiodesign/echoboard) — feedback boards & public roadmaps for SaaS teams · *open source*

**[Live app](https://echoboard-nine.vercel.app)** · **[Demo board](https://echoboard-nine.vercel.app/b/orbit)** · **[Source](https://github.com/portalstudiodesign/echoboard)**

- **Next.js 16 · TypeScript · PostgreSQL (Drizzle) · Better Auth · Stripe**, deployed on Vercel + Neon
- Multi-tenant workspaces with roles and invitations, voting, a roadmap, duplicate merging, voter emails
- Data integrity enforced by the database (composite keys, triggers); 60+ integration tests on a real Postgres, CI on every push
- Stripe Checkout, customer portal and signature-verified webhooks; an embeddable widget isolated with Shadow DOM + iframe

#### [askdocs](https://github.com/portalstudiodesign/askdocs) — a RAG pipeline that knows when not to answer · *open source*

- **Python · SQLite** — hybrid retrieval (BM25 + dense vectors, fused with Reciprocal Rank Fusion), answers with citations
- Abstains when the documentation doesn't cover the question, treats retrieved text as untrusted, scored with an evaluation set
- Runs fully offline with no API key; uses OpenAI embeddings when a key is present

#### [TiroCare](https://tirocareromania.netlify.app) — health companion for thyroid patients (Romanian)

**[Web app](https://tirocareromania.netlify.app)**

- **JavaScript · Capacitor · OCR · conversational AI** — onboarding adapts the app to the user's condition
- Lab reports imported from PDF or photo, with OCR extraction of TSH, FT4, ATPO and Anti-Tg and comparison against reference ranges
- Medication schedules, retest reminders and a PDF report for the doctor; no accounts, no server — data stays on the device

> Onyx Flow and TiroCare are commercial products, so their source is private. I'm happy to walk through the code
> and architecture in an interview.

---

### 🛠️ Tools

**Languages:** C# · TypeScript · JavaScript · Python · SQL
**Games & mobile:** Unity 6 / 2022 LTS · URP 2D · Android · Google Play Console · AdMob · Capacitor
**Web:** Next.js · React · Node.js · Tailwind CSS · PostgreSQL · Stripe · Vercel · Netlify
**AI:** agentic coding with Claude Code, with my own review on top · RAG, embeddings and evaluation sets · conversational AI in a shipped product
**Practices:** specification-first development · engine-free, testable game logic · automated tests · CI with GitHub Actions · Git
