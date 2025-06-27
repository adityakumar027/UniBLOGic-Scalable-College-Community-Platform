# 🧠 Uniblogic

**Uniblogic** is a scalable, real-time chess tournament platform engineered for university-level competitions and high-concurrency environments. It supports Swiss-system pairing, Buchholz scoring for fair tie-breaking, and real-time multiplayer gameplay.

> Built with a modern full-stack architecture using TypeScript, TurboRepo, Express, WebSockets, Prisma, PostgreSQL, and React.

---

## 🚀 Features

- ♟️ **Real-Time Chess Engine** — Powered by WebSockets for minimal-latency gameplay
- 🧮 **Swiss Tournament System** — Dynamic match pairing with Buchholz tie-breaking
- 🧩 **Modular Monorepo** — Built using TurboRepo for scalable team collaboration
- 💾 **Robust Backend** — Express + Prisma + PostgreSQL
- 💡 **Modern Frontend** — Vite + React + Tailwind UI
- 🛠️ **CI/CD & Deployment** — PM2, NGINX, and EC2 support for reliable production deployment



## ⚙️ Setup & Installation

### 1. Clone the repo

```bash
git clone https://github.com/your-username/uniblogic.git
cd uniblogic
2. Install dependencies
bash
Copy
Edit
pnpm install
3. Setup Environment Variables
bash
Copy
Edit
cp apps/backend2/.env.example apps/backend2/.env
cp apps/frontend/.env.example apps/frontend/.env
Make sure to set your actual values (DB URL, WebSocket URL, etc.) in the .env files.

🧪 Running Locally
Start Backend
bash
Copy
Edit
cd apps/backend2
npx prisma generate
pnpm dev
Start Frontend
bash
Copy
Edit
cd apps/frontend
pnpm dev
Then go to: http://localhost:5173/game

🔗 Environment Variables
apps/frontend/.env
env
Copy
Edit
VITE_BASE_URL=http://localhost:3001
VITE_WEB_SOCKET_URL=ws://localhost:3001/ws
apps/backend2/.env
env
Copy
Edit
DATABASE_URL=postgresql://<username>:<password>@localhost:5432/uniblogic
PORT=3001
📸 Screenshots



🛠️ Tech Stack
Frontend: React, Vite, TailwindCSS

Backend: Express.js, WebSockets, Prisma, PostgreSQL

Monorepo: TurboRepo

Deployment: AWS EC2, PM2, NGINX

CI/CD: GitHub Actions (optional)

🧑‍💻 Author
Aditya Kumar
IIIT Gwalior 

