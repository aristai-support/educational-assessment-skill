# Chapter 11: Mathematics Teaching and Assessment in the Age of Generative AI

## Core Idea
Generative AI reliably solves the computational items that dominate elementary
and middle-school assessment, so take-home computational work no longer measures
anything; the redesign is to shift both the *task type* (toward reasoning,
explanation, and multiple representations, where current models are weakest) and
the *modality* (toward in-class and verbal assessment). Grounded in a small
mixed-methods study of preservice teachers plus the instructor's own action
research.

## Frameworks Introduced

- **The Two-Axis Assessment Shift: Task Type and Modality**: the chapter's
  central recommendation — every redesign move falls on one of two axes.
  - When to use: responding to generative AI in any quantitative subject where
    the answer is checkable and the procedure is standard.
  - How: *Task type* — drop items whose answer AI supplies directly; require
    students to show and explain their work; require reasoning across multiple
    representations and the relationships among them; require transfer to a new
    context. *Modality* — move weight to in-class formative work and proctored
    in-class tests; add verbal assessment where the learner explains how they
    know they are right; for anything still taken home, run the item through the
    AI first and modify based on what it returns.

- **Assess Against the Model's Current Weak Edge**: design items that sit where
  the tool is documented to fail.
  - When to use: when you need AI-resistance now, with the explicit
    understanding that the edge moves as models improve.
  - How: the documented weak edges in this study are (a) visual and
    diagrammatic representation — number lines, base-ten blocks, geometric
    figures; (b) precise mathematical terminology, attributed to LLMs' bias
    toward linguistic over mathematical intelligence and the scarcity of complex
    mathematics in training data; (c) conceptual rather than procedural
    explanation; (d) increasing item difficulty, where success rate drops.
    Re-audit each cycle — the chapter is explicit that this edge is temporary.

- **Embedding AI Into the Task**: when a take-home task cannot be AI-proofed,
  make AI use the assignment.
  - When to use: take-home work where the target skill is something AI can
    scaffold but not perform for the student.
  - How: in this study, preservice teachers were required to use AI on their
    homework and then use it to *refine their own explanations* so those
    explanations would be clear to a young learner. The graded object becomes
    the refinement, not the solution.

- **Shallow Assessment Trap (NCTM position)**: rather than threatening
  instruction, these tools create positive pressure to build assignments that
  blend fundamentals with creative thinking.
  - When to use: as the framing argument when defending redesign to colleagues
    or administrators.
  - How: pair fundamentals (needed to judge whether an AI output is reasonable)
    with open, creative demands (which AI cannot supply for the learner).

- **AI Differentiation Across Content, Process, and Product**: the chapter's
  strongest *positive* use case for AI in mathematics.
  - When to use: producing rich, contextual assessment items at a volume manual
    authoring cannot sustain.
  - How: prompt for real-life-context word problems, then re-prompt with grade
    level, ability level, interests, and cultural relevance as constraints.
    Context-set items assess conceptual understanding far better than abstract
    items but are expensive to write by hand — this is exactly where the tool
    pays.

## Key Concepts
- **Procedural vs. conceptual explanation**: AI defaults to correct step
  sequences (the rule) while omitting the underlying meaning (why the rule
  holds); conceptual explanation is what precedes the rule in good instruction.
- **Multiple representations**: diagrams, graphs, number lines, manipulatives —
  and, critically, the *relationships among* them, which is where assessment
  should now aim.
- **Hallucination (NCTM usage)**: AI producing answers that are untrue or
  unreasonable, making learner intuition about reasonableness a required skill.
- **Sense making**: the fundamentals-plus-problem-solving base that lets a
  learner judge whether a generated output is plausible.
- **Prompt constraint refinement**: iteratively adding constraints (grade level,
  audience, representation type) until output is fit for purpose; the specificity
  of the prompt bounds the quality of the result.
- **Show-your-work effect**: model accuracy on word problems rises substantially
  when required to show working and falls sharply when not.
- **Difficulty gradient**: model success declines as item difficulty rises;
  reported failure probability on word problems increases with the number of
  addition and subtraction operations.
- **Action research**: the instructor's own method here — critically reflecting
  on one's own teaching practice through specific tested interventions.

