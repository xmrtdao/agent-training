# Agent Training Syllabus

Structured curriculum covering everything an XMRT DAO agent needs to know.

## Module 1: Ecosystem APIs

| Lesson | Topics | Est. Time |
|--------|--------|-----------|
| 1.1 | Relay endpoints — health, status, tools, fleet chat | 15 min |
| 1.2 | Supabase functions — calling, parameters, auth | 20 min |
| 1.3 | Mesh networking — gossipsub, peer discovery, P2P | 20 min |
| 1.4 | Fleet chat — sending, polling, agent labels | 10 min |

## Module 2: Third-Party APIs

| Lesson | Topics | Est. Time |
|--------|--------|-----------|
| 2.1 | Resend — sending emails, webhooks, inbox polling | 15 min |
| 2.2 | Typefully — scheduling tweets, drafts, social set ID | 10 min |
| 2.3 | Ollama — local LLM, models, API | 10 min |

## Module 3: Edge Functions

| Lesson | Topics | Est. Time |
|--------|--------|-----------|
| 3.1 | Deploying a new function via Supabase CLI/API | 20 min |
| 3.2 | Calling edge functions from agents | 10 min |

## Module 4: CLI Tools

| Lesson | Topics | Est. Time |
|--------|--------|-----------|
| 4.1 | Node health check script | 5 min |
| 4.2 | Campaign scripts — festival-campaign, seasonal-scraper | 15 min |

## Module 5: Step-by-Step Tutorials

| # | Tutorial | 
|---|----------|
| 5.1 | Fetching Full Email Body from Inbox |
| 5.2 | Registering on the Mesh Network |

## Module 6: Deployment

| Lesson | Topics | Est. Time |
|--------|--------|-----------|
| 6.1 | Termux Hermes install — Android phone setup | 30 min |
| 6.2 | Node architecture — all processes, ports, startup sequence | 15 min |

## Module 7: Content Publishing

| Lesson | Topics | Est. Time |
|--------|--------|-----------|
| 7.1 | Bot-Optimized vs Human-Optimized content | 10 min |
| 7.2 | Publishing pipeline — MuAPI → Paragraph → Typefully | 15 min |

## Reference

- [NODE_ARCHITECTURE.md](06-deployment/node-architecture.md)
- [Issue #13](https://github.com/xmrtdao/mobilemonero/issues/13) — Gossipsub Mesh
- [Issue #47](https://github.com/xmrtdao/mobilemonero/issues/47) — This repo
