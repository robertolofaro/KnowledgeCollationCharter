# Guidelines for Designing and Sharing Open Knowledge Collation Projects

**A Charter for Evidence-Based, Democratized Research Dissemination**

*Version 1.0 — April 2026*

*Synthesized from: "The Making of Star Trek" (Whitfield & Roddenberry, 1968); John Rawls, "A Theory of Justice" (1971); the Anthropic Model Specification ("Claude Constitution"); and the NewsAgent Morning Brief project (R. Lofaro, 2025–2026)*

---

## Preamble: Why This Matters

Public discourse suffers not from a shortage of information, but from a deficit of *structured, evidence-grounded interpretation* available to people who are not specialists. Expert analysis exists in abundance — it is siloed behind paywalls, compressed into op-eds that hide their reasoning, or produced by institutions whose incentives are not fully disclosed.

The ambition of this charter is to describe how any organization — a civic group, a company, a community of practice, a single person — can design and operate a knowledge collation project that is:

- **Systematic**: following documented rules rather than editorial instinct
- **Evidence-anchored**: traceable to disclosed sources
- **Multi-perspectival**: structured to surface disagreement rather than hide it
- **Replicable**: described in enough detail that others can instantiate their own version
- **Fair**: designed so that the rules would be accepted by anyone, regardless of which side of the analysis they found themselves on

This document draws on three sources that may seem unrelated but turn out to be deeply compatible: John Rawls' theory of procedural justice, the production bible developed for *Star Trek*, and the epistemic principles embedded in Anthropic's guidelines for AI behavior. The NewsAgent project — a daily AI-assisted morning brief organized around an "editorial team" of named analyst personas — is offered throughout as a working example.

---

## Part I — Founding Principles (The Rawlsian Foundation)

### 1.1 The Original Position for Knowledge Design

Rawls asks us to imagine designing institutions from behind a *veil of ignorance* — not knowing our place in society, our class, our abilities, or our conception of the good. The rules we would choose in that position are the just ones, because they cannot have been tailored to advantage whoever is doing the choosing.

Applied to knowledge collation projects, the equivalent question is: **what rules would you accept for producing and sharing analysis if you did not know whether you would be the producer, the subject, or the reader of that analysis?**

A project whose methods pass this test:
- Would not select sources to confirm a conclusion its designers already hold
- Would apply the same scrutiny to evidence that challenges its default view as to evidence that confirms it
- Would present its methodology openly enough that subjects of the analysis could understand and challenge how they are being characterized
- Would make its outputs accessible to readers who lack the technical background to evaluate primary sources themselves

This is the first design question every project should answer: *Would we accept these rules if we did not know whose interests they would serve?*

### 1.2 Public Reason: Writing for the Audience You Owe

Rawls' concept of *public reason* holds that citizens in a democracy owe one another justifications in terms all can understand, not only in terms accessible to specialists or co-believers. The same obligation applies to knowledge dissemination.

**Operationally, this means:**

- Conclusions must be expressible in plain language, even when the underlying evidence is technical
- Where specialist terminology is unavoidable, it must be defined
- The reasoning chain — from evidence to interpretation to conclusion — must be made explicit, not compressed into an assertion
- A reader who disagrees with a conclusion must be able to identify *which step* they dispute: the source, the interpretation, or the inference

This does not require simplification to the point of distortion. It requires that the simplification choices be documented and that the full reasoning be available to those who want it.

### 1.3 The Difference Principle Applied to Information Access

Rawls holds that social and economic inequalities are only justified if they benefit the least advantaged members of society. Applied to knowledge: *design choices that create differential access to analysis are only justified if they result in better overall quality that eventually reaches those with least access.*

In practice, this principle argues for:
- Open licensing as the default; paywalls only when the revenue directly funds expanded access
- Multiple reading levels (executive summary, full brief, source appendix)
- Formats accessible on low-bandwidth or low-cost devices
- Proactive sharing in the channels where the least-served audiences actually are

The NewsAgent project posts its daily briefs freely on Patreon. That is not a marketing decision; it is an ethical one: the structured, multi-perspective analytical frame is more valuable to someone who does not have institutional access to expert briefings than to someone who does.

