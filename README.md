<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&pause=1000&color=A855F7&center=true&vCenter=true&width=750&lines=Hola%2C+soy+Juan+Cortez+%F0%9F%91%8B;Desarrollador+Full-Stack+%7C+18+años;Construyo+SaaS%2C+bots+y+sistemas+de+IA;Caracas%2C+Venezuela+%F0%9F%87%BB%F0%9F%87%AA" alt="Typing SVG" />

<br/>

[![Email](https://img.shields.io/badge/cortezurreajuanalberto%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cortezurreajuanalberto@gmail.com)
[![Portafolio](https://img.shields.io/badge/Ver_Portafolio_Completo-A855F7?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Juan23456788977/Portafolio)

</div>

---

## 👨‍💻 Sobre mí

Soy desarrollador Full-Stack venezolano, 18 años. Trabajo simultáneamente como **pasante de desarrollo y QA en Akdemia** (plataforma EdTech con 500+ colegios activos) y como **desarrollador freelance de bots de trading algorítmico** para clientes con capital en mercados de criptomonedas.

No aprendo tecnologías para hacer tutoriales. Las aprendo porque tengo un problema real que resolver.

---

## 🚀 Proyectos Principales

### 🧠 Cortan v2.0 — SaaS Multi-tenant con IA
> *Mi proyecto más ambicioso. En desarrollo activo.*

Plataforma SaaS corporativa multi-tenant construida desde cero. Cada "tenant" (taller/empresa) tiene su propio espacio aislado mediante **Row Level Security en Supabase**, con un sistema de roles granular (`pasante`, `moderador`, `admin`, `system-agent`).

El módulo más complejo es el **God-Mode System**: un rol `system-agent` con permisos de bypass total que permite a los agentes de IA ejecutar flujos de trabajo sin restricciones de RLS, manteniendo trazabilidad completa en logs de auditoría.

Integra **pgvector** para sincronización offline de embeddings vectoriales — los agentes tienen memoria semántica persistente aunque el LLM no la tenga nativamente.

**Stack real:** Next.js 16 (App Router) · React 19 · Supabase (PostgreSQL + pgvector) · Firebase (Auth + Firestore) · Stripe Webhooks · WebAuthn (SimpleWebAuthn) · Twilio Voice · WhatsApp (Baileys) · Gemini AI SDK · Ollama (qwen2.5-coder) · Three.js + React Three Fiber · Playwright · Docker

[![Showcase](https://img.shields.io/badge/Ver_Showcase_(código_privado)-A855F7?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Juan23456788977/cortan-showcase)

---

### 🛒 VECommerce — E-commerce Venezuela-first
> *Monorepo producción-ready.*

Plataforma de comercio electrónico diseñada para el mercado venezolano. Arquitectura monorepo con backend en **FastAPI** (Python) y frontend en **Next.js TypeScript**.

El backend maneja autenticación con **JWT + bcrypt** (`python-jose` + `passlib`), gestiona el esquema de base de datos con **Alembic** para migraciones versionadas, y usa **Redis** para caché de sesiones. **MinIO** actúa como storage S3-compatible para imágenes de productos. El flujo de pagos corre sobre **Stripe Webhooks**.

**Stack real:** FastAPI 0.115 · Uvicorn · SQLAlchemy 2.0 · PostgreSQL · Alembic · Redis · MinIO · Stripe · Next.js · TypeScript · Tailwind · Docker Compose · Pydantic Settings

[![Showcase](https://img.shields.io/badge/Ver_Showcase_(código_privado)-F59E0B?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Juan23456788977/vecommerce-showcase)

---

### 🤖 AI Email Assistant — Clasificador + Respuesta Automática
> *Automatización real aplicada al soporte al cliente.*

Sistema full-stack que automatiza el soporte por correo electrónico. El flujo es: leer email entrante → clasificar prioridad con un **modelo entrenado con scikit-learn** → generar respuesta contextual con **OpenAI GPT** → enviar respuesta automática.

El clasificador es un modelo de ML propio entrenado sobre datos reales de soporte, no un prompt engineering genérico. Los servicios `classifier.py` y `llm_response.py` están desacoplados intencionalmente para poder reemplazar el LLM sin tocar la lógica de clasificación.

**Stack real:** FastAPI · Python · OpenAI API · scikit-learn · Docker Compose · Arquitectura de microservicios

[![Showcase](https://img.shields.io/badge/Ver_Showcase_(código_privado)-10B981?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Juan23456788977/ai-email-assistant)

---

### 🎓 PasantConnect — Sistema de Gestión de Pasantías
> *Proyecto de tesis de grado. Código 100% público.*

Sistema web completo desarrollado como tesis para el **I.T.A.T. (Instituto Técnico de Telemática)**. Gestiona el ciclo completo de pasantías: registro de pasantes/empresas/supervisores, asignación, control de horas, sistema de chat entre pasante y supervisor, subida de fotos de perfil, dark mode, y panel de administración completo.

Las contraseñas se hashean con **bcrypt** (`password_hash` de PHP con algoritmo `$2y$10$`). El sistema de roles funciona con `enum` en MySQL (`pasante`, `moderador`, `admin`) validado en cada endpoint PHP antes de ejecutar cualquier operación.

**Stack real:** PHP 7.3 · MySQL / MariaDB · HTML5 · CSS3 · Vanilla JavaScript (ES6+) · AJAX · bcrypt · Sessions · XAMPP

[![Código](https://img.shields.io/badge/Ver_Código_Completo-3ECF8E?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Juan23456788977/PasantConnect)

---

### 📈 Bots de Trading Algorítmico
> *Freelance — clientes con capital real en mercados crypto.*

Bots de grid trading para pares volátiles (SOL/USDT, BNB/USDT). Conectan a Binance vía **WebSockets** para recibir el order book en tiempo real sin polling. La lógica de grid calcula automáticamente los niveles de entrada/salida según el rango de volatilidad del par y ajusta el tamaño de posición al capital disponible.

El sistema incluye gestión de riesgo: stop-loss automático si el precio sale del rango configurado, y alertas por Telegram cuando se ejecuta una orden.

**Stack real:** Python · Binance API (REST + WebSockets) · Telegram Bot API · asyncio

*🔒 Código privado por acuerdo con clientes.*

---

## 🛠️ Stack Técnico

```
Frontend ────── Next.js · React 19 · TypeScript · Tailwind · Framer Motion · Three.js
Backend  ────── FastAPI · Node.js · PHP · Python · Express
Bases de datos ─ Supabase (pgvector) · Firebase · PostgreSQL · Redis · MySQL · MariaDB
IA & ML ──────── Gemini AI · OpenAI · scikit-learn · Ollama · Agentes Autónomos
Pagos ────────── Stripe (Checkout + Webhooks)
Comunicaciones ─ Twilio Voice · WhatsApp (Baileys) · Resend · Nodemailer · Telegram API
Auth ─────────── Firebase Auth · JWT · WebAuthn (biométrico) · bcrypt · Sessions
DevOps ───────── Docker · Docker Compose · Vercel · Firebase Hosting
Testing ──────── Playwright (E2E) · Vitest (Unit) · Testing Library
```

---

## 📊 Estadísticas

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Juan23456788977&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A855F7&icon_color=A855F7&text_color=ffffff" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Juan23456788977&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A855F7&text_color=ffffff" height="165"/>
</div>

---

## 📫 Contacto

Estoy abierto a **oportunidades remotas**, colaboraciones y proyectos freelance.

- 📧 **Email:** cortezurreajuanalberto@gmail.com
- 💼 **Portafolio completo:** [github.com/Juan23456788977/Portafolio](https://github.com/Juan23456788977/Portafolio)

<div align="center">
  <br/>
  <i>"No sigo hojas de ruta. Las construyo."</i>
</div>
