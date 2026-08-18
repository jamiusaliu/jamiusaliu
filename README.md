## Saliu Jamiu Olamilekan

AI automation engineer in Lagos, Nigeria. I design, build and ship production AI
systems end to end — from client brief to deployed product.

Most of my work is delivery: architecting the solution, integrating the moving
parts, and verifying that what ships actually does what was needed. I build with
AI assistance and then make sure I can explain every line of it.

---

### Currently building

**[alertmux](https://github.com/jamiusaliu/alertmux)** — natural-hazard alerts from
five official sources, normalised into one CAP-shaped schema with provenance.

Weather warnings from 59 national meteorological agencies via WMO SWIC, US alerts
from NOAA/NWS, global disaster events from GDACS, earthquakes from USGS, and
satellite-observed events from NASA EONET. Python, FastAPI, MIT.

It relays official warnings and never issues them. It never infers a value a source
did not supply — a missing field is `null` and named in `unavailable_fields`, and
severity codes are only translated where the mapping has been confirmed against real
CAP files. The design decisions and their reasoning are written down in
[`docs/DECISIONS.md`](https://github.com/jamiusaliu/alertmux/blob/main/docs/DECISIONS.md),
including the ones that look like mistakes and aren't.

**[dictate](https://github.com/jamiusaliu/dictate)** — offline voice-to-text for
macOS using faster-whisper. Local and private; audio never leaves the machine.

---

### What I work with

**Backend** · Python, FastAPI, Supabase (Postgres, pgvector, RLS), REST APIs
**AI** · Claude, LLM app integration, RAG pipelines, MCP, voice agents (VAPI, LiveKit)
**Orchestration** · n8n, Make.com, Trigger.dev, webhook and background jobs
**Frontend & deploy** · Next.js, TypeScript, Astro, Vercel, Netlify, Railway, Docker

---

### Selected work

Building automation since 2024. Contract and client work, mostly private:

- **Nespresso Professional AU** — FastAPI keyword-research microservice on Railway,
  generating B2B keyword candidates with Claude, validating demand via Google Trends,
  and feeding an n8n pipeline. Live in the client's monthly SEO programme.
- **Voice agents and RAG chatbots** — inbound, outbound, reactivation and no-show
  flows across SMS, Instagram, Facebook and live chat.
- **Multi-tenant CRM automation** — Next.js and Supabase with pgvector, LangGraph
  agents, a human-in-the-loop approval queue, RLS, and HMAC webhook verification.
- **Taught a paid six-week AI automation cohort** to 10+ students, fundamentals
  through hands-on builds.

I also run [JAMIU AI SOLUTION](https://jamiuaisolution.online), where I build free
tools for AI search visibility — measuring whether AI answer engines actually
recommend a brand, and what to fix when they don't.

---

### Contact

[jamiusaliu090@gmail.com](mailto:jamiusaliu090@gmail.com) · [jamiuaisolution.online](https://jamiuaisolution.online)

Open to contract and freelance work building and maintaining AI automation systems.