### 1.4 Reflective Equilibrium as Ongoing Governance

Rawls' method of *reflective equilibrium* — iterating between abstract principles and concrete judgments until they cohere — describes how these guidelines should be used. They are not a rigid rulebook. When a specific editorial decision feels wrong but technically complies with the rules, that tension is information: either the rule needs refinement or the intuition about the specific case needs examination.

Every project should document its significant editorial tensions and how they were resolved. Those records are more valuable for the next project than a list of rules that never required interpretation.

---

## Part II — The Editorial Architecture (The Star Trek Bible Approach)

The production bible for *Star Trek*, developed in 1967 before a single episode aired, was not a creative constraint — it was an enabling infrastructure. It defined the universe, the rules of its physics, the characters and their relationships, the tone, and the non-negotiables. Because writers knew all of that, they could work in parallel without producing contradictory outputs. The quality of individual episodes was not dependent on the creator being in the room.

A knowledge collation project needs the same architecture.

### 2.1 The Project Bible: What Must Be Defined Before You Begin

**2.1.1 Scope Declaration**

State explicitly:
- What topics and geographies are covered
- What time horizon is relevant (today's news, this week's analysis, long-run trends)
- What questions the project aims to answer — and what it does not
- What audience it is designed for

A scope that is not documented will expand by default until it becomes unmanageable.

**2.1.2 The Source Tier System**

Divide sources into mandatory and optional tiers, with explicit rationale for each tier boundary:

| Tier | Description | Handling |
|------|-------------|----------|
| Tier 1 — Mandatory | Primary sources and high-reliability institutional outputs that must be consulted regardless of relevance on any given cycle | Always checked; always cited if relevant |
| Tier 2 — Standard | Recognized secondary sources with documented editorial standards | Consulted when topic coverage requires; cited when used |
| Tier 3 — Contextual | Specialist publications, think-tank outputs, non-anglophone outlets | Used when topic demands; clearly labeled as Tier 3 |
| Tier 4 — Flagged | Sources with known reliability limitations or undisclosed funding; blogs, aggregators | Usable only with explicit flag; never for primary factual claims |

The NewsAgent project defines eleven mandatory sources spanning institutional (central banks, international organizations), Tier 1 press, and non-anglophone outlets. The mandatory layer exists precisely to prevent the editorial team — human or AI — from gravitating toward sources that confirm its existing framing.

**2.1.3 The Analyst Persona System**

Parallel, multi-perspective analysis requires defined roles. Rather than a single neutral voice (which merely hides the perspective it is written from), the project should define named analyst personas, each with:

- A distinct epistemic orientation or expertise domain
- A characteristic set of questions they bring to any topic
- A declared set of sources they weight most heavily
- A known set of blind spots they are expected to have

The personas must collectively cover the analytical space. They should not all be variations of the same perspective. The dissent between personas is where the analytical value lives.

**Example persona set (NewsAgent):** Six analysts covering geopolitical-economic, financial-market, technology-innovation, social-institutional, regulatory-legal, and long-run systemic perspectives. No two are configured to agree by default on cross-cutting topics.

**2.1.4 The Output Template**

Define the output format before the first cycle runs. The template should specify:
- Required sections (what must always appear)
- Optional sections (what appears when relevant)
- Word or token budget per section
- The distinction between factual summary, analysis, and editorial judgment — and how each is typographically or structurally marked
- How disagreements between analyst perspectives are surfaced rather than averaged

A template that is not defined in advance will be reinvented each cycle, accumulating inconsistencies that make longitudinal comparison impossible.

### 2.2 Parallel Contribution Within a Shared Frame

The Star Trek bible's power was that it enabled distributed creative work without loss of coherence. The same principle applies here:

- Any contributor (human or AI) who has read the project bible should be able to produce a compliant output without real-time supervision
- The bible must be specific enough to constrain but not so prescriptive as to eliminate judgment
- Contributor outputs should be evaluable against the bible by someone who was not present during production
- The bible itself is versioned: when it changes, the version history explains why

### 2.3 Versioning and Longitudinal Integrity

Each cycle's output should carry:
- A date and version identifier
- The bible version in effect during production
- A changelog if the template was updated since the previous cycle

