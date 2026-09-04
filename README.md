# educational-assessment

An agent skill for **redesigning assessments that generative AI can defeat**.

It turns the frameworks in *Educational Assessments in the Age of Generative AI* (eds. Patrick W. Wachira, Xiongyi Liu & Selma Koc; IGI Global, 2025 — 423pp, 11 chapters) into something a coding agent can apply to a real course, a real assignment sheet, or a real institutional policy.

It is **not** a book summary. It contains no reproduced text from the source. Every framework, decision rule and technique has been restated, cross-checked against the other chapters, and — where the book contradicts itself — adjudicated rather than averaged.

---

## What it's for

You have an assignment, a rubric, or a policy that quietly stopped working when students got access to a good model. This skill helps you answer:

- **Is this assignment still measuring anything?** (There is a five-second test.)
- **What do I replace it with** that permits AI rather than fighting it?
- **Where can I let a machine grade,** and where is that actively unsafe?
- **What does an AI-use policy have to say** to change behaviour rather than just express a preference?
- **Is my feedback teaching, or just scoring?**

## The one idea it's built on

Five chapters, by five independent author teams, converge on this from five directions:

> **If the artifact is generatable, the artifact carries no information about the learner.**

So: assess the **process**, not the product. Nearly every other recommendation in the book is a special case of that move.

The corollary the volume states unanimously — **AI detection is not a strategy.** Not "use it carefully": every chapter that addresses detection rejects it. A detector produces an opinion with no adjudicable evidence, it flags plain correct prose (punishing beginning writers and non-native speakers), and obfuscation tooling means the race is permanently lost. Redesign the task instead.

---

## What's inside

| File | What it is | Size |
|---|---|---|
| `SKILL.md` | Loads first. The spine, ~10 core frameworks, the source contradictions, chapter + topic indexes. | ~1,600 words |
| `cheatsheet.md` | **The highest-value file.** 9 decision rules, a machine-scoring safety table, thresholds, and "tells and smells". | ~970 words |
| `patterns.md` | 19 executable techniques, each with *when to use / how / trade-offs*. | ~1,500 words |
| `glossary.md` | 53 terms with chapter references. | ~1,080 words |
| `chapters/ch01–ch11` | One file per chapter: frameworks, key concepts, mental models, anti-patterns, a worked example, takeaways. Loaded on demand. | ~15,400 words |

**Progressive disclosure**: only `SKILL.md` enters context up front. Chapter files are read when a question actually needs them, so the full ~22k words never load at once.

## A sample of what it actually gives you

**A decision rule** (from `cheatsheet.md`):

| When… | Do | Because |
|---|---|---|
| You catch yourself writing an AI *policy* | Write an AI *design* instead | Merely permitting AI changes nothing about what you measure |
| A high-weight assessment has no live component | Add an oral defence | Highest-leverage single change; it cannot be delegated |
| A student couldn't defend it in five minutes | The assessment isn't measuring them | Live articulation is the load-bearing evidence |
| A personalization rollout is planned | Fund targeted onboarding for low performers first | Adoption tracks prior achievement; the default widens the gap |

**A pattern** (from `patterns.md`):

> **Annotate-the-AI-Draft** — *when the essay is now forgeable and your subject expertise is the scarce resource.*
> Instruct students to generate the essay, paste it in, then use tracked changes to insert quotations and data from this week's readings that support or challenge each claim. **Grade the annotation layer**: evidence selection, claim mapping, detection of the model's characteristic failures.
> *Trade-off*: drafting fundamentals go unassessed — pair with a competency check.

**A diagnostic** (from `SKILL.md`):

> **AI-enabled vs AI-powered.** AI-enabled = the human drives, AI assists a step. AI-powered = AI drives, the human accepts. Ask which one your task actually *rewards*. Most integrity failures are tasks that claim the first and grade the second.

---

## Where it disagrees with its own source

An edited volume of eleven independent teams does not speak with one voice. Averaging the disagreements away would make the skill confidently wrong, so they are surfaced instead.

**1. Ch9 vs Ch11 — can machines grade?**
Ch9 asserts AI assessment is accurate, objective and bias-reducing, on a citation chain. **Ch11 puts the same tools under adversarial test and documents them failing**: it draws a number line then ignores it and reverts to procedure; a "base-ten blocks" visual that wasn't, showing the wrong operation. Ch11 is better evidenced — it tested tools, Ch9 surveys affordances. The skill carries a safe/unsafe zone table and Ch11's four documented failure modes.

**2. Ch8 overstates its own results.**
The volume's only controlled study (n=128, 16 weeks) concludes its AI tutor was effective. **Every reported t-test was non-significant** (p = 0.064–0.955). Its usable residue is better than its claim: formative quizzes correlated r = 0.352 with finals, and adoption tracked prior attainment (72.4% top quartile vs 53.6% bottom) — the tool didn't work *and* was taken up least by the students it was meant to help.

**3. Modality contradiction.**
Ch6 lists reverting to in-class timed assessment as an anti-pattern; Ch2 and Ch11 recommend exactly that shift. Neither states its scope condition.

## Limits, stated plainly

- **One book only.** Chapters 3, 5, 7 and 9 yielded no directly executable technique between them; Ch5 is a corpus study of 358 newspaper articles, not assessment design. Route to Ch6, Ch8, Ch10 and Ch11 first.
- **2025-vintage empirical claims.** Nearly every concrete recommendation bets on a *current model weakness* whose half-life is measured in releases. Only Ch11 says so outright. The book's own advice applies to itself: re-audit the weak edge each cycle.
- **The unexamined assumption.** The volume treats interaction logs, tracked changes and revision histories as trustworthy evidence, and **nowhere argues they are unforgeable** — while the entire process-over-product thesis rests on exactly that. Keep it in mind when deploying the portfolio and interaction-log patterns.

---

## Install

```bash
npx skills add https://github.com/aristai-support/educational-assessment-skill --skill educational-assessment
```

Or clone directly into your agent's skill root:

```bash
# Claude Code
git clone https://github.com/aristai-support/educational-assessment-skill ~/.claude/skills/educational-assessment

# Codex / Cursor / Amp and other cross-agent hosts
git clone https://github.com/aristai-support/educational-assessment-skill ~/.agents/skills/educational-assessment
```

`SKILL.md` sits at the repository root, which is exactly the layout the `skills` CLI detects — no restructuring needed. Restart your agent session afterwards so it picks the skill up.

## Usage

```
"Redesign this final essay — students are all using AI now"
"Is this rubric still measuring anything?"
"We need a course AI policy"
"Where can I safely let a machine grade?"
"load ch10"     # construct theory for higher-order skills
"load ch11"     # mathematics + the documented AI failure modes
```
