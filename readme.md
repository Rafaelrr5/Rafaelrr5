# Rafael Rocha Ribeiro

Software engineer building on SYDLE ONE by day, after a stretch as a ServiceNow
consultant; building tooling for AI coding agents the rest of the time. I care
about the unglamorous half of both: the verification step, the memory that
survives the session, the check that catches the thing nobody would have found.

Based in Juiz de Fora, Brazil. Also teach programming and robotics to high school
students, which is where I learned that if you cannot explain the failure, you do
not understand the system.

---

## Selected work

**[agent-cortex](https://github.com/Rafaelrr5/agent-cortex)** — long-term memory for
coding agents, in one file, plus 39 procedures that keep delegated work honest.
An agent's context window is short-term memory; this is the part that survives.
Memory travels as text and the search index is derived, so it syncs through git
without ever putting a live SQLite file there. The ranking is embeddings-led with
lexical as a narrow tiebreak, because a naive fusion of the two measured *worse*
than either signal alone.

**[Minecraft-Modpack-Assistant](https://github.com/Rafaelrr5/Minecraft-Modpack-Assistant)**
— an AI assistant for the whole modpack lifecycle, from an idea to a pinned,
conflict-checked pack. Every operation is a dry run by default, and the game
instance is never touched without a backup and an explicit confirmation —
enforced in code, not by convention. Pre-1.0 alpha, and the README says exactly
which parts are.

**[financas-br](https://github.com/Rafaelrr5/financas-br)** (Extrato Claro, pt-BR) —
imports Brazilian bank and brokerage statements (Inter, Mercado Pago, B3) into a
local SQLite and shows them in an offline dashboard. Nothing leaves the machine:
no server, no account, no telemetry, Python standard library only.

**[alexa-hermes](https://github.com/Rafaelrr5/alexa-hermes)** (pt-BR) — a voice bridge
from Alexa to a local AI agent, at zero cost. Alexa gives an endpoint about eight
seconds and real work takes minutes, so the skill does not wait: it queues the
request, and you ask for the answer on a second turn.

**[claude-autosend](https://github.com/Rafaelrr5/claude-autosend)** — schedule
prompts to fire into Claude Code CLI sessions at a chosen wall-clock time.

---

## Writing

Short pieces on working with AI coding agents, each anchored to something in
agent-cortex you can read and run:

- [Implemented and tested is not evidence](https://github.com/Rafaelrr5/agent-cortex/blob/main/articles/implemented-and-tested-is-not-evidence.md)
- [Why your agent forgets everything](https://github.com/Rafaelrr5/agent-cortex/blob/main/articles/why-your-agent-forgets-everything.md)
- [Five agents, one repo](https://github.com/Rafaelrr5/agent-cortex/blob/main/articles/five-agents-one-repo.md)
- [Hooks: the seam in your agent you did not know was there](https://github.com/Rafaelrr5/agent-cortex/blob/main/articles/hooks-the-seam-you-did-not-know.md)
- [Why brand skills matter more than brand guidelines](https://github.com/Rafaelrr5/agent-cortex/blob/main/articles/why-brand-skills-matter.md)

---

## What I actually work on

**Enterprise platforms** — SYDLE ONE today. Before that, ServiceNow: ITSM,
CMDB/CSDM, Flow Designer, scoped applications, and the agentic side of the
platform. Certified: CSA, CIS-ITSM, CIS-Data Foundations, Now Assist Essentials,
Now Assist Executive, Agentic AI Executive.

**AI agents and LLM tooling** — orchestration, delegated execution with a real
verification step, retrieval and long-term memory. A recurring finding: an agent's
own report of what it did is a self-report, not evidence, and most of the value is
in the checks you run afterwards.

**Full-stack** — TypeScript and Python, React and Next.js, Node, React Native,
Postgres and Supabase.

---

## Reach me

- **Email** — [faelrribeiro3@gmail.com](mailto:faelrribeiro3@gmail.com)
- **LinkedIn** — [rafael-rocha-ribeiro](https://www.linkedin.com/in/rafael-rocha-ribeiro-581bb2202/)
- **Site** — [3rstudios.com.br](https://3rstudios.com.br)

Open to collaborating on agent tooling and to hearing where any of the above is
wrong, especially with a measurement attached.
