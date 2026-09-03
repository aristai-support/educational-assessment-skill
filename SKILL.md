---
name: educational-assessment
description: "Knowledge base from \"Educational Assessments in the Age of Generative AI\" (eds. Wachira, Liu & Koc, IGI Global 2025). Use when designing or redesigning assessments that generative AI can defeat, assessing higher-order and critical skills, writing AI-use policy for a course or institution, building process-based or authentic assessment, judging where AI scoring is safe, or reasoning about academic integrity without detection tools."
---

<!-- argument-hint: [topic, framework name, or chapter number] -->

# Educational Assessments in the Age of Generative AI
**Editors**: Patrick W. Wachira, Xiongyi Liu, Selma Koc (Cleveland State University) · **Publisher**: IGI Global, 2025
**Pages**: 423 · **Chapters**: 11 (different author teams) · **Generated**: 2026-09-02

## How to Use This Skill

- **Without arguments** — load the core frameworks below
- **With a topic** — ask about `rubric design`, `academic integrity`, `formative assessment`, `AI detection`; I read the relevant chapter
- **With a chapter** — ask for `ch10`; I load that file
- **Browse** — ask "what chapters do you have?"

---

## The Spine — read this first

One claim carries the whole book, and five chapters reach it independently from different directions:

> **If the artifact is generatable, the artifact carries no information about the learner.**

Therefore: **assess the process, not the product.** Ch10 supplies the construct theory, Ch1 instantiates it in writing pedagogy, Ch4 gives the operational generator, Ch11 instantiates it in mathematics, Ch2 supplies the institutional policy layer. Nearly every other recommendation in the book is a special case of this move.

**Corollary the book states unanimously: AI detection is not a strategy.** Every chapter that addresses detection rejects it — as unreliable, as adversarial to the student relationship, and as solving the wrong problem. Redesign the task instead.

---

## Core Frameworks & Mental Models

### Process-Based Evaluation (Ch10 — the governing framework)
Higher-order constructs (reflection, reasoning, creativity, judgment) are visible in the *steps*, not the artifact — so output-only assessment structurally cannot measure them.
- **When**: any time the claimed construct could have been produced by a generator.
- **How**: instrument the task so each step is visible; credit competence step by step, attach a corrective at each step where it is absent.

### The Bloom's Question–Feedback–Reflection Loop (Ch10 — the most transferable concrete design)
Converts a chatbot from an answer vendor into a cognitive scaffold.
1. Inside a genuine, situated problem, the learner authors a **laddered set of questions** deliberately spanning Bloom's six levels.
2. The learner **critiques** the AI's answers for incompleteness, bias, and unstated assumptions traceable to training data.
3. From that critique, the learner writes **follow-up questions**, again mapped to cognitive levels.
4. Loop 1–3, then finalize.

**The graded object is the loop, not the exit** — question coverage and ascent, critique quality, and how follow-ups respond to identified weaknesses.

### Balanced AI Integration × AI Literacy "4 A's" (Ch4 — the assignment generator)
The book's most directly reusable artifact: a 4×4 grid, not a taxonomy.
- **Balanced AI Integration**: Clear Guidelines · Process Over Product · Encouraging Critical Thinking · Feedback and Reflection
- **AI Literacy (Cardon et al.)**: Application · Authenticity · Accountability · Agency

Cross them to generate or audit an assignment: every cell is a design question the task should answer.

### AI-enabled vs AI-powered (Ch4 — the crispest one-line test)
**AI-enabled** = the human drives, AI assists a step. **AI-powered** = AI drives, the human accepts. Ask which one your task actually rewards. Most integrity failures are tasks that claim the first and grade the second.

### Assess Against the Model's Current Weak Edge (Ch11)
- **Use the *application* level as your AI-resistant zone** (Ch10): AI is weakest where the problem is local, situated, and criterion-bound.
- **"Run it through the model first"** (Ch11): before assigning, paste your own task into the model. If it produces a passing answer, you have written a prompt, not an assessment.
- **Caution**: the weak edge *moves*. Treat "uniquely human" as an empirical boundary to re-audit each cycle, never a slogan.

### The Two-Axis Assessment Shift (Ch11)
Redesign along **Task Type** (computation → reasoning, justification, multiple representations) and **Modality** (written artifact → oral defence, live work, process log). Generalizes cleanly beyond mathematics.

### Centaur / Cyborg collaboration + The Five "Can'ts" (Ch6)
Partition the work explicitly between human and machine strengths rather than banning or ceding. The Five "Can'ts" name what the model still cannot do — use them as task-design anchors, subject to the moving-boundary caution above.

### Feed Up / Feed Back / Feed Forward (Ch8 — Hattie & Timperley)
The most reusable instrument in the volume: an audit grid that works on *any* feedback, human or machine.
- **Feed Up**: where is the learner going? **Feed Back**: how are they going? **Feed Forward**: what next?
- **When**: auditing any feedback mechanism, especially AI-generated feedback, which reliably over-serves Feed Back and under-serves Feed Forward.

### Skill Deconstruction via Backward Design (Ch6)
Ask **"what skill was this artifact ever a proxy for?"** — then assess that skill directly. This is the operative move for every assignment redesign, and the reason "the essay is dead" is a claim about *proxies*, not about writing.

### Authentic & Incremental Assessment (Ch2)
Authentic assessment as the governing design principle; incremental/iterative submission so the trace exists to be graded. Ch2 also carries the **assessment-type × Bloom's matrix** — the densest single table in the book — and the institutional **policy stack**.

---

## ⚠ A contradiction between sources — do not average it away

