<div align="center">

# VEDANT BANSOD

### AI & Machine Learning &middot; Full-Stack Systems &middot; Generative AI

Building production-oriented AI applications with secure server-side orchestration, persistent data pipelines, and responsive interfaces.

<br />

<a href="https://github.com/boeing-boy-97">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=540&lines=AI+%26+Machine+Learning+Engineer;Full-Stack+Systems+Developer;Building+Production-Oriented+AI+Apps;Prompt+Engineering+%2B+RAG+Pipelines" alt="Typing Animation" />
</a>

<br />

[![Portfolio](https://img.shields.io/badge/Portfolio-vedant--bansod-0ea5e9?style=flat-square&logo=google-chrome&logoColor=white)](https://vedant-bansod-portfolio.netlify.app/)
[![GitHub](https://img.shields.io/badge/GitHub-boeing--boy--97-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/boeing-boy-97)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vedant_Bansod-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vedant-bansod-525316314/)
[![Email](https://img.shields.io/badge/Email-bansods685%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:bansods685@gmail.com)

<br />

[About](#about) &nbsp;&middot;&nbsp; [Current Focus](#current-focus) &nbsp;&middot;&nbsp; [Tech Stack](#tech-stack) &nbsp;&middot;&nbsp; [Selected Work](#selected-work) &nbsp;&middot;&nbsp; [Engineering Highlights](#engineering-highlights) &nbsp;&middot;&nbsp; [Experience & Training](#experience--training) &nbsp;&middot;&nbsp; [Education](#education) &nbsp;&middot;&nbsp; [Contact](#contact)

</div>

---

## About

I am an engineering student pursuing a **B.Tech in Artificial Intelligence** at JD College of Engineering and Management, Nagpur (2024–2028). My focus lies in bridging machine learning models and LLMs with production-ready software engineering.

Rather than building surface-level wrappers, I design systems end-to-end: architecting normalized database schemas, protecting API keys behind rate-limited backend proxies, orchestrating asynchronous workers for heavy compute tasks, and building clean, accessible web interfaces.

---

## Current Focus

- **LLM Application Architecture:** Implementing server-authoritative agents, structured JSON outputs, and retrieval-augmented generation (RAG) with local vector embeddings.
- **Asynchronous Processing:** Building event-driven background queues and WebSocket pipelines for real-time publishing and voice streaming.
- **Data Persistence & Security:** Working with PostgreSQL, Prisma, and Drizzle ORM; enforcing multi-tenant database isolation, session authentication, and AES-256-GCM encryption.
- **Core Engineering Fundamentals:** Deepening systems programming in C++ and exploring computer vision pipelines with OpenCV and TensorFlow.

---

## Tech Stack

<table>
  <tr>
    <td width="24%"><strong>Languages</strong></td>
    <td>Python &middot; C++ &middot; TypeScript &middot; JavaScript &middot; C &middot; SQL</td>
  </tr>
  <tr>
    <td><strong>AI & Machine Learning</strong></td>
    <td>Google GenAI SDK &middot; OpenAI API &middot; TensorFlow &middot; OpenCV &middot; RAG &middot; Prompt Engineering &middot; Computer Vision</td>
  </tr>
  <tr>
    <td><strong>Backend & Services</strong></td>
    <td>Node.js &middot; Express &middot; FastAPI &middot; Flask &middot; REST APIs &middot; WebSockets (<code>ws</code>) &middot; BullMQ &middot; NextAuth / Auth.js</td>
  </tr>
  <tr>
    <td><strong>Frontend</strong></td>
    <td>React &middot; Next.js &middot; TypeScript &middot; Tailwind CSS &middot; HTML5 &middot; CSS3</td>
  </tr>
  <tr>
    <td><strong>Databases & ORMs</strong></td>
    <td>PostgreSQL &middot; Prisma ORM &middot; Drizzle ORM &middot; MongoDB &middot; Redis &middot; SQLite &middot; Firebase Firestore</td>
  </tr>
  <tr>
    <td><strong>DevOps & Tooling</strong></td>
    <td>Docker &middot; Git &middot; GitHub Actions &middot; Vercel &middot; Netlify &middot; Firebase &middot; Postman &middot; Linux</td>
  </tr>
</table>

---

## Selected Work

### 01. [PostWave AI](https://github.com/boeing-boy-97/post-ai)
> Enterprise-grade social media scheduling, AI content generation, and multi-network publishing platform.

- **Problem & Solution:** Content creators and growth teams juggle disparate platforms with divergent formatting rules. PostWave AI unifies 9 networks (LinkedIn, X, Instagram, YouTube, Facebook, Threads, Pinterest, TikTok, Telegram) into a single scheduling workflow.
- **Architecture:** Node.js &middot; Express &middot; Prisma ORM &middot; React &middot; TypeScript &middot; Tailwind CSS &middot; BullMQ &middot; Redis
- **Engineering Implementation:**
  - Designed an asynchronous Redis queue with BullMQ for reliable, scheduled multi-network dispatch.
  - Implemented an **AES-256-GCM** encrypted credential vault to secure third-party OAuth tokens at rest.
  - Built structured prompting engines to automatically adapt master posts to network-specific length constraints and hashtag conventions.
- **Links:** [Repository](https://github.com/boeing-boy-97/post-ai) &middot; [Live Demo](https://postewave.vercel.app)

---

### 02. [RecipeMate](https://github.com/boeing-boy-97/Recipe_mate)
> Persistent cooking assistant and meal planner featuring multimodal visual ingredient recognition.

- **Problem & Solution:** Most cooking apps rely on static databases or ephemeral client-only storage. RecipeMate delivers fully owner-scoped, persistent pantries, meal plans, and customized recipes generated from detected ingredients.
- **Architecture:** Next.js &middot; TypeScript &middot; PostgreSQL 17 &middot; Drizzle ORM &middot; Auth.js (NextAuth v5) &middot; Google Gemini Vision
- **Engineering Implementation:**
  - Structured a normalized PostgreSQL schema with indexed foreign keys, cascade deletes, and versioned Drizzle migrations.
  - Built a Gemini Vision pipeline with an interactive verification phase, preventing incorrect model classifications from corrupting user pantry state.
  - Enforced server-side JWT authentication scoping every database read/write strictly to the authenticated user ID.
- **Links:** [Repository](https://github.com/boeing-boy-97/Recipe_mate) &middot; [Live Demo](https://recipe-mate-kappa.vercel.app)

---

### 03. [DebateAI](https://github.com/boeing-boy-97/DebateAI)
> Dedicated AI debate-practice environment for argument stress-testing and counter-reasoning.

- **Problem & Solution:** General-purpose chat interfaces default to conversational agreeableness. DebateAI provides a calibrated sparring partner that challenges logical flaws, offers structured counterpoints, or delivers an impartial ruling.
- **Architecture:** TypeScript &middot; React &middot; Vite &middot; Node.js &middot; Express &middot; OpenAI API
- **Engineering Implementation:**
  - Implemented a zero-trust architecture: OpenAI API keys remain strictly on the backend with zero client-side leakage.
  - Engineered stance-based prompt routing (`challenge`, `support`, `judge`) with server-enforced context windows and request payload sanitization.
  - Built custom rate-limiting and session guardrails to prevent abuse and manage token budgets.
- **Links:** [Repository](https://github.com/boeing-boy-97/DebateAI) &middot; [Live Demo](https://debateai-beta.vercel.app)

---

### 04. [Digital Bazar](https://github.com/boeing-boy-97/Digital-Bazar)
> Real-time local commerce and inventory reservation platform bridging physical shops in Nagpur with nearby buyers.

- **Problem & Solution:** Dark-store instant delivery platforms cannibalize local retailers. Digital Bazar empowers neighborhood merchants to list live counter inventory, allowing buyers to reserve items before leaving home.
- **Architecture:** TypeScript &middot; Node.js &middot; Express &middot; Prisma ORM &middot; PostgreSQL &middot; Docker &middot; Redis
- **Engineering Implementation:**
  - Created an offline-friendly reserve-and-collect workflow utilizing single-use, **time-expiring HMAC-signed QR tokens**.
  - Engineered shopkeeper inventory counters with optimistic concurrency control to prevent double-reservation of stock.
  - Containerized services with Docker Compose for consistent local testing across PostgreSQL, Redis, and application instances.
- **Links:** [Repository](https://github.com/boeing-boy-97/Digital-Bazar) &middot; [Live Demo](https://digital-bazar-three.vercel.app/)

---

### 05. [Campus Connect](https://github.com/boeing-boy-97/campus-connector)
> College-verified social and academic networking platform for campus collaboration and team formation.

- **Problem & Solution:** Open social media lacks academic trust and student verification. Campus Connect isolates networks by institution, creating safe channels for hackathon teaming, project collaboration, and peer study groups.
- **Architecture:** Flutter (Mobile) &middot; TypeScript &middot; Firebase Auth & Firestore &middot; Cloud Functions &middot; GitHub Actions
- **Engineering Implementation:**
  - Enforced institutional domain whitelisting during signup, backed by automated photo ID verification workflows.
  - Architected tenant-isolated Firestore security rules ensuring cross-college data access is rejected at the database level.
  - Configured multi-stage GitHub Actions CI/CD to automate static analysis, mobile test runs, and cloud function deployments.
- **Links:** [Repository](https://github.com/boeing-boy-97/campus-connector) &middot; [Live Demo](https://campus-connector-student.vercel.app)

---

### 06. [AI Calling Agent](https://github.com/boeing-boy-97/AI-calling-agent-)
> Bidirectional conversational voice and telephony agent prototype with event-driven streaming.

- **Architecture:** TypeScript &middot; Node.js &middot; Express &middot; WebSockets (`ws`) &middot; Google GenAI SDK &middot; Docker
- **Engineering Implementation:**
  - Configured full-duplex WebSocket channels to stream bidirectional audio and transcript events with low round-trip latency.
  - Containerized telephony gateway handlers with Docker for deployment alongside SIP/VoIP service bridges.
- **Links:** [Repository](https://github.com/boeing-boy-97/AI-calling-agent-) &middot; [Live Demo](https://ai-calling-agent-bice-five.vercel.app)

---

## Engineering Highlights

<details open>
<summary><strong>Server-Side AI Orchestration & Key Security</strong></summary>

<br />

All model inferences execute strictly within server-side environments (Node.js/Express, FastAPI, Next.js route handlers). Client applications never receive raw API keys. Requests undergo strict input validation, rate limiting, and output normalization before reaching the client.
</details>

<details open>
<summary><strong>Relational Data Modeling & Migrations</strong></summary>

<br />

Extensive practical experience designing relational schemas using **PostgreSQL** with **Prisma** and **Drizzle ORM**. Schemas enforce referential integrity, foreign key cascading, composite unique constraints, and indexed lookups for low-latency queries.
</details>

<details open>
<summary><strong>Cryptographic Tokens & Verification</strong></summary>

<br />

Integrated **AES-256-GCM** encryption for persistent storage of external credentials in multi-platform social management tools, alongside time-limited, signed **HMAC QR tokens** for tamper-proof local physical inventory pickup.
</details>

<details open>
<summary><strong>Automated CI/CD & Containerization</strong></summary>

<br />

Maintained reproducible development and deployment environments using **Docker** and **Docker Compose**, paired with automated **GitHub Actions** workflows for linting, test suites, and build verification on push.
</details>

---

## Experience & Training

- **AI/ML Virtual Internship** &middot; Google &times; AICTE *(2025)*  
  Completed applied machine learning curriculum covering supervised algorithms, model evaluation techniques, and practical ML pipelines.
- **Cyber Job Simulation** &middot; Deloitte / Forage *(2025)*  
  Conducted simulated enterprise security incident triage, log inspection, and vulnerability reporting.
- **Open-Source Builder & Developer** *(Ongoing)*  
  Actively building and deploying end-to-end full-stack AI applications, maintaining open repositories, and testing emerging frameworks.

---

## Education

**B.Tech in Artificial Intelligence** &middot; *2024 &ndash; 2028*  
**JD College of Engineering and Management, Nagpur**  
- **Academic Standing:** SGPA: 8.6 / 10  
- **Core Coursework:** Machine Learning, Computer Vision, Data Structures & Algorithms, Object-Oriented Programming (C++), Relational Database Management Systems.

---

## Certifications & Credentials

- **AI/ML Virtual Internship** &mdash; Google &times; AICTE (2025)
- **Cyber Job Simulation** &mdash; Deloitte / Forage (2025)
- **C++ Programming (Score: 80%)** &mdash; IIT Bombay (Spoken Tutorial)
- **GenAI Data Analytics** &mdash; Industry Training (2025)
- **Solutions Architecture** &mdash; Cloud Foundations (2025)
- **Cybersecurity Analyst** &mdash; Industry Track (2025)

---

## Contact

<div align="center">

**Have a project, internship opportunity, or technical discussion? Let's connect.**

[Portfolio](https://vedant-bansod-portfolio.netlify.app/) &nbsp;&middot;&nbsp; [GitHub](https://github.com/boeing-boy-97) &nbsp;&middot;&nbsp; [LinkedIn](https://www.linkedin.com/in/vedant-bansod-525316314/) &nbsp;&middot;&nbsp; [Email: bansods685@gmail.com](mailto:bansods685@gmail.com)

<br />

<sub>Building practical AI systems, learning continuously, and shipping software that solves real problems.</sub>

</div>

