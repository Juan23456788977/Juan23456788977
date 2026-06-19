<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&pause=1000&color=A855F7&center=true&vCenter=true&width=800&lines=Hola%2C+soy+Juan+Cortez+%F0%9F%91%8B+%2F+Hey%2C+I'm+Juan+Cortez;Desarrollador+Full-Stack+%2F+Full-Stack+Developer;18+años+%7C+Caracas%2C+Venezuela+%F0%9F%87%BB%F0%9F%87%AA;Construyo+SaaS%2C+IA+y+bots+%2F+I+build+SaaS%2C+AI+%26+bots" alt="Typing SVG" />

<br/>

[![Email](https://img.shields.io/badge/Email-cortezurreajuanalberto%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cortezurreajuanalberto@gmail.com)
[![Portafolio](https://img.shields.io/badge/Portafolio_Completo-A855F7?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Juan23456788977/Portafolio)

</div>

---

## 👨‍💻 Sobre mí / About Me

> 🇪🇸 Desarrollador Full-Stack venezolano, 18 años. Trabajo como **pasante de desarrollo y QA en Akdemia** (plataforma EdTech con 500+ colegios) y como **freelance** construyendo bots de trading algorítmico con capital real en mercados crypto. No aprendo tecnologías para hacer tutoriales — las aprendo porque tengo un problema real que resolver.

> 🌐 Venezuelan Full-Stack Developer, 18 y/o. Working as **development & QA intern at Akdemia** (EdTech platform, 500+ schools) and as a **freelance** algorithmic trading bot developer with real capital in crypto markets. I don't learn technologies to build tutorials — I learn them because I have a real problem to solve.

---

## 🚀 Proyectos / Projects

---

### 🧠 Cortan v2.0 — SaaS Multi-tenant con IA / AI Multi-tenant SaaS

> 🇪🇸 Plataforma SaaS corporativa multi-tenant. Cada tenant tiene aislamiento total vía **Row Level Security en Supabase**. El módulo `system-agent` es un rol de bypass total que permite a los agentes de IA ejecutar flujos de trabajo sin restricciones, con trazabilidad en logs de auditoría. Integra **pgvector** para memoria semántica persistente en los agentes.

> 🌐 Enterprise multi-tenant SaaS. Each tenant is fully isolated via **Supabase Row Level Security**. The `system-agent` module is a full-bypass role enabling AI agents to execute workflows without restrictions, with full audit log traceability. Uses **pgvector** for persistent semantic memory across agents.

**Stack:** `Next.js 16` `React 19` `Supabase + pgvector` `Firebase` `Stripe` `WebAuthn` `Twilio` `WhatsApp` `Gemini AI` `Ollama` `Three.js` `Playwright` `Docker`

[![Showcase](https://img.shields.io/badge/Ver_Showcase_/_View_Showcase_(código_privado)-A855F7?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Juan23456788977/cortan-showcase)

---

### 🛒 VECommerce — E-commerce Venezuela-first

> 🇪🇸 Monorepo producción-ready con backend en **FastAPI** y frontend en **Next.js TypeScript**. Autenticación con **JWT + bcrypt**, migraciones versionadas con **Alembic**, caché de sesiones en **Redis**, almacenamiento S3-compatible con **MinIO**, y pagos con **Stripe Webhooks**.

> 🌐 Production-ready monorepo with a **FastAPI** backend and **Next.js TypeScript** frontend. **JWT + bcrypt** auth, versioned migrations with **Alembic**, **Redis** session caching, **MinIO** S3-compatible storage, and **Stripe Webhooks** payment flow.

**Stack:** `FastAPI` `Python` `Next.js` `TypeScript` `PostgreSQL` `SQLAlchemy` `Alembic` `Redis` `MinIO` `Stripe` `Docker Compose`

[![Showcase](https://img.shields.io/badge/Ver_Showcase_/_View_Showcase_(código_privado)-F59E0B?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Juan23456788977/vecommerce-showcase)

---

### 🤖 AI Email Assistant — Clasificador ML + Respuesta Automática / ML Classifier + Auto-Response

> 🇪🇸 Sistema que lee emails entrantes, los clasifica por prioridad con un **modelo entrenado con scikit-learn**, y genera respuestas con **OpenAI GPT**. Los servicios `classifier.py` y `llm_response.py` están desacoplados para poder reemplazar el LLM sin tocar la lógica de clasificación.

> 🌐 System that reads incoming emails, classifies them by priority using a **trained scikit-learn model**, and generates responses via **OpenAI GPT**. `classifier.py` and `llm_response.py` are decoupled so the LLM can be swapped without touching the classification logic.

**Stack:** `FastAPI` `Python` `OpenAI API` `scikit-learn` `Docker Compose`

[![Showcase](https://img.shields.io/badge/Ver_Showcase_/_View_Showcase_(código_privado)-10B981?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Juan23456788977/ai-email-assistant)

---

### 🎓 PasantConnect — Sistema de Pasantías / Internship Management System

> 🇪🇸 Proyecto de tesis de grado para el I.T.A.T. Sistema completo: registro de pasantes/empresas/supervisores, control de horas, chat en tiempo real, subida de fotos, dark mode y panel admin. Contraseñas con **bcrypt** (`$2y$10$`), roles via `enum` en MySQL validados en cada endpoint.

> 🌐 Graduation thesis for I.T.A.T. Full system: intern/company/supervisor management, hour tracking, real-time chat, photo uploads, dark mode, and admin panel. Passwords hashed with **bcrypt** (`$2y$10$`), roles enforced via MySQL `enum` validated at every endpoint.

**Stack:** `PHP 7.3` `MySQL` `Vanilla JavaScript ES6+` `CSS3` `bcrypt` `AJAX` `Sessions`

[![Código / Code](https://img.shields.io/badge/Ver_Código_/_View_Code_(público)-3ECF8E?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Juan23456788977/PasantConnect)

---

### 📈 Bots de Trading Algorítmico / Algorithmic Trading Bots

> 🇪🇸 Bots de grid trading para pares volátiles (SOL/USDT, BNB/USDT). Conexión a Binance vía **WebSockets** para order book en tiempo real sin polling. Lógica de grid con niveles automáticos según volatilidad, stop-loss automático y alertas por Telegram.

> 🌐 Grid trading bots for volatile pairs (SOL/USDT, BNB/USDT). Connected to Binance via **WebSockets** for real-time order book without polling. Auto grid levels based on volatility, automatic stop-loss, and Telegram alerts on execution.

**Stack:** `Python` `Binance API` `WebSockets` `asyncio` `Telegram Bot API`

*🔒 Código privado por acuerdo con clientes / Private by client agreement*

---

## 🛠️ Stack Técnico / Tech Stack

| Área / Area | Tecnologías / Technologies |
|-------------|---------------------------|
| **Frontend** | Next.js · React 19 · TypeScript · Tailwind · Framer Motion · Three.js |
| **Backend** | FastAPI · Node.js · PHP · Python · Express |
| **Bases de datos / DBs** | Supabase (pgvector) · Firebase · PostgreSQL · Redis · MySQL |
| **IA & ML** | Gemini AI · OpenAI · scikit-learn · Ollama · Agentes Autónomos |
| **Pagos / Payments** | Stripe Checkout · Stripe Webhooks |
| **Comunicaciones / Comms** | Twilio Voice · WhatsApp (Baileys) · Resend · Telegram API |
| **Auth** | Firebase Auth · JWT · WebAuthn · bcrypt · Sessions |
| **DevOps** | Docker · Docker Compose · Vercel · Firebase Hosting |
| **Testing** | Playwright (E2E) · Vitest (Unit) · Testing Library |

---

## 📊 Estadísticas / Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Juan23456788977&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A855F7&icon_color=A855F7&text_color=ffffff&locale=es" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Juan23456788977&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A855F7&text_color=ffffff" height="160"/>
</div>

---

## 📫 Contacto / Contact

🇪🇸 Abierto a oportunidades remotas, colaboraciones y proyectos freelance.
🌐 Open to remote opportunities, collaborations and freelance projects.

- 📧 cortezurreajuanalberto@gmail.com
- 💼 [Portafolio completo / Full portfolio](https://github.com/Juan23456788977/Portafolio)

<div align="center">
  <br/>
  <i>🇪🇸 "No sigo hojas de ruta. Las construyo."</i><br/>
  <i>🌐 "I don't follow roadmaps. I build them."</i>
</div>
