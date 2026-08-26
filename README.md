## Dylan Peellaert — Applied AI & Product Software Engineer

I build AI systems, and I build the instrument that proves they hold.

Every number below has a command behind it. If a claim cannot be replayed, it is not on this page.

---

### In production since May 2026

Two products I designed and built alone, running at a carpentry and roofing company.

**An agent that handles the company's inbox.** It reads each message, classifies it, extracts the data from quote PDFs, updates the client and site records, and drafts the reply.
`Python 3.11` · `FastAPI` · Claude ReAct agent, **37 tools** · Gmail + Microsoft Graph · Notion · Sentry · Railway
**966 of 975 tests green in 15 s** · 255 commits · v4.2.0

**The field app the technicians carry.** Offline-first: entries, geotagged photos and an adaptive questionnaire are queued locally and resynchronised when the network comes back. PDF report, manager dashboard.
`PWA + Service Worker` · `Supabase (PostgreSQL + RLS)` · `Playwright`
**91 unit tests green in 1.4 s** · 189 declared test cases · 381 commits · v1.0.1

> No usage figures anywhere on this page. Nothing on the client side is instrumented, so any number of users, interventions or hours saved would be invented.

---

### What I work on most — [C Brain](https://github.com/Yuno15-bb/c-brain) `Apache-2.0`

Persistent memory for CLI agents: what you work out once is distilled into a note, filed, linked, and surfaced again in the next session, from any project. It makes no request of its own — no telemetry, no account.

**46 published releases · 57 tags · 168 commits.** A leak check with **21 markers** stands between the work and every push.

That check blocked its own author for nine days and thirty-seven commits. It was lifted by adding a counter-proof — a closed list of literals, allowed only under `tests/`, each one paired with a case proving the non-exempted variant still blocks — never by disarming a marker. The CI replays the check over the entire git history, not just the tip.

---

### How I work

**I build the control that could prove me wrong, then I sabotage it to check that it really goes red.** A test that has never failed protects nothing.

On the memory engine — 1 542 commits over two months, 47 test benches, 16 written architecture decisions — I refuted three of my own retrieval hypotheses by measurement, and kept the refutations written down instead of deleting them. A recall bench refuses a commit that degrades ranking, whoever wrote it.

---

### Links

- **Portfolio** — [yuno15-bb.github.io](https://yuno15-bb.github.io)
- **C Brain** — [github.com/Yuno15-bb/c-brain](https://github.com/Yuno15-bb/c-brain)

Open to AI and product engineering roles, and to work with small companies.
