# Keystone article — outline for author

**Working title options** (pick one; the two-word device is the strongest hook):
1. *Engineering Trustworthy Industrial AI* — plain, durable, matches the Foundational term
2. *Two Words That Change Industrial AI* — hook-forward, LinkedIn-friendly
3. *What Is Trustworthy Industrial AI — and Why It Must Be Engineered*

**Role of this article:** Post 0. The program's hub — every later article links back here.
**Target length:** 1,200–1,600 words. **Tone:** practitioner-to-practitioner, zero vendor content.

---

## 1. Hook — capability is not the bottleneck (1–2 paragraphs)

- Industrial AI has never been more capable: foundation models, agents, digital twins, optimization — all advancing fast.
- But no plant manager has ever asked what architecture the model uses. They ask: *can I act on this? Will it hold up in the incident review?*
- Claim in one line: **capability is advancing; trust is not. And trust does not arrive on its own — it has to be engineered.**

## 2. The two words (core section — from the team email, in author's voice)

**"Engineering"** — trust is a discipline, not a hope.
- It has methods, systems, evidence, and tests — like every other engineering discipline.
- Anti-pattern to name: treating trust as something that "somehow gets done" — a disclaimer, a dashboard, a pilot that never scales.

**"Trustworthy"** — operationally defined, or it means nothing.
- The bar: engineers and operators can rely on it. Concretely: **auditable, explainable, repeatable, predictable, testable.**
- Key claim (quote/link Terms page): *trustworthiness is an emergent engineering property, not a model characteristic.* You cannot buy a trustworthy model; you can only engineer a trustworthy system.
- One de-bucketing paragraph: this is not "responsible AI" (policy/ethics lens) and not "AI safety" (frontier-model lens). It is an engineering lens for operational settings where consequences are physical, standards are binding, and accountability is legal.

## 3. Why the industrial bar is different (short — sets up the decomposition)

- Every technology wave raises capability; none of them, by itself, produces auditability, repeatability, or accountability.
- In industrial settings a confident wrong answer is categorically worse than a refusal.
- The sharpest one-line test: **"Who signs?"** (link canonical term). If nobody can sign for an AI-assisted decision, it is not operationally ready.

## 4. The map — seven dimensions (the decomposition)

Frame: to engineer trust you must first decompose the problem. Seven dimensions, following the anatomy of how industrial work gets done — know → reason → decide → act → compose → deploy → sustain value:

1. **Engineering Knowledge** — what the AI knows
2. **Grounded Reasoning** — how the AI reasons
3. **Trustworthy Decisions** — why engineers should trust the decision
4. **Industrial Agents** — how work gets executed
5. **Industrial AI Platforms** — where intelligence lives
6. **Operational Deployment** — how intelligence is deployed safely
7. **Industrial AI Products** — how trust creates lasting business value

Two justification moves (this is what makes it a framework, not a list):
- **Each dimension has a distinctive failure mode.** One sentence each — what breaks when this dimension is neglected (e.g., knowledge: fluent answers ungrounded in the standard that governs the asset; decisions: a recommendation nobody can sign; deployment: a model that worked in the pilot and drifts silently in the plant). Author to supply the examples — lived ones beat invented ones.
- **The dimensions are chosen to outlast tooling waves.** Models will change; the need to know, reason, decide, act, deploy, and sustain will not.

Optional: note that a platform earns trust in its *primitives*, a product earns trust in its *outcomes* (plants the dim-5/dim-7 distinction early; one sentence, no more).

## 5. How this program studies it (method — short)

- **The map vs. the journeys:** dimensions are coordinates; **volumes** are deep arcs across them. A volume may sit on one dimension or cut across several.
- **Canonical vocabulary** with maturity statuses (Foundational → Experimental) — the status ladder is itself an engineering discipline signal. Link the Terms page.
- **Design tests** ("Who signs?") over abstractions.
- Announce Volume I: *The Governed Decision Layer* — starting at dimension 3, because that is where the pain is sharpest today: the ungoverned middle between what AI predicts and what agents do.

## 6. What this is not (3–4 lines)

- Not vendor advocacy. Not model benchmarking. Not trend commentary. Not AI-ethics policy.
- Success = practitioners citing and building on these ideas *because they're useful, not because they're ours* (reuse the about-page line — it should live in both places).

## 7. Close — invitation

- What's next: Volume I articles, weekly-ish.
- Invite practitioners: disagreement and field experience welcome (link Contributing / email).
- Subscribe pointer (RSS).

---

## Author notes (not part of the article)

- **Exclusions:** no product names, no client names, no colleague names. No deep dive on any single dimension — that's what volumes are for. Mention ASSET-grade at most once (it's canonical on Terms, but the keystone should not read as a benchmark pitch).
- **Terms to link:** Engineering Trustworthy Industrial AI, Grounded Reasoning, Trustworthy Decision, "Who Signs?", The Governed Decision Layer, Terms page itself.
- **LinkedIn companion post:** compress to hook + the two words + the seven dimensions as a plain list + link. Frame as "a research program organized around seven dimensions," NOT "a 7-part series" — keeps sequencing freedom.
- **Housekeeping after publish:** Terms page says Governed Decision Layer was "first introduced in Volume I" — currently a dangling attribution since the volume is empty. Either let the keystone carry the first public introduction or update the attribution when the Volume I opener publishes.
