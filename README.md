# MyTaskFlow 🚀

MyTaskFlow is a modern productivity and task management SaaS application with
Kanban workflows, agency support, and a Supabase-powered backend.

## ✨ Features
- Kanban-based task management
- Personal & agency workspaces
- Supabase authentication
- Row Level Security (RLS)
- Real-time updates
- Project templates & dependencies
- Edge Functions support

## 🛠 Tech Stack
- Frontend: React + TypeScript + Vite
- Styling: Tailwind CSS
- Backend: Supabase (PostgreSQL, Auth, RLS)
- Hosting: Vercel / Netlify

## 📂 Project Structure
- `src/` – Frontend application
- `supabase/` – Database schema & edge functions
- `public/` – Static assets
- `PRD.md` – Product requirements
- `backend.md` – Backend architecture

## ⚙️ Environment Setup

```env
VITE_SUPABASE_URL=your_project_url
VITE_SUPABASE_ANON_KEY=your_anon_key
