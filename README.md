# Hi, I'm Sagar 👋

Backend-leaning full-stack developer, now working towards AI and data engineering. I build complete systems — Spring Boot APIs with real
auth and database design, and Next.js frontends that consume them — and I deploy them rather
than leaving them on `localhost`.

I care about the parts that are easy to skip: role-based access control, rate limiting, schema and index design, CI, and documentation that lets someone else run the project.

---

## AI and data - where I am heading

I am moving towards AI engineering, and I am clear about the starting point: one solid academic
project, genuine interest, and a lot of deliberate practice ahead.

- **Academic project - medicinal plant identification.** In Jupyter notebooks I prepared leaf
  images with Python image-processing libraries and trained CNN-based models, along with related
  architectures, to classify plant species from photographs.
- **What the project taught me.** The whole loop, not just the model: dataset preparation and
  augmentation, training runs, checking results honestly, and going back to fix the data or the
  architecture when the numbers were not good enough.
- **What I am doing now.** Strengthening Python and SQL, and learning the data-engineering side -
  storage, data modelling, pipelines - that decides whether an AI model is useful outside a
  notebook.

I am ready to adapt and learn quickly. Python, data engineering and AI engineering roles are
where I want to go next, and I would rather be judged on how fast I learn than on the length of
my CV.

## Featured projects

### 🚕 [royal-travels](https://github.com/SaGaru007/royal-travels)

A cab and travel booking platform, built end to end.

- **Frontend:** Next.js 14 + TypeScript — public booking flow, live trip tracking, role-based admin console
- **Backend:** Spring Boot 4 / Java 21 REST API — JWT auth, `ProblemDetail` errors, rate limiting
- **Data:** PostgreSQL (Supabase), indexed for search and list sorting
- **Ops:** Docker on Render, Vercel frontend, GitHub Actions CI, MIT licensed

Three distinct interfaces in one system: customers book and track, admins dispatch and manage
fleet and drivers, and drivers get a passwordless trip sheet authorised by trip reference plus
their registered phone.

[Live demo](https://royal-travels-plum.vercel.app) · [API health](https://royal-travels-api.onrender.com/api/health)

### 💳 [stripe-payment-service](https://github.com/SaGaru007/stripe-payment-service)

A payment-provider adapter that isolates Stripe from application code.

- Spring Boot 3.4 / Java 17, packaged with Docker
- Create, retrieve and expire Stripe Checkout sessions
- Signature-verified webhooks (`Webhook.constructEvent`) with async event processing, so payment
  state is decided by webhook rather than by a browser redirect the user can close
- Stable `ErrorCodeEnum` codes instead of leaked provider errors

### 🛍️ [nextjs-ecommerce-storefront](https://github.com/SaGaru007/nextjs-ecommerce-storefront)

Next.js 16 / React 19 / Tailwind v4 storefront — catalogue, dynamic product routes, search and a
context-driven cart. Frontend-focused; the API, auth and checkout are documented next steps.

### 👤 [developer-portfolio](https://github.com/SaGaru007/developer-portfolio)

Express + SQLite portfolio with an admin panel and image uploads.

---

## Toolbox

**Languages** Java · TypeScript · JavaScript · SQL · Python
**Backend** Spring Boot · Spring Security · JPA/Hibernate · Express · REST
**Frontend** Next.js (App Router) · React · Tailwind CSS
**Data** PostgreSQL · MySQL · SQLite
**AI / data** Jupyter · NumPy · pandas · image processing · CNN training
**Tooling** Docker · Git · GitHub Actions · Maven · Vercel · Render

## Currently

- Deepening database work: query tuning, indexing strategy, and transaction isolation
- Writing a from-scratch MySQL course - fundamentals through window functions, with a
  runnable practice schema: [learning/mysql](https://github.com/SaGaru007/royal-travels/tree/main/learning/mysql)

## Get in touch

📧 [sagarhadapad200@gmail.com](mailto:sagarhadapad200@gmail.com)

Open to backend, full-stack, Python, data engineering and AI engineering roles.
