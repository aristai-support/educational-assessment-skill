# Cheatsheet

## The spine — one test, applied everywhere

**If the artifact is generatable, the artifact carries no information about the learner.** Assess the process/trace instead. Ch 1, 2, 4, 10 and 11 reach this independently; every other recommendation is a special case of it.

1. Could a generator produce a passing version? → If yes, the artifact cannot be the evidence.
2. Where is the construct actually visible? → In the question sequence, the revisions, the handoff decisions, the justification of divergence, the live explanation. Grade that.

## Detection is rejected — say it plainly

Every chapter that addresses it rejects it (Ch 1, 2, 3, 4, 6, 9, 10). Not "use carefully" — do not build integrity policy on it.
- A detector outputs an opinion with no verifiable source; plagiarism detection produced adjudicable evidence, this does not.
- Detectors flag plain, correct prose — punishing beginning writers, non-native speakers, grammar-tool users. Obfuscation tooling means the race is permanently lost.
- **Never prosecute on a detector score alone.** Recognising machine prose opens a conversation, never a finding.

## Decision rules

| When… | Do | Because |
|---|---|---|
| A task invites outsourcing (rote, irrelevant, disengaging) | Redesign the task | The invitation is information about the task, not the student |
| You catch yourself writing an AI *policy* | Write an AI *design* instead | Merely permitting AI changes nothing about what you measure |
| A high-weight assessment has no live component | Add an oral defence | Highest-leverage single change; it cannot be delegated |
| A student couldn't defend it in five minutes | The assessment isn't measuring them | Live articulation is the load-bearing evidence |
| The construct is reflection, reasoning, creativity or judgment | Instrument the process, credit step by step | Output-only assessment structurally cannot reach these |
| A tool can't explain why it gave a score | Treat it as a signal to a human, never the decision | Black-box verdicts are unlearnable and unauditable |
| Errors are cheap and reversible (formative) | Let AI in; keep summative under human oversight | The student iterates; a final grade does not |
| A personalization rollout is planned | Fund targeted onboarding for low performers first | Adoption tracks prior achievement; the default widens the gap |
| AI is permitted at all | Name the independent steps, with worked examples | Ambiguity, not malice, drives most misuse |

## Where machine scoring is safe — Ch 9 vs Ch 11

**Ch 9 asserts AI assessment is accurate, objective and bias-reducing. Ch 11 empirically documents the same tools failing.** Ch 11 is better evidenced — it tested tools; Ch 9 surveys affordances. Do not average these into "AI can help with assessment."

| Zone | Machine-score? |
|---|---|
| Narrow, physically measurable constructs (pronunciation, fluency, mechanics), item-level feedback | Yes — deployed at scale (Ch 5) |
| High-volume low-judgment formative work, errors reversible | Yes, with human spot-check (Ch 3, 9) |
| Adaptive item difficulty from prior responses | Yes (Ch 3, 9) |
| Generating context-rich differentiated items, then human-reviewed | Yes — strongest positive case (Ch 11, 7) |
| Holistic essay / writing scores | No — bias persists on subjective tasks, no published accuracy evidence (Ch 3, 5) |
| Anything summative or high-stakes | No (Ch 2, 3, 7, 10) |
| Emotion / engagement monitoring | No — most sensitive data, weakest consent story (Ch 9) |

**Ch 11's documented failure modes — design against these, expect the edge to move:**
- **Visual/diagrammatic representation** (number lines, base-ten blocks, geometric figures) — it draws the representation, then ignores it and reverts to procedure.
- **Precise domain terminology** — a term outside its competence yields a plausible but wrong artifact.
- **Conceptual vs procedural explanation** — fluent in the rule, unreliable on why the rule holds.
- **Harder items** — success falls as difficulty and operation count rise.

**Bias is bidirectional** (Ch 9's durable contribution): automation removes rater subjectivity and installs training-data bias. Fairness is a claim to test, never a property conferred by a machine.

## Thresholds and defaults

- **~50–75%** of students will use AI even under prohibition. Design for that number, not for compliance.
- **Micro-assessments: under 3 minutes, ≤3 questions, ~20 per semester.** Correlation with summative outcome r ≈ 0.35 — an early-warning signal, not a prediction.
- **Novices gain most** (~34% vs ~14% average) — first-years are the most affected population, in both directions.
- **Adoption gap ~72% top quartile vs ~54% bottom quartile.** Assume it unless you controlled for it.
- **Human review of AI-generated items is mandatory** — every framework in the book routes machine output past a teacher before it counts.
- **First move into machine scoring: speech and mechanics before text.**
- Write measurable targets *before* selecting a tool, then select against them.

## Tells and smells

- **Marginal passes, not top grades, are the alarm.** Students who now scrape through learned nothing and will never be remediated.
- **Your feedback answers only "how am I going?"** → you are grading, not teaching.
- **You swapped "essay" for "video presentation" and changed nothing else** → the objectives were never examined.
- **The prompt is five years old** → that is exactly what LLMs answer best.
- **Your AI policy is a prohibition plus a citation rule** → it defines no authorship and will not change behaviour.
- **A well-built tool goes unused** → check which of autonomy, competence or relatedness it stripped, then whether students were ever taught to formulate follow-up questions (the top reported barrier at every performance level).
- **Someone proposes in-class timed handwritten essays** → less valid, reliable, inclusive and equitable than untimed work, and unavailable to online cohorts.