This allows outputs from different cycles to be compared. It also allows the project to learn: a pattern of editorial decisions that repeatedly deviate from the template in the same direction is evidence that the template needs updating.

---

## Part III — Epistemic Standards (From the Claude Constitution)

The Claude Constitution establishes several epistemic principles for AI behavior that generalize cleanly to any knowledge dissemination project, regardless of whether AI is involved.

### 3.1 Calibrated Uncertainty

**The rule:** Represent confidence levels accurately. Do not state as certain what is uncertain. Do not hedge what is well-established to appear balanced.

**In practice:**
- Use explicit confidence markers: *confirmed*, *strongly suggested*, *plausibly*, *contested*, *speculative*
- When evidence is mixed or limited, say so and say how
- Distinguish between *no evidence for* (absence of evidence in consulted sources) and *evidence against* (evidence exists that contradicts the claim)
- Do not use the format of certainty (declarative sentences, absence of hedges) when the underlying evidence warrants uncertainty

Calibration failure in both directions is a problem. Overclaiming authority damages trust when errors emerge. Underclaiming (false balance) obscures genuine consensus and creates false equivalences.

### 3.2 Non-Manipulation

**The rule:** Influence readers only through legitimate epistemic means — evidence, demonstration, well-reasoned argument. Never through techniques that exploit psychological biases, create false urgency, or bypass deliberate evaluation.

**In practice:**
- Do not arrange evidence selectively to produce a predetermined conclusion while appearing balanced
- Do not use emotional language to compensate for weak evidence
- Do not use headlines or summaries that are technically accurate but structured to create impressions the underlying content does not support
- Do not embed editorial conclusions in the structure of a factual summary without marking them as such

This rule is not about neutrality. A project can have a perspective. The rule is about *how* that perspective is expressed: through argument, not manipulation.

### 3.3 Preserve Reader Autonomy

**The rule:** Prioritize approaches that help readers reason and evaluate evidence well, rather than simply providing conclusions for adoption.

**In practice:**
- Make the reasoning chain explicit, not just the conclusion
- Present the strongest version of alternative interpretations before dismissing them
- Flag where further reading would give a reader the tools to form their own judgment
- Resist the temptation to simplify in ways that remove the reader's ability to disagree

This is the most demanding standard. It is also the most important for a project that aims at democratization rather than just dissemination. The goal is not to tell readers what to think. It is to give them a better-structured set of materials to think with.

### 3.4 Transparency About Method and Attribution

**The rule:** Be honest about how outputs are produced, who contributed, and what limitations apply.

**In practice:**
- Disclose when AI is used in production, what model, and what role it played
- Attribute contributions at appropriate granularity: human designer, AI architecture translator, prior sessions, external reviewers
- Disclose funding sources and institutional affiliations
- Document known limitations: what topics the project's source set covers poorly, what languages are underrepresented, what analytical perspectives are absent from the current persona set
- Distinguish between limitations that are acknowledged and those that are unknown

The NewsAgent project explicitly attributes its framework to a human domain designer and AI architecture translation, with prior sessions credited where relevant. That transparency is not a disclaimer — it is part of the epistemic contract with the reader.

### 3.5 Distinguish Fact, Interpretation, and Opinion

Every output should make structurally legible the difference between:

- **Factual reporting**: what the sources say happened
- **Analysis**: what the sources, taken together, suggest about causes, patterns, or implications
- **Judgment**: the project's own evaluative position, where it has one

These three categories may appear in the same document. They should not appear in the same paragraph without signaling which is which.

---

## Part IV — Dissemination Ethics

### 4.1 Open by Default

Any project that invokes the Rawlsian principle of designing for the least-advantaged reader is ethically committed to open dissemination as the default. Exceptions require justification:

- Paywalls are justifiable only if the revenue directly funds the project's capacity to produce and share more widely
- Embargoes are justifiable for time-sensitive operational reasons, not as a commercial differentiation strategy
- Restricted access tiers are justifiable for interactive tools with significant infrastructure costs, provided that a read-only version remains free

### 4.2 Licensing

