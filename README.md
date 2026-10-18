# UniBLOGic

College community platform with user authentication, communities, posts, comments, and media-upload services. This is not the chess tournament project described by the previous README.

## Repository layout

- `frontend/`: React 18, TypeScript, Vite, Tailwind CSS, Redux, and UI components.
- `backend/Backend Server/`: Express/TypeScript API with Prisma, authentication, community, post, and user routes.
- `backend/Video Transcoder/`: media-processing service.
- `backend/Video_Stream/`: video infrastructure and supporting files.

## Local development

Frontend:

```bash
cd frontend
npm install
npm run dev
```

The frontend also provides `npm run build`, `npm run preview`, and `npm run lint`.

Backend:

```bash
cd "backend/Backend Server"
npm install
npm run dev
```

The backend's dev script compiles TypeScript and launches `dist/server.js`. Set up its database and provider configuration first. A reproducible environment-variable example and full multi-service startup guide are still needed. The backend's test command is a placeholder, not an automated test suite.

## Deployment status

No current live deployment is verified here. A complete deployment needs database configuration, authentication, storage/media providers, service URLs, and review of tracked environment files. Do not assume static frontend hosting alone runs the backend or video services.
