# Chapter 5: AI-adaptive Chinese Language Learning Environment and Assessments in Hong Kong

## Core Idea
A corpus study of 358 Hong Kong Chinese-language newspaper articles (2018–2024)
showing that AI-adaptive *learning* has arrived in Chinese language education while
AI-adaptive *assessment* has barely started — only 1.9% of the discourse touched
assessing Chinese ability at all. **This chapter is a discourse/media analysis, not
an assessment-design chapter.** It contributes evidence about stakeholder readiness
and a catalog of deployed tools; it introduces no named assessment framework. Read
it for the readiness diagnostic and the language-specific constraints, not for a
method. (Note: it contains no "Prompt Engineering competency" framework — that
belongs elsewhere in the volume.)

## Frameworks Introduced
- **Problem-oriented Critical Discourse Analysis, sociocognitive approach (van Dijk)**: treat public discourse as evidence of how stakeholders *define the situation*, not as a report of the situation itself.
  - When to use: gauging institutional and public readiness for an assessment change before you design for it — who is talking, about what, and what they are silent about.
  - How: (1) build a bounded corpus from named sources over a defined window; (2) code articles into topic categories; (3) recruit independent raters to verify your categorization; (4) read the *proportions* as a readiness signal; (5) treat under-discussed categories as the gap.
- **Six-category coding scheme for AI-in-language-education discourse**: general language education / enhancing L1 literacy / L2 English / Putonghua / heritage-and-minority learners / assessing language ability.
  - When to use: as a reusable audit grid for any language program — ask which of these six your institution has actually invested in.
  - How: count coverage per category; the last category (assessment) is almost always the starved one.
- **Normalization of technological innovation (Lee)**: an innovation is adopted only when student expectations, teacher expectations, and institutional pedagogical beliefs converge.
  - When to use: diagnosing why an adopted AI tool is not actually being used.
  - How: measure student learning habits/expectations against stated institutional targets; where they mismatch, the fix is instructional strategy plus training for *both* groups — not more technology.

## Key Concepts
- **AI-adaptive learning environment**: a system that adjusts content, pace, and difficulty from learner performance data rather than delivering a fixed sequence.
- **Trilingualism and biliteracy**: Hong Kong's language policy — spoken Cantonese, Putonghua, English; written Standard Chinese and English — which makes "the language being assessed" a non-trivial question.
- **Diglossic gap (Cantonese vs. Standard Written Chinese)**: Cantonese-speaking students must be *taught* literacy in a written code that is not their spoken language, so writing assessment is partly a second-code assessment.
- **Computer-assisted language learning (CALL)**: the pre-generative body of research and practice that AI-adaptive learning inherits — including its findings on training and normalization.
- **Normalization process**: the social process by which an innovation stops being an innovation and becomes ordinary practice.
- **DSE Chinese**: the Hong Kong public examination whose criteria (content, expression, structure, word use) commercial AI graders now encode — the point where AI touches high-stakes assessment.
- **Pronunciation-accuracy scoring**: AI comparing a learner recording against a generated reference to score accuracy and flag specific items — the one assessment function actually deployed at scale here.
- **Predictive language screening**: using biometric data (EEG) plus a trained algorithm to forecast language-development risk before it is behaviorally observable.

## Mental Models
- Use *discourse coverage* as a readiness proxy when you have no adoption data: what stakeholders argue about is what they are prepared to fund; what nobody mentions is where the gap is.
- Think of the six-category grid as a **starvation detector** — learning tools attract 98% of the attention, assessment 2%, in every language program you will audit.
- Use **speech before text** when introducing AI assessment to a non-English language: pronunciation and fluency scoring is objective, immediately actionable, and culturally uncontroversial; essay scoring is none of those.
- Think of policy guidelines as *preliminary until they define authorship* — "acknowledge AI like a citation" is a placeholder, not a policy.

## Anti-patterns
- **Assuming English-language AI findings transfer to a non-alphabetic language**: Chinese requires word segmentation before any analysis; tools had to solve sentence-splitting and character/word distinction first. Assessment tooling for a language is only as good as its parsing layer.
- **Treating "Chinese" as one construct**: DSE Chinese, IB Chinese, GCSE Chinese, PSC, and HSK measure different things for different populations. An AI grader trained on one is not valid for another.
- **Deploying AI tools without training both teachers and students**: the CALL literature shows the innovation fails at the expectations mismatch, not at the technology.
- **Writing an AI policy that is only a prohibition plus a citation rule**: stakeholders in this corpus could not articulate what counted as legitimate use, so the policy did no work.
- **Reading media enthusiasm as evidence of learning gains**: the corpus documents claims made by vendors and journalists, not measured outcomes. The chapter's own evidence base is discourse, not achievement data.

## Worked Example
The chapter's most transferable case is **AI pronunciation assessment in a live competition** — a public Putonghua recitation contest scored by AI rather than by judges alone.

The loop: a candidate reads a prescribed passage supplied through the app → the system captures the recording → an acoustic model scores pronunciation accuracy against the reference → the learner receives real-time feedback naming the specific syllables mispronounced → aggregated data across all participants surfaces the difficulty patterns common to the cohort → those patterns feed back into what gets taught.

The same loop appears in the classroom tools the corpus documents: a system pulls fresh authentic audio daily (radio and government news), generates a reference reading, has the learner record the same text, scores it, and names improvable items. Two design properties make this work where essay scoring does not: the construct is narrow and physically measurable, and the feedback is item-level rather than holistic. Contrast with the essay-grading tool in the same corpus, which auto-scores against exam criteria and generates a model essay — higher stakes, weaker validity claim, and no published evidence of accuracy.

**What is context-bound**: the Cantonese/Putonghua/Standard-Written-Chinese configuration, the DSE criteria, and the ethnic-minority second-language provision are specific to Hong Kong. **What generalizes**: the starvation pattern (learning tools ≫ assessment tools), the speech-before-text sequencing, and the normalization requirement.

## Key Takeaways
1. Audit your own program with the six-category grid; expect to find assessment starved relative to learning tools, and treat that as the actionable gap.
2. Start AI assessment where the construct is narrow and measurable — pronunciation, fluency, mechanics — before attempting holistic writing scores.
3. Give item-level feedback, not holistic scores: the deployed tools that learners valued named the specific word that was wrong.
4. For any non-English language, verify the parsing layer (segmentation, morphology, script) before evaluating the assessment layer.
5. Budget for training teachers *and* students, and check the expectation match; normalization fails on mismatch, not on tooling.
6. An institutional AI policy that cannot say what legitimate use looks like will not change behavior — define authorship, not just prohibition.
7. Treat vendor and press claims about AI learning gains as hypotheses; this chapter documents the claims, and notes the outcome research does not yet exist.

## Connects To
- **Ch 6**: shares the "detection is not the answer" and "assessment must be redesigned" conclusion, but Ch 6 supplies the redesign methods this chapter only calls for.
- **Ch 7**: the adaptive-learning-path tools cataloged here (Duolingo, adaptive difficulty) are the same class of system Ch 7 theorizes as inquiry-supporting.
- **Ch 8**: the normalization/expectations-mismatch problem here is the qualitative counterpart to Ch 8's finding that higher-performing students self-select into AI tool use.