Outputs should be licensed under terms that permit:
- Non-commercial redistribution with attribution
- Adaptation and translation, with derivative works under equivalent terms
- Citation in commercial contexts, with attribution

Creative Commons CC BY-SA or CC BY-NC-SA are appropriate defaults for most projects. Projects that want commercial use permitted should use CC BY.

### 4.3 Accessibility and Format Pluralism

A single output format serves a single audience. Projects committed to democratization should produce at minimum:
- A full-length analytical brief (for engaged readers)
- An executive summary (for readers with limited time)
- A source list with links (for readers who want to go deeper)

Where resources allow: audio versions, translations, and simplified-language adaptations.

### 4.4 Community and Feedback Loops

A dissemination project that does not receive feedback cannot learn whether its calibration is accurate, whether its source set has systematic gaps, or whether its persona set is missing important perspectives.

Design feedback mechanisms that are:
- Specific enough to be actionable (not just ratings, but structured disagreement)
- Low-friction enough to be used by the audience the project is actually trying to reach
- Documented: feedback and the project's response to it should be part of the public record

---

## Part V — Template Instantiation: How to Start Your Own

A project that has read this charter and wants to instantiate its own version should work through the following questions before producing a single output.

### 5.1 The Minimum Viable Bible

Answer these questions in writing before the first cycle:

**Scope:**
1. What domain(s) does this project cover?
2. What time horizon is relevant?
3. What is the primary audience?
4. What is the project explicitly *not* covering?

**Sources:**
5. What are the mandatory Tier 1 sources? (List them. If you cannot name at least five, the source architecture is not ready.)
6. What are the criteria for promoting a source from Tier 2 to Tier 1, or demoting it?
7. What is the policy for sources in languages other than the project's primary language?

**Analyst personas:**
8. How many distinct analytical perspectives are represented?
9. What is each persona's primary domain, characteristic questions, and declared blind spots?
10. What topics would produce genuine disagreement between the personas? (If none come to mind, the personas are not sufficiently distinct.)

**Output template:**
11. What sections are always present?
12. How are factual reporting, analysis, and editorial judgment distinguished in the output?
13. What is the word/token budget for each section?

**Attribution and transparency:**
14. How is AI involvement disclosed, if any?
15. How is the project funded?
16. What are the known limitations of the current source and persona architecture?

### 5.2 The Ethical Checklist

Before publishing, ask:
- Would we accept these methods if we were the subject of this analysis?
- Could a reader who disagrees with our conclusion identify which step they dispute?
- Is the confidence level in the output accurately calibrated to the evidence we actually consulted?
- Are we disclosing everything a reader would want to know to evaluate this output?

### 5.3 Governance Questions for Multi-Contributor Projects

If more than one person or system contributes to the project:
- Who has authority to update the project bible, and what process governs that?
- How are editorial disagreements resolved?
- What happens when a contributor's output is assessed as non-compliant with the bible?
- How is the project bible itself reviewed for accuracy and continued fitness?

---

## Appendix: Source Acknowledgments and Intellectual Attribution

This charter was synthesized by Roberto Lofaro (domain designer and project originator) with Claude (architecture translation and synthesis), drawing on:

- **"The Making of Star Trek"** (Stephen Whitfield & Gene Roddenberry, 1968): the production bible concept, parallel contributor architecture, enabling constraint design
- **"A Theory of Justice"** (John Rawls, 1971): the original position, veil of ignorance, public reason, difference principle, reflective equilibrium
- **Anthropic Model Specification** ("Claude Constitution", 2024–2025): calibrated uncertainty, non-manipulation, autonomy preservation, transparency requirements
- **NewsAgent Morning Brief project** (R. Lofaro / Claude, 2025–2026): the working proof of concept for editorial team structure, source tier systems, and democratized dissemination

These sources are acknowledged not only for intellectual honesty but because understanding where a framework comes from is essential to knowing when and how to adapt it. The framework is offered freely under Creative Commons CC BY-SA 4.0. Derivative projects should maintain attribution and equivalent openness.

---

*"Justice is the first virtue of social institutions, as truth is of systems of thought."*
*— John Rawls, A Theory of Justice, §1*

*"The only limits are those of vision."*
*— Gene Roddenberry*
