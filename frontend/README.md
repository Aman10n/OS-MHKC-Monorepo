# OS-MHKC Frontend

The Next.js client for the [OS-MHKC Mental Health Knowledge Companion](../README.md).

## Stack

- Next.js 16 and React 19
- TypeScript
- Tailwind CSS 4
- Framer Motion
- Axios
- Supabase JavaScript client

## Start locally

```bash
npm install
cp .env.example .env.local
npm run dev
```

Open `http://localhost:3000`. The frontend expects the FastAPI service at `http://localhost:8000` unless `NEXT_PUBLIC_API_URL` is changed.

See the [root README](../README.md) for architecture, backend setup, environment variables, and the responsible-use notice.
