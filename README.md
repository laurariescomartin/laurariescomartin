# Laura Riesco Martín

**Software Engineer | Backend | AI-powered Applications**

📍 Salamanca, Spain · Open to relocation
📧 laurariessco@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/laura-riesco-martin)

---

## About Me

Software Engineering graduate from the Universidad Pontificia de Salamanca (UPSA), with an academic exchange (SICUE) at the University of Granada (UGR).

I have hands-on experience building AI-powered applications with RAG and LLMs, secure full-stack web software, and 3D interactive engines. I like systems that are well-architected, modular, and secure by design.

Currently looking for a Junior Software Engineer role where I can contribute and keep growing — particularly interested in backend development, AI integration, and application security.

---

## Featured Projects

### [CodexAssist](https://github.com/laurariescomartin/codex-assist) — AI-Powered Code Assistant *(Bachelor's Thesis · 9.2/10)*

A RAG platform that lets developers query their own codebase in natural language. LLM answers are grounded strictly in repository context, eliminating hallucinations.

**What I built:**
- Code-aware chunking pipeline and semantic retrieval over ChromaDB (cosine similarity search)
- RAG Triad evaluation (Context Relevance, Groundedness, Answer Relevance) to validate output quality
- Modular architecture where the LLM and vector store are swappable without touching business logic
- FastAPI backend with intelligent context filtering (strips deps, logs, config noise)
- Full-stack deployment with Docker Compose

`Python` `FastAPI` `LangChain` `ChromaDB` `Docker` `Prompt Engineering`

---

### [Cinema Management Platform](https://github.com/laurariescomartin/catalogo-cine) — Secure Full-Stack Web App *(SICUE Exchange · UGR)*

Full-stack web application built through 5 incremental engineering phases, with a focus on security and access control.

**What I built:**
- 5-level RBAC (anonymous → registered → moderator → manager → superuser), enforced server-side on every route
- Security layer: XSS prevention via Twig strict auto-escaping, bcrypt password hashing, parameterised SQL queries against injection attacks
- Async AJAX search engine with role-filtered queries — regular users see published content only; managers query full catalogue including drafts
- Containerised with Docker Compose (Apache + MySQL services separated)

`PHP` `Twig` `Vanilla JS` `AJAX` `MySQL` `Docker` `bcrypt` `RBAC`

---

### [ChefDrez](https://github.com/laurariescomartin/threejs-chess-engine) — 3D Interactive Chess Engine *(Computer Graphics · UGR)*

Browser-based 3D chess game with a culinary theme — pieces are kitchen utensils on a cutting board, rendered in WebGL.

**What I built:**
- Strategy pattern for move validation: each piece type is a pluggable strategy, extensible without modifying the core engine
- OOP class hierarchy where each piece is a `THREE.Object3D` with encapsulated animation logic
- Capture animations synchronised with board state via Promises + TWEEN.js
- Cinematic camera that auto-rotates to the active player using CatmullRom curves; dynamic lighting that responds to game events

`JavaScript ES6+` `Three.js` `TWEEN.js` `WebGL` `Raycasting`

---

## Technical Skills

| | |
|---|---|
| **Languages** | Python · JavaScript (ES6+) · PHP · Java · C/C++ · SQL · HTML5/CSS3 |
| **Frameworks** | FastAPI · LangChain · Three.js · TWEEN.js · Twig · Spring Boot · Node.js |
| **AI / ML** | RAG · LLMs · ChromaDB · NLP · Vector Databases · Embeddings · Prompt Engineering |
| **Databases** | PostgreSQL · MySQL · ChromaDB |
| **Tools** | Docker · Docker Compose · Git · Linux/Bash · Postman · Maven |
| **Security** | XSS Mitigation · bcrypt · SQL Injection Prevention · RBAC · Secure Session Management |
| **Practices** | REST APIs · OOP · Software Architecture · Agile/Scrum |

---

## Education

**BSc Computer Engineering** — Specialization in Software Engineering
Universidad Pontificia de Salamanca (UPSA) · 2022–2026
Thesis grade: 9.2/10 · Overall GPA: 7.47/10

**SICUE National Academic Exchange**
University of Granada (UGR) · 2024–2025 · Full academic year

---

## Languages

Spanish (Native) · English (Working Proficiency) · French (Basic)
```