## Mental Models
- Use **"run it through the model first"** as the default authoring step for any
  take-home item — the model's answer tells you exactly what the item now
  measures.
- Think of the AI as **fluent in procedure, weak in meaning**: it will hand you
  the algorithm reliably and the reason behind the algorithm unreliably, so the
  reason is where your assessment weight should sit.
- Treat **AI's weakness as temporary scaffolding, not architecture**: build the
  reasoning-and-representation shift because it is pedagogically right, and take
  the AI-resistance as a bonus that will erode.
- Think of **verbal, in-class explanation as the highest-integrity instrument
  available** — it is simultaneously the hardest to outsource and the most direct
  evidence of conceptual understanding.

## Worked Example
The instructor probed ChatGPT with tasks that require a *representation*, not
just an answer, and the failures were diagnostic.

Task one: round 3.546 to the nearest hundredth **using a number line**. The
model drew a number line, then delivered the standard digit-comparison rounding
procedure — look at the next digit, five or greater rounds up — never actually
using the number line it had drawn. The representation was decorative; the
explanation was purely procedural, skipping the conceptual grounding that in
good instruction *precedes* the rule.

Task two: compute 41 − 28 and explain it with a **base-ten blocks** diagram. The
step-by-step regrouping explanation was sound, but the generated visual was not
base-ten blocks, would have been incomprehensible to a young learner, and
appeared to depict addition rather than subtraction — plausibly because the
precise term "base ten blocks" sat outside the model's competence.

Task three, by contrast, worked: asked to explain to a middle schooler why
subtracting a negative equals adding, the model produced multiple accessible
routes including a real-life debt context, because the prompt named the grade
level. It still failed on the number line — telling the learner to *imagine* one
rather than supplying it. A parallel integer-multiplication task produced
patterns, algebraic reasoning, and intuition together, but the algebraic route
was pitched above middle school until the prompt was tightened.

The design conclusion the instructor drew: build assessment items that require
reasoning *with and across* representations. That is where the tool fails, and —
independently — where conceptual understanding actually lives.

## Key Takeaways
1. Stop assessing computation on take-home work in elementary and middle
   mathematics; AI does it accurately and the item measures nothing.
2. Shift task type toward problem-solving, explanation, reasoning across
   multiple representations, and transfer to new contexts.
3. Shift modality toward in-class formative work, proctored tests, and verbal
   assessment where the learner explains how they know their answer is right.
4. Test every remaining take-home item against the AI before assigning it, and
   modify based on the response.
5. When a take-home task cannot be protected, embed AI in it — grade the
   refinement of the student's own explanation rather than the solution.
6. Use AI for what it is genuinely good at here: generating context-rich,
   culturally relevant, ability-differentiated word problems at a volume manual
   authoring cannot match.
7. Because AI now handles the routine work, raise the ceiling — pose harder
   problems that let learners demonstrate deeper understanding.
8. Teachers see the potential but do not know how to integrate it; first-hand
   structured experience with the tool, including prompt construction and
   refinement, is the prerequisite for adoption.

## What Transfers vs. What Is Math-Specific
**Transfers to any quantitative subject** (statistics, physics, chemistry,
engineering, accounting): the two-axis shift; run-it-through-the-model item
authoring; the show-your-work effect; the difficulty gradient; embedding AI in
the task; using AI to mass-produce contextualized items; the observation that
online-administered exams inflate scores relative to in-person ones.

**Math-specific**: the particular weak edges — base-ten blocks, number lines,
geometric figures, and precise mathematical terminology — and the
procedural-versus-conceptual distinction as it plays out in elementary
arithmetic. The *category* of weakness (domain-specific representations and
technical vocabulary) generalizes; the specific instances do not.

## Connects To
- **Ch 10**: this is Ch 10's process-based-evaluation principle instantiated in
  one subject — "show and explain your work" is "assess the trace, not the
  artifact," and the representation-reasoning focus targets exactly Ch 10's
  situated application level where AI is weakest.
- **Ch 9**: supplies the empirical counterweight to Ch 9's confident claims
  about AI assessment accuracy and objectivity; here the same tools are
  documented failing on visuals, terminology, and harder items.
