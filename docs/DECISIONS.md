# Decisions

## 2026-11-25: Static Vite site on Netlify free, content in one data file

- **Choice:** Vite + React + Tailwind static build (plain HTML/CSS if the locked design is simple enough), deployed to Netlify free as site `ashermills`, with pushes to `main` redeploying. All copy lives in `src/content.ts`.
- **Why:** Reviewers need a fast, phone-friendly page. A static build has no server to break, scores well on Lighthouse, and one content file means every public claim can be fact-checked in one place.
- **Rejected:** `AM-Bear/project-starter` (Next.js, Clerk, Supabase): auth and a database are dead weight for a one-page site.
- **Content rule:** every claim comes from the brief's facts or from a link checked on the day. Links that fail are left off and listed in `docs/progress.md`.
- **Resume:** Asher chose (2026-11-25) to link his Nov 24 resume PDF as-is, knowing it carries his phone number.
