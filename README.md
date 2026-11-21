# Stay Safe

**Connected care, guaranteed safety.**

Stay Safe is an accessible emergency alert platform built for elderly dependents (including users with low vision, hand tremors, and limited tech familiarity) and their family carers.

---

## Repositories

| Repository | Description | Live |
| :--- | :--- | :--- |
| [`stay-safe-front`](https://github.com/<ORG>/stay-safe-front) | Accessible PWA built with React 19, Vite, Tailwind CSS v4, Radix UI, and Phosphor Icons. | [stay-safe-app.netlify.app](https://stay-safe-app.netlify.app) |
| [`stay-safe-api`](https://github.com/<ORG>/stay-safe-api) | REST & WebSocket API built with Node.js, Express 5, PostgreSQL, Resend, and Nominatim. | [Health Check](https://stay-safe-api-1.onrender.com/health) |
| [`Stay-Safe`](https://github.com/<ORG>/Stay-Safe) | Project landing page and interactive screen showcase. | — |

---

## How It Works

1. **One-time family setup**: A carer creates the family account and sets up `carer` and `dependent` profiles.
2. **Elderly-first interface**: The dependent device stays signed in on a single-action screen with a large **AJUDA** button, 3-second cancelable trigger, full-screen alert states, on-screen 72px PinPad, and multisensory feedback (vibration, sound, and `pt-BR` voice).
3. **Real-time response**: Alerts are delivered immediately via WebSockets and email (with GPS coordinates and Google Maps link) and automatically escalate on the server if unanswered after 30 seconds.

---

## Tech Stack

- **Frontend**: React 19, Vite 8, Tailwind CSS v4, Radix UI, Phosphor Icons, Fontsource (`Atkinson Hyperlegible Next` & `Fraunces`), `vite-plugin-pwa`, Vitest
- **Backend**: Node.js, Express 5, `ws` (WebSockets), PostgreSQL (`pg`), `bcrypt`, `jsonwebtoken`, Resend, OpenStreetMap Nominatim, `node:test` + Supertest
- **Infrastructure**: Netlify (Frontend), Render (API), Supabase (PostgreSQL), GitHub Actions (CI)
