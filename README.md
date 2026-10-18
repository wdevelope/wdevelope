# Seongwon Woo — Full-Stack Engineer, Healthcare

<br>

## 🙋 About Me

Optician turned full-stack engineer, building digital healthcare products end to end.
After five years as a licensed optician in optical stores and eye clinics, I moved into software. I hold degrees in both optometry and computer science.

As R&D Team Lead at ICU Corporation, an ophthalmic healthcare startup, I build our products solo: planning, UI design, development, deployment and operations.

<br>

## 🌟 Projects

### 👓 Preznel REF | VR Platform for Strabismus Diagnosis & Vision Training (Solo)

A VR platform for diagnosing strabismus and phoria and training binocular vision: a patient VR app (Galaxy XR, Quest 3), a real-time relay server and a clinician desktop dashboard.

- **Clinical modules**: 3 diagnostic tests (visual acuity, phoria, fusional vergence) and 3 training modules; virtual prism delivered through Prentice's-rule target displacement and a single-pass URP stereo shader
- **Measurement accuracy**: traced an under-measurement against reference equipment to baseline offset and response latency, reproduced it mathematically, and corrected the measurement logic
- **Real-time control**: HMD–server–dashboard WebSocket protocol (50 commands, ACK and idempotency), WebRTC P2P mirroring with TURN relay, binocular eye tracking with in-app calibration
- **Reliability**: offline-first result storage with batched, hash-acknowledged sync
- **Delivery**: ~70K lines and 26 releases in 4 months; CI/CD with auto-rollback, desktop auto-update (macOS, Windows), automated Unity APK builds and wireless headset deployment

`Unity 6` `C#` `OpenXR` `Node.js` `WebSocket` `WebRTC` `Electron` `React` `MongoDB` `AWS`

<br>

### 🧿 Preznel ALY | Optical Clinic SaaS & AI Myopia Prediction (Solo)

An operations platform for a multi-site optical clinic chain (eye exams and prescriptions, sales and inventory, finance, customer messaging), with a customer app on iOS and Android and an AI myopia-progression model.
Planned, designed, built, deployed and operated solo; in production for tens of thousands of customers.

- **Architecture**: TypeScript monorepo (Express API, React admin web, Expo app, shared types) plus a separate FastAPI AI service; Controller–Service layering with Zod DTO validation
- **Security**: JWT audience separation, refresh-token rotation with reuse detection, pre-auth tokens for 2FA, three-tier (HQ, organization, center) data scoping; fixed 18 issues from a security audit in one day
- **Data integrity**: MongoDB transactions, inventory and messaging ledgers, partial unique indexes; production data fixes only through dry-run, backup and tested migrations
- **Data & AI**: MongoDB → Python ETL and an XGBoost myopia-progression model served by FastAPI
- **DevOps**: path-filtered CI/CD to EC2 (PM2, health checks, auto-rollback) and S3/CloudFront

`TypeScript` `React` `Express` `MongoDB` `React Native (Expo)` `Python` `FastAPI` `XGBoost` `AWS`

<br>

### 🚢 Sdenet | Maritime SaaS Backends incl. EDMS for HMM Ground Staff (Solo)

Five backend services for a B2B vessel management platform, including EDMS, a system that centralizes maritime regulations and internal rule documents.

- **Shared auth server**: SSO with HttpOnly cookies on a shared domain, per-service permissions by company, organization and position, Toss Payments integration
- **Approval workflow**: electronic approval for regulation changes, with real-time notifications over SSE
- **Document management**: CKEditor-based web editing, new/old regulation comparison, versioned change history
- **Search**: MongoDB Atlas with custom search for near real-time results across thousands of documents
- **Refactoring**: migrated the legacy JavaScript codebase to TypeScript

`NestJS` `Express` `PostgreSQL` `MongoDB` `GitLab CI` `AWS EC2`

<br>

## 🔓 Open Source

- [nativewind/nativewind#1869](https://github.com/nativewind/nativewind/pull/1869): root-caused an out-of-memory crash (exponential recursion in react-native-css-interop) and submitted a fix (in review)

<br>

## 🤖 How I Build

- **AI-native, with guardrails**: Claude Code hooks enforce spec- and test-first edits and block task completion while tests fail; parallel sub-agents on git worktrees
- **Domain first**: clinical logic and data integrity are designed before the UI

<br>

## 🛠️ Skills & Technologies

- **Languages**: TypeScript, JavaScript, C#, Python, SQL
- **Backend**: Node.js (Express, NestJS, Hono), oRPC, WebSocket, WebRTC, Python (FastAPI)
- **Frontend**: React (Vite), Next.js, Astro, Zustand, TanStack Query, Tailwind CSS
- **Mobile / Desktop / XR**: React Native (Expo), Electron, Unity 6 (URP, OpenXR, Android XR)
- **Database**: MongoDB (Mongoose), PostgreSQL (Drizzle, Prisma, TimescaleDB), Supabase
- **DevOps**: AWS (EC2, S3, CloudFront, Route53, Load Balancer, Amplify), Docker, GitHub Actions, Nginx, PM2
- **AI & Data**: Pandas, Scikit-learn, XGBoost

<br>

## 🚀 Mission

**"Building a better world through efficient code."**

<br>

## 📫 Get in Touch

- [LinkedIn](https://www.linkedin.com/in/seongwon-woo-4a11092a7/)
- Email: dnqkr18@gmail.com
