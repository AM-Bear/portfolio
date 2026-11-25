# Progress

Goal: ship Asher's portfolio at https://ashermills.netlify.app so he can paste it into the Palantir Meritocracy Fellowship "Portfolio URL" field.

## Link checks (2026-11-25)

| Item | Result | Use |
|---|---|---|
| thirdlineai.com | 200 | link |
| github.com/AM-Bear | 200 | link |
| linkedin.com/in/asher-mills-0559b73ba | 999 to scripts; confirmed his own profile in his signed-in Chrome | link |
| mynote-ten.vercel.app | 200, opens on sign-in page | link, labelled sign-in required (Asher's call) |
| money-ball-betting.replit.app (Moneyline) | 404 | no link |
| tapin-nfc.netlify.app (Tap In) | 401, password-protected | no link |
| Thirdline-LLC/NFC-Attendance-Scanner | PRIVATE (brief said public) | no link |
| AM-Bear/mynote, AM-Bear/dealflow-ai, Thirdline-LLC/cclp-supply, AM-Bear/m-brain-gateway | PRIVATE | no link |

## Plan

- [x] Link and repo checks
- [x] Repo `AM-Bear/portfolio` (public) and vault folder `02 Projects/Portfolio/`
- [ ] Design questions to Asher (3, one at a time)
- [ ] Kombai brainstorm: 4 directions (hero, one project card, phone view) — finish line: Asher picks
- [ ] Remix rounds until Asher locks one — finish line: Asher says "that's the one"
- [ ] Plan grilled by `omega-plan-griller` before any build
- [ ] Build: sections hero, now-building strip, projects, experience, leadership, education, skills, contact; content in `src/content.ts`
- [ ] Meta: title, description, Open Graph, og:image 1200x630, favicon; resume PDF link
- [ ] Checks: `npm run build` passes; Lighthouse mobile perf and a11y 90+; no horizontal scroll at 375px; every outbound link 200 (LinkedIn excepted, see above)
- [ ] Local preview shown to Asher
- [ ] Deploy to Netlify `ashermills` only after Asher says go; connect repo so `main` redeploys
- [ ] Vault session log