**Ch9 claims AI assessment is accurate, objective, and bias-reducing. Ch11 empirically documents the same tools failing** on visual representations, precise domain terminology, conceptual (as opposed to procedural) explanation, and harder items.

**Ch11 is the better-evidenced chapter and should be treated as the corrective.**

**Separately, Ch8 overstates its own results.** Its conclusion claims the study "demonstrates the effectiveness of AI tutors", but **every reported t-test was non-significant** (exam question types p = 0.064–0.955; quizzes p = 0.373). Its two findings that *do* hold: a formative→summative correlation (r = 0.352, p < .01), and an adoption **selection bias** — 72.4% uptake in the top quartile vs 53.6% in the bottom, meaning an AI tutor deployed without targeted onboarding **widens** the achievement gap. Cite Ch8 for those two, not for tutor effectiveness. Machine scoring is safest on procedural, text-based, well-specified tasks; it degrades exactly where the higher-order constructs this book cares about actually live. See `cheatsheet.md` for the decision rule.

---

## Chapter Index

| # | Title | Key Frameworks |
|---|-------|----------------|
| [ch01](chapters/ch01-process-based-writing-assessment.md) | Process-Based Assessment in the Writing Classroom | Process over product; Cognitive Process Theory of Writing; Critiquing-AI-Output assignment |
| [ch02](chapters/ch02-false-sense-of-achievement.md) | The False Sense of Achievement | Authentic assessment; assessment-type × Bloom's matrix; incremental assessment; policy stack |
| [ch03](chapters/ch03-assessment-transformation-africa.md) | Transforming Educational Assessment in Africa | Formative/summative deployment boundary; twelve-challenge audit; equity mitigations |
| [ch04](chapters/ch04-ai-powered-prompts-writing.md) | AI-Powered Prompts for First-Year Writing | Balanced AI Integration; AI Literacy 4 A's; **AI-enabled vs AI-powered**; Chain-of-Thought as pedagogy |
| [ch05](chapters/ch05-ai-adaptive-language-learning.md) | AI-Adaptive Chinese Language Learning (Hong Kong) | *Discourse study, not assessment design* — six-category coverage audit; Lee's normalization process |
| [ch06](chapters/ch06-essay-is-dead.md) | The Essay Is Dead *(most tool-dense chapter)* | **Skill deconstruction / backward design**; Five "Can'ts"; Centaur/Cyborg; Bloom's Digital Taxonomy; Aiken's & Haladyna's MCQ taxonomies |
| [ch07](chapters/ch07-inquiry-based-learning.md) | Inquiry-Based Learning Through AI-Enabled Assessment | AI-augmented inquiry loop; four-part fairness protocol; accessibility-by-design; Fairness/Transparency/Accountability |
| [ch08](chapters/ch08-ai-enhanced-formative-assessment.md) | AI-Enhanced Formative Assessment | **Feed Up / Feed Back / Feed Forward**; formative→summative correlation; adoption selection bias |
| [ch09](chapters/ch09-management-education-assessment.md) | Assessment in Management Education | Five AI assessment affordances; six technology-enabler properties; five usage strategies |
| [ch10](chapters/ch10-higher-order-critical-skills.md) | **Assessing Higher-Order and Critical Skills** | **Process-Based Evaluation**; Four Higher-Order Skill Domains; **Bloom's Q–F–R Loop**; four method types |
| [ch11](chapters/ch11-mathematics-teaching-assessment.md) | Mathematics Teaching and Assessment | **Two-Axis Shift**; assess against the weak edge; embedding AI in the task; shallow-assessment trap |

## Topic Index

- **academic integrity** → ch02, ch03, ch06
- **AI detection (rejected)** → ch01, ch02, ch04, ch06
- **authentic assessment** → ch02, ch07
- **Bloom's taxonomy** → ch02, ch06, ch10
- **critical thinking / higher-order skills** → ch10, ch06, ch11
- **equity & access** → ch03, ch07
- **feedback loops** → ch07, ch08, ch10
- **formative vs summative** → ch03, ch08
- **machine scoring reliability** → ch09, ch11 *(contradictory — see above)*
- **mathematics** → ch11
- **oral defence / viva** → ch02, ch11
- **policy & governance** → ch02, ch03
- **process over product** → ch01, ch04, ch10, ch11
- **prompt engineering as assessable skill** → ch04, ch10
- **rubric design** → ch01, ch02, ch11
- **writing pedagogy** → ch01, ch04, ch06

## Supporting Files

- [glossary.md](glossary.md) — all key terms with chapter references
- [patterns.md](patterns.md) — executable techniques
- [cheatsheet.md](cheatsheet.md) — decision rules, including where machine scoring is safe

---

## Scope & Limits

- Covers this book only. It is an **edited volume**: chapters are by different author teams, vary in rigour, and occasionally disagree — the Ch9/Ch11 conflict above is the significant one.
- **Ch3, Ch5 and Ch9 are context-bound** (African higher education, Hong Kong Chinese-language teaching, management education). Extract the mechanics, check the transfer.
- **Ch9 and Ch5 are the thinnest.** Ch9 is an affordance survey with no study, rubric, or worked redesign. Ch5 is a corpus/discourse study of 358 newspaper articles — cite it as readiness evidence, not method.
- **Route practitioners to Ch6 and Ch8 first**; Ch7 is a sound design checklist whose evidence base is vendor case studies.
- Empirical claims about model capability are **2025-vintage** and were already moving when written. The book's own advice applies to itself: re-audit the weak edge each cycle.
- Content is **synthesized** — frameworks, principles and techniques restated, not the book's text. Local reference only; not redistributable.
