# Part 2 — Generative AI & Agentic AI
### A 3-Day Course for Manufacturing Engineers & Business Professionals

> **Who this is for:** The same audience as Part 1 — non-technical manufacturing and business professionals. You should have completed **Part 1 (Foundations of AI)** first, or at least be comfortable with the idea that "AI learns patterns from data."
>
> **Promise of Part 2:** By the end of these three days you'll use ChatGPT/Copilot confidently and safely, write prompts that get great results, understand what "AI agents" and "agentic AI" really mean, know the difference between Generative AI and AGI — and you'll have applied all of it to real manufacturing tasks.

---

## Recap: Where We Are in the Journey

| Part | Theme | Status |
|------|-------|--------|
| Part 1 | Foundations of AI | ✅ Done — you can explain AI and train a simple model |
| **Part 2 (this one)** | **Generative AI & Agentic AI** | 👈 You are here |
| Part 3 | Industry Application & Business Value | Coming next |

In Part 1, AI **recognized** (defects) and **predicted** (failures). In Part 2, AI **creates** (writes, draws, summarizes) and **acts** (takes steps on your behalf). Same foundation — a huge leap in what it can do.

**Same daily rhythm as Part 1:** Warm-up → Core Concepts → Manufacturing Spotlight → Hands-On Workshop → Homework (with free/paid tools) → Takeaways → Quiz.

---

# DAY 1 — "Meet Generative AI" (The Technology Behind ChatGPT & Copilot)

### ☕ Warm-up (15 min)
Ask a free AI assistant: *"Write a 4-line safety reminder for forklift operators in a busy warehouse."* In two seconds, it produces something usable that **never existed before**. It didn't copy-paste from a database — it *generated* it. That's the difference, and it changes everything about knowledge work.

### 📘 Core Concepts

#### 1. What is Generative AI?
**Generative AI** = AI that **creates new content** — text, images, audio, code, video — rather than just classifying or predicting.

> **Factory analogy:** Part 1's AI was a *quality inspector* (judges existing parts). Generative AI is a *tireless apprentice writer/designer* who drafts documents, summarizes reports, and sketches ideas — fast, but needs your review.

#### 2. What's an "LLM" and why does everyone say it?
- **LLM = Large Language Model.** It's the engine inside ChatGPT, Microsoft Copilot, Google Gemini, and Claude.
- It was trained on enormous amounts of text and learned the patterns of human language so well that it can **predict the next word** over and over to build coherent paragraphs.

> **Mind-blowing but true:** At its core, an LLM is doing fancy "predict the next word." Strung together billions of times, that simple trick produces essays, code, and answers. *It's pattern prediction (Part 1!) — supercharged.*

#### 3. The single most important caution: "Hallucinations"
- LLMs sometimes state **wrong information with total confidence** — a made-up statistic, a fake citation, a wrong spec.
- This is called a **hallucination.** It happens because the AI predicts *plausible-sounding* text, not *verified* truth.

> **Golden rule:** **Treat Gen AI like a brilliant, fast intern who is sometimes confidently wrong.** Always verify facts, numbers, and anything safety- or compliance-related. *You* are responsible for the output.

#### 4. The tools you'll actually use (and which to pick)

| Tool | Free tier | Paid tier | Best for | Data safety note |
|------|-----------|-----------|----------|------------------|
| **Microsoft Copilot** | ✅ Yes | Copilot Pro / Microsoft 365 Copilot (~$20–30/user/mo) | Office users; works inside Word, Excel, Outlook, Teams | **With a work (M365) account, your data is protected and not used to train public models** — best for company use |
| **ChatGPT (OpenAI)** | ✅ Yes (GPT-class model) | Plus (~$20/mo) | General drafting, brainstorming, broadest ecosystem | Free version: avoid pasting confidential data |
| **Google Gemini** | ✅ Yes | Advanced (~$20/mo) | Google Workspace users | Same caution on confidential data in free tier |
| **Anthropic Claude** | ✅ Yes | Pro (~$20/mo) | Long documents, careful reasoning | Same caution |

> 💡 **Recommendation for manufacturing/business pros:** If your company uses Microsoft 365, **Microsoft Copilot with your work account** is the safest starting point — your prompts and company data are protected. For personal practice, any free tier is fine **as long as you never paste confidential or safety-critical information.**

