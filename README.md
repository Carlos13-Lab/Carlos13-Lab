# Carlos Díaz — Full Stack Developer

**TypeScript · Node.js (Fastify, Express) · React / Next.js · Conversational AI**
Based in Venezuela (UTC-4) · Open to remote work, full-time or contract · Español nativo

I build production backends, web apps and AI voice/chat agents for insurance, payments and telecom companies. I care about reliability (retries, circuit breakers, idempotency), observability and code that stays easy to change.

## What I've been building (2025–2026)

- **AI sales voice agent (ElevenLabs).** Designed the agent's prompt, knowledge base and guardrails; compared LLMs with automated WebSocket regression tests and moved from GPT-5.1 to Claude Haiku, cutting turns from up to 94 to at most 45 words in tests; fixed brand mis-transcription with ASR keywords and a pronunciation dictionary.
- **AI assistant microservice for a mobile app.** Fastify + OpenAI Responses API with tool calling, SSE chat and live voice via ElevenLabs; 64 test files.
- **Collections and scheduled jobs (Node.js / MySQL).** Batched, de-duplicated, single-flight cron jobs with test mode; a debt campaign that delivered 1,884 e-mails and surfaced 156 failed payments missing from the financing report.
- **API gateway for three insurers.** Fastify adapters to a common contract, circuit breaker with backoff, RFC 7807 errors, OpenTelemetry + Prometheus + Grafana.
- **Real-time bank webhooks (FibexTelecom).** Node.js/TypeScript API processing payments from 4 Venezuelan banks, with JWT, IP allow-listing, retries and alerts.
- **Marketing site rebuild (Next.js).** Live pricing from an API, sign-up and payment flow (PayPal, Pago Móvil), SEO/GEO with JSON-LD and llms.txt.

Most of this work lives in private client repositories. Public, client-free versions of the patterns:

- **[voice-agent-test-kit](https://github.com/Carlos13-Lab/voice-agent-test-kit)** — regression tests for ElevenLabs voice agents (word limits, required/forbidden phrases, hang-up) over scripted WebSocket calls, plus a TTS→STT check that a pronunciation dictionary works.
- **[resilient-api-gateway](https://github.com/Carlos13-Lab/resilient-api-gateway)** — Fastify gateway that unifies three upstream APIs: per-upstream adapters, circuit breaker, retries with jitter, RFC 7807 errors, JWT scopes, OpenTelemetry and a Prometheus/Grafana dashboard via `docker compose up`.

## Stack

- **Backend:** Node.js, TypeScript, Fastify, Express, REST, OpenAPI, Zod, BullMQ, webhooks, cron jobs
- **Frontend:** React, Next.js (App Router), TanStack Router/Query, Tailwind CSS, Angular, Ionic
- **Data:** PostgreSQL, MySQL, SQL Server, MongoDB, Redis, Prisma
- **AI:** ElevenLabs Agents, OpenAI (Responses API, tool calling, vision), Claude, n8n, WhatsApp Business API, Twilio
- **Ops:** Docker, Nginx, GitHub Actions, OpenTelemetry, Prometheus, Grafana, Loki, Sentry, Datadog

## Contact

[LinkedIn](https://www.linkedin.com/in/carlosdiazdeveloper/) · [carlosrdf45@gmail.com](mailto:carlosrdf45@gmail.com)
