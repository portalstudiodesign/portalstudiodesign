### Hi, I'm Iulian 👋

I'm a developer from Romania who builds **complete products** — from the database schema to the store listing.
I've shipped a mobile game to Google Play, a health app for thyroid patients, and an open-source SaaS with
subscriptions, an embeddable widget and CI.

📫 **Contact:** [portaldesignstudios@gmail.com](mailto:portaldesignstudios@gmail.com) · [LinkedIn](https://www.linkedin.com/in/antal-adrian-iulian/)

---

### 🚀 What I've built

#### [Echoboard](https://github.com/portalstudiodesign/echoboard) — feedback boards & public roadmaps for SaaS teams · *open source*

**[Live app](https://echoboard-nine.vercel.app)** · **[Demo board](https://echoboard-nine.vercel.app/b/orbit)** · **[Source](https://github.com/portalstudiodesign/echoboard)**

A multi-tenant SaaS: workspaces with roles and invitations, public boards with voting and comments, a
roadmap, merging of duplicate ideas, email notifications, an embeddable widget and Stripe subscriptions.

- **Next.js 16 · TypeScript · PostgreSQL (Drizzle) · Better Auth · Stripe · Tailwind**, deployed on Vercel + Neon
- Data integrity enforced by the database — composite keys for one-vote-per-user, triggers for counters
- 60+ integration tests against a real Postgres, CI on every push, signature-verified Stripe webhooks
- A dependency-free widget isolated with Shadow DOM + iframe, with clickjacking protection on every other page

#### [Onyx Flow](https://play.google.com/store/apps/details?id=com.portaldesignstudio.onyxflow) — premium block puzzle for Android · *published on Google Play*

**[Google Play](https://play.google.com/store/apps/details?id=com.portaldesignstudio.onyxflow)** · **[Website](https://portalstudiodesign.github.io/onyx-flow-site/)**

- **Unity 6 · C#** — game rules live in engine-free assemblies, so they are unit-tested without opening Unity
- Procedural visual identity (no stock art), a developer sandbox with replay, profiling and seeded runs
- Taken end to end solo: gameplay, art direction, store listing, privacy policy and release

#### [TiroCare](https://tirocareromania.netlify.app) — personal assistant for thyroid patients (Romanian)

**[Web app](https://tirocareromania.netlify.app)**

- **JavaScript · Capacitor (Android) · AI integration** — symptom and lab-result tracking, medication reminders, an AI assistant
- Built for a regulated space: explicit consent for AI, in-app reporting of AI answers, a public privacy policy
- Android app being prepared for Google Play

> The source of Onyx Flow and TiroCare is private because they are commercial products.
> I'm happy to walk through the code and architecture in an interview.

---

### 🛠️ Tools I work with

**Languages:** TypeScript · JavaScript · C# · SQL
**Web:** Next.js · React · Node.js · Tailwind CSS
**Data & services:** PostgreSQL · Drizzle ORM · Stripe · Vercel · Neon
**Mobile & games:** Unity 6 · Capacitor · Android
**Practices:** automated testing (Vitest, Unity EditMode) · CI with GitHub Actions · Git