#### 5. Free vs. Paid — when is it worth paying?
- **Free tiers are genuinely powerful** and enough to learn everything in this course.
- **Pay when:** you need it integrated into Office apps, want the latest/most capable models, need higher usage limits, or require enterprise data protection and admin controls.
- **Don't pay until** you've found a repeatable task that saves real time. (Crawl before you run — Part 1's lesson applies to spending, too.)

### 🏭 Manufacturing Spotlight: Gen AI for the "Paperwork Tax"
Manufacturing runs on documents — and Gen AI is a paperwork machine:
- **Shift handover reports** — turn bullet points into a clean, complete report.
- **Standard Operating Procedures (SOPs)** — draft first versions in minutes, then refine.
- **Incident & root-cause write-ups** — structure messy notes into a 5-Why or 8D format.
- **Training material** — generate quizzes, checklists, and onboarding guides.
- **Email & communication** — draft customer updates, supplier requests, internal memos.

**Value:** Engineers and supervisors spend **20–40% of their time on documentation.** Cutting that in half gives skilled people their time back for actual engineering.

### 🛠️ Hands-On Workshop: "Your First Power Prompts" (60 min)
**Tool: any free AI assistant (Microsoft Copilot recommended). No setup beyond a free login.**

Work through these five real tasks. Type each prompt, read the result, then improve it:

1. **Summarize:** Paste a long (non-confidential) paragraph and ask: *"Summarize this in 3 bullet points for a busy plant manager."*
2. **Draft:** *"Write a shift handover note. Day shift completed 1,200 units, Line 2 had a 30-min jam at 2pm now resolved, low on packaging film. Keep it under 100 words."*
3. **Transform:** *"Turn these rough notes into a professional 5-Why analysis: [paste 4–5 messy bullet points]."*
4. **Explain:** *"Explain what OEE means to a new operator, with a simple example."*
5. **Brainstorm:** *"Give me 10 ideas to reduce changeover time on a packaging line."*

**Debrief:** Which results were instantly usable? Which needed fixing? **Where did it possibly hallucinate?** (Check any number or fact it produced.)

### 🏠 Homework (Day 1)
**Goal:** Build the habit of using Gen AI for daily tasks — and verifying it.

- **Task A:** Use a free AI assistant to draft **one real document** from your job (handover, email, checklist). Edit it to be accurate. Time how long it took vs. doing it from scratch.
- **Task B:** Deliberately try to **catch a hallucination.** Ask it for "3 statistics about manufacturing productivity" and then check whether those numbers are real. Write down what you find.
- **Tools:**

| Tool | Free? | Notes |
|------|-------|-------|
| **Microsoft Copilot (work account)** | ✅ Free tier | Safest for anything work-related |
| **ChatGPT / Gemini / Claude** | ✅ Free tiers | Fine for practice with non-confidential content |

> ⚠️ **Safety homework:** Never paste customer data, employee data, proprietary designs, or anything under NDA into a free/public AI tool. When in doubt, leave it out.

### ✅ Key Takeaways (Day 1)
1. **Generative AI creates** new content (text, images, more); it's pattern prediction supercharged.
2. **LLMs** power ChatGPT/Copilot/Gemini/Claude by predicting the next word — extremely well.
3. **Hallucinations are real** — treat Gen AI as a fast intern who's sometimes confidently wrong; **always verify.**
4. **Free tiers are enough to learn.** Pay only when integrated, repeatable value is proven.
5. **Use a work account (e.g., M365 Copilot) for company data** and never paste confidential info into public tools.

### ❓ Quick Quiz (Day 1)
1. What's it called when AI confidently states something false? *(A hallucination)*
2. What does LLM stand for? *(Large Language Model)*
3. True/False: Free AI tiers are too weak to be useful for learning. *(False)*

---

# DAY 2 — "Becoming a Gen AI Power User" (Prompts, Images, and Your Own Knowledge)

### ☕ Warm-up (15 min)
Yesterday you talked to AI. Today you learn to talk to it *well.* The difference between a vague prompt and a great one is the difference between a frustrated intern and a star performer. **Prompting is a skill — and it's learnable in an afternoon.**

### 📘 Core Concepts

#### 1. The anatomy of a great prompt — the "RTCF" recipe
Great prompts have four parts. Remember **R-T-C-F**:

| Part | Meaning | Example |
|------|---------|---------|
| **R — Role** | Tell it who to be | "You are a senior quality engineer..." |
| **T — Task** | Say exactly what you want | "...write a defect report..." |
| **C — Context** | Give the details | "...for a stamped bracket with edge cracks found on Line 4..." |
| **F — Format** | Specify the output shape | "...as a table with cause, evidence, and corrective action." |

> **Weak prompt:** "Write a defect report." → generic.
> **Strong prompt (RTCF):** "You are a senior quality engineer. Write a defect report for a stamped bracket with edge cracks found on Line 4 today. Format it as a table with columns: cause, evidence, corrective action." → **specific, usable.**

#### 2. Five techniques that instantly improve results
1. **Give examples** ("Here's a good report I wrote before; match this style: ...").
2. **Ask it to think step by step** ("Walk through the root cause step by step before concluding").
3. **Iterate** — your first prompt is a draft. Say "make it shorter," "more formal," "add a safety section."
4. **Ask for options** ("Give me 3 versions: formal, friendly, and ultra-brief").
5. **Tell it what NOT to do** ("Don't invent any numbers; if you don't know, say so" — this reduces hallucinations!).

#### 3. Beyond text: Generative AI for images and more
- **Image generation** (e.g., Microsoft Designer/Copilot, DALL·E, Adobe Firefly) — create diagrams, training visuals, concept sketches, poster graphics.
- **In manufacturing:** signage and safety posters, training illustrations, concept mockups, marketing visuals for the sales team.
- **Caution:** Don't use AI images to fake real parts or data; use them for *communication and concepts*, not as engineering drawings.

#### 4. The game-changer: making AI use YOUR documents (RAG, explained simply)
Out of the box, an LLM doesn't know *your* SOPs, *your* machine manuals, or *your* policies. Two ways to fix that:

- **The simple way (do this first):** **Paste or upload** the relevant document into the chat and ask questions about it. ("Here's our maintenance manual — what's the torque spec for the gearbox bolts?") *Most paid tools and Copilot let you upload files.*
- **The advanced way — RAG (Retrieval-Augmented Generation):** A system that connects the AI to your company's document library so it can **look up the right document automatically** and answer with citations. You don't build this yourself — IT or a vendor sets it up. **Microsoft 365 Copilot does this with your company's files, emails, and Teams data automatically.**

> **Plain-English RAG:** Give the AI an "open-book exam" using *your* manuals, so its answers are grounded in your real documents instead of its general training. **This dramatically reduces hallucinations.**

#### 5. Custom assistants ("GPTs" / "Agents-lite")
- Tools now let you build a **custom assistant** with fixed instructions and your documents — no coding. ("You are our SOP helper. Only answer using these 12 uploaded procedures.")
- Examples: ChatGPT's "GPTs," Microsoft Copilot Studio "agents," Gemini "Gems."
- **Manufacturing example:** A "Maintenance Buddy" assistant loaded with your equipment manuals that any technician can ask, in plain language, day or night.

### 🏭 Manufacturing Spotlight: Gen AI Across the Plant
- **Maintenance:** "What does fault code E-207 on the CNC mean, and what are the first 3 checks?" — answered from the uploaded manual in seconds.
- **Quality:** Auto-draft 8D reports; summarize a week of inspection logs into trends.
- **Training:** Generate role-specific onboarding guides and quizzes from your SOPs.
- **Procurement/Supply chain:** Draft RFQs, summarize supplier emails, compare quotes.
- **Engineering:** Brainstorm DOE factors, summarize research, draft work instructions.
- **Frontline language access:** Translate safety notices and instructions for a multilingual workforce.

**Value:** Faster troubleshooting (less downtime), consistent documentation, knowledge captured from retiring experts, and inclusion for non-native-language workers.

### 🛠️ Hands-On Workshop: Build a "Maintenance Buddy" (75 min)
**Tool: Microsoft Copilot or ChatGPT (free tier works for the upload-and-ask version; "custom GPT" creation may need a paid tier — both paths below).**

**Path A — Upload & Ask (free, everyone does this):**
1. Find a **non-confidential** manual or SOP (or use a sample appliance manual from the web).
2. Upload/paste it into the assistant.
3. Ask 5 real questions a technician would ask. Note how grounded the answers are vs. yesterday's generic answers.
4. Apply **RTCF**: "You are a maintenance expert. Using only the manual above, list the step-by-step procedure to reset the unit. If it's not in the manual, say 'not specified.'"

**Path B — Create a Custom Assistant (optional, if you have a paid tier or Copilot Studio):**
1. Create a new custom GPT/agent.
2. Set instructions: *"You are 'Maintenance Buddy.' Answer only from the uploaded manuals. Always cite the section. Never guess specs."*
3. Upload 2–3 manuals. Test it. Share it with a colleague.

**Debrief:** Did "answer only from the document" reduce made-up answers? *(Yes — that's RAG thinking in action.)*

### 🏠 Homework (Day 2)
**Goal:** Master prompting and grounding.

- **Task A (Prompting):** Take yesterday's document task and redo it using the full **RTCF** recipe. Compare quality.
- **Task B (Grounding):** Upload a real (non-confidential) manual or policy and build a 10-question Q&A for your team. Note which answers were grounded vs. shaky.
- **Task C (Image):** Generate one safety poster or training graphic with a free image tool.
- **Tools:**

| Tool | Free? | Paid? | Use for |
|------|-------|-------|---------|
| **Microsoft Copilot** | ✅ Free | M365 Copilot for company-doc grounding | Text + grounding in your files |
| **ChatGPT** | ✅ Free | Plus for custom GPTs & file upload limits | Prompting, custom assistants |
| **Microsoft Designer / Copilot image** | ✅ Free | — | Safety posters, training visuals |
| **Adobe Firefly** | ✅ Free credits | Subscription for more | Commercial-safe images |

> 💡 **Spend check:** You can do 90% of Day 2 on free tiers. The main reason to upgrade is **file-upload limits** and **building shareable custom assistants** for your team.

### ✅ Key Takeaways (Day 2)
1. Great prompts use **RTCF: Role, Task, Context, Format.**
2. **Iterate** — the first answer is a draft; refine it.
3. **Ground the AI in your documents** (upload/paste, or RAG) to slash hallucinations.
4. **No-code custom assistants** turn AI into a "Maintenance Buddy" or "SOP Helper."
5. Gen AI does **images too** — great for training, safety, and communication.

### ❓ Quick Quiz (Day 2)
1. What do the letters RTCF stand for? *(Role, Task, Context, Format)*
2. What's the simplest way to make AI answer from your own manual? *(Upload/paste it and ask)*
3. What does RAG help reduce? *(Hallucinations — by grounding answers in real documents)*

---

# DAY 3 — "Agentic AI & The Road to AGI" (When AI Starts to *Act*)

### ☕ Warm-up (15 min)
So far, AI has answered when you ask. Now imagine telling it: *"Check yesterday's downtime log, find the top recurring fault, draft an email to the maintenance lead, and schedule a review meeting."* — and it does **all of it**, step by step, using tools. That's **agentic AI**, and it's the frontier of 2025–2026.

### 📘 Core Concepts

#### 1. From "assistant" to "agent" — what changes?
- **A chatbot/assistant** *responds.* You ask, it answers. One turn at a time.
- **An AI agent** *acts.* You give it a **goal**, and it figures out the steps, **uses tools** (email, search, databases, apps), checks its own progress, and keeps going until the goal is met — with you supervising.

> **Factory analogy:** An assistant is a **reference librarian** (answers your question). An agent is a **junior project coordinator** (you give an outcome, they run the errands, make the calls, and report back).

#### 2. The four parts of an AI agent (no jargon)
1. **🧠 The brain (LLM):** reasons and plans.
2. **🎯 A goal:** what you want achieved.
3. **🛠️ Tools:** things it can *use* — search the web, read a file, send an email, query a system, run a calculation.
4. **🔁 A loop:** Plan → act → observe the result → adjust → repeat until done.

#### 3. Start simple → go advanced (the agentic ladder)
You don't jump to autonomous agents. Climb the ladder:

| Rung | What it is | Example | Risk |
|------|-----------|---------|------|
| **1. Single-task assistant** | Answers/drafts on request | "Draft this report" | Very low |
| **2. Assistant + your data** | Grounded in your docs | "Answer from our SOPs" | Low |
| **3. Tool-using assistant** | Can take ONE action with approval | "Find this and put it in a draft email" | Low–medium |
| **4. Multi-step agent (supervised)** | Plans & executes several steps, you approve key actions | "Analyze downtime, draft summary, propose meeting times" | Medium |
| **5. Autonomous agent** | Runs a whole workflow with minimal oversight | "Monitor inventory and auto-reorder within limits" | Higher — needs guardrails |

> **Best practice:** Stay on rungs 1–4 for most business use. **Keep a human approving consequential actions** (anything that spends money, contacts customers, or touches production/safety).

#### 4. "Human-in-the-loop" is the safety belt
- Agents should **ask permission** before doing anything irreversible or costly.
- Set **guardrails:** spending limits, approval steps, "read-only" vs. "can-act" boundaries.
- **Log everything** the agent does so you can audit it.

> The goal isn't "AI runs the plant alone." It's "AI handles the busywork chain, humans approve the decisions that matter."

#### 5. Where do you actually get agents? (real tools, mid-2026)
- **Microsoft Copilot Studio** — build no-code/low-code agents grounded in your M365 data and connected to business systems.
- **ChatGPT / Gemini / Claude with tools** — consumer agents that can browse, run tasks, and use connected apps.
- **Vendor & platform agents** — many manufacturing software vendors (MES, ERP, maintenance platforms) now embed agentic features.

> **Crawl/Walk/Run still applies:** start with a supervised, single-workflow agent on a low-risk task before trusting anything autonomous.

#### 6. Generative AI vs. AGI — clearing up the confusion
- **Generative AI (today):** Creates content and, as agents, can act on goals — but it's still **narrow**. It has no true understanding, consciousness, or general common sense. It's a very capable tool.
- **AGI (Artificial General Intelligence):** A hypothetical future AI that matches or exceeds humans at **virtually any** intellectual task, learns anything, and transfers knowledge across domains. **It does not exist today.** Experts disagree on whether/when it arrives.
- **Why you should care (calmly):** The capable, *narrow* AI you can use **today** already delivers huge value. Don't wait for AGI; don't fear sci-fi. Focus on practical wins now, and stay informed.

> **Balanced take:** Treat AGI as a long-term "watch this space" topic. Treat **today's Gen AI and agents** as practical tools to deploy this quarter — with humans in charge.

### 🏭 Manufacturing Spotlight: Agentic AI Use Cases (Start Simple → Go Deep)

**Simple (rungs 1–3):**
- "Summarize this week's quality logs and email me the top 3 issues."
- "Search our manuals for fault code E-207 and draft the repair steps."

**Intermediate (rung 4, supervised):**
- **Downtime triage agent:** reads downtime data, identifies top recurring fault, drafts a corrective-action note, and proposes a review meeting — *you approve before anything sends.*
- **Supplier follow-up agent:** drafts and queues reminder emails for late POs, flags exceptions for your sign-off.

**Advanced (rung 5, with strong guardrails):**
- **Inventory replenishment agent:** monitors stock, auto-creates reorder drafts within preset limits, escalates anything unusual to a human.
- **Maintenance scheduling agent:** watches sensor predictions (Part 1!) and proposes optimized maintenance windows around the production schedule.

**Value:** Compresses multi-step "swivel-chair" work (jumping between systems) into minutes, reduces errors, and lets your experts focus on judgment, not data shuffling.

### 🛠️ Hands-On Workshop: "Design Your First Agent" + Mini-Build (75 min)

**Part A — Paper design (everyone, 30 min):**
Pick one real multi-step task from your job. Fill out the **Agent Blueprint:**

| Field | Your answer |
|-------|-------------|
| **Goal** | What outcome should the agent achieve? |
| **Steps** | List the 3–6 steps a human does today |
| **Tools needed** | Email? File search? A system query? Calendar? |
| **Approval points** | Where MUST a human say "yes" before it proceeds? |
| **Guardrails** | Limits, "never do X," read-only zones |
| **Success metric** | How do we know it worked? |

**Part B — Mini-build (choose your level, 45 min):**
- **Free / everyone:** Simulate the agent by **chaining prompts** in a normal chat: ask the AI to (1) analyze pasted data, (2) draft the email, (3) propose meeting times — one after another. You're playing the "loop" manually. *This teaches exactly how agents think.*
- **If you have Copilot Studio / a paid agent tool:** Build a **simple supervised agent** that does one real chain (e.g., search docs → draft summary) with an approval step.

**Debrief:** Where were you nervous about letting it act alone? *(That's your human-in-the-loop instinct — keep it.)*

### 🏠 Homework (Day 3) — Bridge to Part 3
**Goal:** Consolidate Gen AI + agentic skills and prepare for the business-value deep dive.

- **Task A:** Complete one **Agent Blueprint** for a real workflow in your area. Identify the approval points and guardrails. Bring it to Part 3.
- **Task B:** Write a half-page: *"Three Gen-AI or agent ideas for my team, ranked by value and risk."* (You'll turn these into business cases in Part 3.)
- **Task C (Reflection):** In your own words, explain the difference between **Generative AI (today)** and **AGI (future)** to a skeptical colleague.
- **Tools recap:**

| Tool | Free? | Paid? | Use for |
|------|-------|-------|---------|
| **Microsoft Copilot** | ✅ Free | M365 Copilot for grounded, in-app agents | Daily Gen AI + agent features |
| **Copilot Studio** | Trial available | Subscription | Building no-code business agents |
| **ChatGPT / Gemini / Claude** | ✅ Free tiers | ~$20/mo for tools & agents | Prompting, simulated agent chains |

> 💡 **Spend check for Part 2 overall:** You can complete **all learning** on free tiers. Paid tiers matter when you want (a) AI inside Office apps, (b) grounding in *company* data with enterprise protection, or (c) shareable, tool-using agents for your team.

### ✅ Key Takeaways (Day 3)
1. **Assistants respond; agents act** — given a goal, they plan, use tools, and loop until done.
2. Climb the **agentic ladder** (rungs 1–5); stay supervised for anything consequential.
3. **Human-in-the-loop + guardrails** are non-negotiable, especially near money, customers, or production.
4. **Today's Gen AI/agents are powerful but narrow.** **AGI is hypothetical and doesn't exist yet** — act on today's tools.
5. Real agent platforms exist now (e.g., **Copilot Studio**) — start small, supervised, low-risk.

### ❓ Quick Quiz (Day 3)
1. What's the key difference between an assistant and an agent? *(An agent acts toward a goal using tools and a loop; an assistant just responds)*
2. On which agentic rungs should a human approve consequential actions? *(All of them for consequential actions — especially rungs 4–5)*
3. Does AGI exist today? *(No — it's hypothetical; today's AI is powerful but narrow)*

---

## 🎓 Part 2 Wrap-Up

**You're now a Generative & Agentic AI practitioner.** You can:
- ✅ Use ChatGPT/Copilot safely and effectively
- ✅ Write strong prompts with RTCF and reduce hallucinations
- ✅ Ground AI in your own documents (upload & RAG)
- ✅ Build a no-code custom assistant
- ✅ Explain and design AI agents with proper guardrails
- ✅ Clearly distinguish today's narrow Gen AI from hypothetical AGI

### Your bridge to Part 3
In **Part 3 — Industry Application & Business Value**, we leave the tools behind and put on the **business hat**: mapping AI across the entire manufacturing value chain, building ROI cases finance will approve, managing risk and change, and creating *your* 90-day AI roadmap — finishing with a capstone project you can pitch to leadership.

### 📚 Glossary (Part 2)
- **Generative AI** — AI that creates new content.
- **LLM (Large Language Model)** — the engine behind chat AIs; predicts text.
- **Hallucination** — confident but false AI output; always verify.
- **Prompt** — your instruction to the AI; use **RTCF** (Role, Task, Context, Format).
- **RAG (Retrieval-Augmented Generation)** — grounding AI in your documents ("open-book exam").
- **Custom assistant / GPT / Gem / agent** — a no-code AI configured with your instructions and data.
- **AI Agent** — AI that pursues a goal by planning, using tools, and looping.
- **Human-in-the-loop** — a person approves key actions.
- **Guardrails** — limits that keep an agent safe.
- **AGI** — hypothetical general-purpose AI; does not exist today.

*End of Part 2.*
