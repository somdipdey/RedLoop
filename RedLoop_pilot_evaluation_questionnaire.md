# RedLoop — Pilot Evaluation Questionnaire (n = 15)

**Purpose.** Measure how well RedLoop achieved its goal — teaching AI red teaming, safety and
security to people who design and develop LLM-based AI systems — using mostly quantitative,
paper-defensible instruments, with a short qualitative section.

**Design note.** Pair this self-report survey with the **objective** knowledge gain you already
capture from RedLoop's built-in 8-item **Knowledge Check** (pre vs post). Together they give an
objective measure (test scores) and perceptual measures (self-efficacy, usability, motivation,
intention). The self-efficacy block uses a **retrospective pre/post** design ("rate your
confidence *before* and *after* using RedLoop") because, with a small sample, it controls for
response-shift bias and yields clean paired comparisons.

**Scale legend (unless stated otherwise):** 5-point Likert — **1 = Strongly disagree,
2 = Disagree, 3 = Neither agree nor disagree, 4 = Agree, 5 = Strongly agree.** Confidence items:
**1 = Not at all confident … 5 = Extremely confident.** Two items use their own scales (marked).

**Ethics.** Participation is voluntary and anonymous; responses are used only in aggregate.
Because RedLoop runs offline, no learner work or personal data left participants' machines.

---

## Section A — Background (covariates)

A1. Current role: ☐ Data scientist ☐ ML/AI engineer ☐ Software engineer ☐ Researcher
☐ Product/technical lead ☐ Other: ______

A2. Years of professional experience in AI/ML or software: ☐ <1 ☐ 1–3 ☐ 4–7 ☐ 8+

A3. Experience building **LLM-based** systems: ☐ None ☐ Some ☐ Experienced

A4. Prior experience with **AI red teaming / security testing**: ☐ None ☐ Some ☐ Extensive

A5. Prior familiarity with the **A4SRAI** framework: ☐ Never heard of it ☐ Heard of it
☐ Familiar ☐ Have used it

A6. How much of RedLoop did you complete? ☐ <25% ☐ 25–50% ☐ 51–75% ☐ 76–99% ☐ 100%
(which modules you finished, if not all): ______

---

## Section B — Self-efficacy / competence (retrospective pre/post) — **primary measure**

For each capability, give **two** ratings on the 1–5 confidence scale: your confidence
**BEFORE** using RedLoop and **AFTER** using RedLoop.

| # | Capability | Confidence BEFORE (1–5) | Confidence AFTER (1–5) |
|---|-----------|:---:|:---:|
| B1 | Explain what AI red teaming is and **why it matters** for LLM systems | | |
| B2 | Describe the **A4SRAI** framework and its four components | | |
| B3 | Explain **where red teaming fits across the Agile lifecycle** (continuous, not a final gate) | | |
| B4 | Recognise common LLM attacks (prompt injection, jailbreak, data poisoning, model inversion, membership inference, bias exploitation, misuse, adversarial examples) | | |
| B5 | Choose an appropriate **control/mitigation** for a given attack | | |
| B6 | **Threat-model** an LLM system I am building | | |
| B7 | Build and maintain a **risk register** and read a **risk matrix** | | |
| B8 | Identify **coverage blind spots** across RAI principles and lifecycle stages | | |
| B9 | Map red-teaming work to **standards** (EU AI Act, NIST AI RMF, ISO/IEC 42001) | | |
| B10 | **Apply** red teaming to my own real project | | |

---

## Section C — Perceived learning outcomes (1–5 agreement)

C1. RedLoop improved my understanding of **what AI red teaming is and why it matters**.
C2. RedLoop improved my understanding of **LLM safety and security risks**.
C3. RedLoop helped me understand how to **embed red teaming across the whole lifecycle** (A4SRAI).
C4. The **Safe Sandbox** before/after demos helped me understand how attacks work and how controls stop them.
C5. The **built-in scenarios** (HireFast, MediBot, NeoBank Assistant, CityWatch) helped me see how to apply the concepts to realistic systems.
C6. I am now more confident I could **threat-model an LLM system I build**.
C7. I can **map red-teaming work to standards** (EU AI Act / NIST / ISO) better than before.
C8. Overall, RedLoop **achieved its goal** of teaching me AI red teaming, safety and security.

---

## Section D — Usability: System Usability Scale (SUS, 1–5) — **standard validated instrument**

Answer 1 (Strongly disagree) to 5 (Strongly agree). *(Items alternate positive/negative by design — please read each carefully.)*

D1. I think I would like to use RedLoop frequently.
D2. I found RedLoop unnecessarily complex.
D3. I thought RedLoop was easy to use.
D4. I think I would need the support of a technical person to use RedLoop.
D5. I found the various functions in RedLoop were well integrated.
D6. I thought there was too much inconsistency in RedLoop.
D7. I would imagine most people would learn to use RedLoop very quickly.
D8. I found RedLoop very cumbersome to use.
D9. I felt very confident using RedLoop.
D10. I needed to learn a lot before I could get going with RedLoop.

---

## Section E — Cognitive load & clarity (1–5 agreement, except E4)

E1. Information in RedLoop was presented in a **clear, easy-to-follow** way.
E2. The topics were complex, but RedLoop **helped me make sense of them**.
E3. The amount of information shown at each step was **manageable** (not overwhelming) — the expandable explanations and tooltips gave detail only when I wanted it.
E4. Overall mental effort you invested in learning with RedLoop: **1 = very, very low … 9 = very, very high** (Paas single-item effort): ______

---

## Section F — Motivation & engagement (Self-Determination-Theory aligned, 1–5 agreement)

F1. I found working through RedLoop **engaging / enjoyable**. *(interest)*
F2. I felt I could **learn at my own pace and in my own way**. *(autonomy)*
F3. After using RedLoop, I feel **more competent** in AI red teaming. *(competence)*
F4. The scenarios felt **relevant to the kind of work I do**. *(relevance)*
F5. Using RedLoop was a **good use of my time**. *(value)*
F6. I am **interested in learning more** about AI red teaming after this. *(continued motivation)*

---

## Section G — Self-directed learning fit (andragogy) (1–5 agreement)

G1. I could **progress through RedLoop without needing an instructor or facilitator**.
G2. The built-in instructions and explanations were **enough for me to learn independently**.
G3. The **expandable explanations and hover tooltips** gave the right level of detail when I needed it.
G4. The **progress tracker and pre/post assessment** helped me monitor my own learning.

---

## Section H — Behavioural intention & adoption (1–5 agreement, except H5)

H1. I intend to **apply red teaming** in my future AI/LLM projects.
H2. I intend to **adopt the A4SRAI approach** (red teaming across the lifecycle) in my work.
H3. I would **use RedLoop again** as a reference.
H4. I would **recommend RedLoop** to a colleague building AI systems.
H5. **Net Promoter:** How likely are you to recommend RedLoop to a colleague building AI systems?
**0 = Not at all likely … 10 = Extremely likely:** ______

---

## Section I — Module-level usefulness (rate each 1–5, or N/A if not used)

Rate how **useful for your learning** each module was: **1 = Not useful … 5 = Extremely useful.**

| Module | Rating (1–5 / N/A) |
|--------|:---:|
| I1. Learn A4SRAI (interactive lifecycle walk) | |
| I2. Attack Library (techniques + controls) | |
| I3. Safe Sandbox (before/after demos) | |
| I4. Threat-Modelling Wizard (scenarios / own system) | |
| I5. Risk Register (matrix + scoring) | |
| I6. Lifecycle Board (deployment gate) | |
| I7. Coverage & Standards (blind spots + mapping) | |
| I8. Knowledge Check (pre/post + certificate) | |
| I9. Report & Export | |
| I10. Home / onboarding & guidance | |

I11. Which **one** module was **most** useful? ______
I12. Which **one** module was **least** useful (or needs most improvement)? ______

---

## Section J — Overall (1–5)

J1. Overall **satisfaction** with RedLoop.
J2. Overall, how **effective** was RedLoop as a learning tool for AI red teaming, safety and security?

---

## Section K — Open-ended (qualitative — keep brief)

K1. What did you **learn** that you didn't know before?
K2. Which feature helped you **most**, and **why**?
K3. How will you **apply** what you learned to your **own work**?
K4. Which attack or control do you now feel **confident** about that you didn't before?
K5. What was **confusing**, or what would you **improve**?
K6. What is **missing** that you'd want added?
K7. Any other comments?

---

## Appendix — Scoring & analysis guidance (for the paper's Section VI / Table IV)

**Objective knowledge gain (from RedLoop's built-in Knowledge Check, not this survey).**
Report pre/post % correct (8 items). Use **Wilcoxon signed-rank** (paired, non-parametric — apt
for n = 15); report medians (IQR) and means (SD), effect size **r = Z/√N**, and Hake's
**normalised gain ⟨g⟩ = (post − pre)/(100 − pre)** overall and per item.

**Section B (self-efficacy retrospective pre/post).** Same treatment per capability: Wilcoxon
signed-rank, medians/means, effect size, and per-item ⟨g⟩ on the 1–5 scale
(⟨g⟩ = (after − before)/(5 − before)). This is your headline evidence that RedLoop met its
purpose. Compute **Cronbach's α** for the 10-item scale to report internal consistency (treat as
indicative at this n).

**Section C, F, G, H (multi-item Likert constructs).** Report mean/SD per item and per construct;
Cronbach's α per construct (perceived outcomes, motivation, self-directed fit, intention).
Correlate (Spearman) usage/completeness (A6) with gains, and SUS with intention (H1–H4).

**Section D (SUS).** Score 0–100: for odd items score = (response − 1); for even items score =
(5 − response); sum the 10 and multiply by 2.5. Report mean/SD; benchmark (~68 = average,
> 80.3 ≈ "excellent"/A) and the adjective rating. Optionally split into Usability (8 items) and
Learnability (items 4 & 10) sub-scores.

**Section E (cognitive load).** Report E1–E3 means; report E4 (Paas mental-effort, 1–9) mean/SD.
Interpret alongside performance (high learning + manageable effort supports the load-sensitive
design).

**Section H5 (NPS).** NPS = %promoters (9–10) − %detractors (0–6).

**Section I (module usefulness).** Report mean usefulness per module and the most/least-useful
tallies — this is your per-feature evidence for the design-rationale claims.

**Section K (qualitative).** Thematic analysis (Braun & Clarke): code responses, report themes
with frequencies and short illustrative quotes; use them to triangulate the quantitative results.

**Threats to validity to acknowledge.** Small single-cohort sample; self-report and
social-desirability bias (mitigated partly by the objective Knowledge Check and retrospective
design); novelty effect; short knowledge test; no control group in this pilot.

**Construct → instrument → paper mapping (Table IV seed).** Knowledge → built-in 8-item test
(objective, pre/post); Self-efficacy → Section B (retrospective pre/post); Perceived learning →
Section C; Usability → SUS (Section D); Cognitive load → Section E (Leppink/Paas-style);
Motivation → Section F (SDT/IMI-aligned); Andragogy fit → Section G; Adoption/intention →
Section H (TAM/UTAUT-aligned) + NPS; Feature value → Section I; Global → Section J; Qualitative →
Section K.
