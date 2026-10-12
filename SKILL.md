---
name: fair-research
metadata:
  version: "0.1"
  status: "experimental"
description: Explore a question, discover credible alternative positions, compare evidence fairly, and make the path from question to conclusion inspectable. Use for article research, problem analysis, opinion formation, or other evidence-sensitive reasoning where the initial position should not receive unjustified methodological privilege.
---

# Fair Research Skill v0.1

## Purpose

Use this skill to investigate a question without treating the user's initial intuition as the thesis to prove.

The goal is not to eliminate bias, discretion, or uncertainty. The goal is to reduce their hidden influence and make the decisions that can change the conclusion visible, explainable, and open to challenge.

This is not a universal scientific protocol. It is a practical research and reasoning framework for article preparation, problem analysis, and opinion formation.

## Relationship with other skills

This skill governs **research fairness and evidence comparison**.

When used in the Medium writing project:

- **Fair Research** governs question definition, alternative discovery, evidence comparison, robustness testing, and transparency of methodological choices.
- **Medium Editorial** governs article posture, argument, research depth, structure, adversarial editorial critique, fact-checking, titles, publication preparation, and performance learning.
- **Francesco Voice** governs wording, tone, rhythm, expression, and authorial style.

Do not modify or override the Francesco Voice skill.

Do not let this skill turn every article into a research paper. Apply only as much rigor as the question requires.

## Core principle

Do not give the position formulated first methodological privileges that have not been justified.

A fair process does not require giving every claim equal weight. It requires giving every credible claim a fair opportunity to earn weight.

Transparency is necessary for scrutiny, not sufficient for correctness.

## Process

### 1. Define the question

Clarify what is actually being investigated before collecting evidence.

When relevant, specify:

- population or subject;
- context or domain;
- conditions;
- time period;
- key terms;
- outcome being evaluated;
- level of generality.

Flag questions that are so broad that different sources may be answering different questions while appearing to disagree.

### 2. Define the rules before the positions

Before deeply evaluating competing positions, decide how alternatives and evaluation criteria will be identified.

Prefer criteria supported by one or more of the following:

- established practices in the relevant field;
- recurring dimensions in prior research;
- methodological standards appropriate to the question;
- features that logically follow from the object being investigated.

Do not choose criteria because they favor a preferred conclusion.

When no authoritative standard exists, state that the criteria are provisional and explain why they were chosen.

### 3. Record the initial position

If the user already has an intuition or preliminary view, record it explicitly only after the basic question and rules have been defined.

Treat it as a possible source of bias, not as the center of the investigation.

If no clear position exists yet, do not force one.

### 4. Discover alternatives iteratively

Search deliberately across different channels when appropriate, including:

- established journals or institutions;
- original research;
- reviews and syntheses;
- repositories and preprints;
- independent researchers or technical analyses;
- other credible sources outside the dominant publication channel.

Use AI primarily as a discovery aid, not as the final arbiter of credibility.

Do not ask only for evidence against the initial position. Search for distinct interpretations, explanations, or claims that deserve to be represented on their own terms.

After each discovery pass, ask what credible position is still missing.

Stop when additional searches produce mostly variants of already represented positions rather than materially new alternatives. Treat this as a pragmatic stopping rule, not proof of completeness.

### 5. Apply a minimal admission filter

An alternative deserves deeper evaluation when it is:

- sufficiently relevant to the defined question;
- precise enough to understand what it claims;
- supported by a reasoning chain that can be reconstructed without inventing substantial missing steps;
- sufficiently inspectable that evidence could strengthen, weaken, qualify, or challenge it.

Do not require prestige, popularity, institutional affiliation, or majority status for admission.

Do not reconstruct an argument so aggressively that the researcher effectively invents the position being evaluated.

### 6. Check whether the alternatives really compete

Before comparing positions, test whether they are actually incompatible or genuinely competing explanations.

Do not force a binary contest when:

- both positions can be true at the same time;
- they apply to different conditions;
- one is a narrower version of the other;
- one explains a different stage or dimension of the phenomenon.

If apparently competing positions are compatible, reformulate the comparison.

### 7. Break positions into specific claims

Evaluate evidence relative to claims, not to sources or broad labels.

A source can strongly support a narrow claim while weakly supporting a broader generalization.

When necessary, decompose a position into multiple claims before evaluation.

### 8. Search symmetrically for evidence

Use comparable search standards across the credible alternatives.

For each important claim, look for:

- evidence supporting it;
- evidence contradicting it;
- evidence limiting its generalizability;
- evidence suggesting different conditions under which it behaves differently.

Distinguish independent confirmation from redundancy.

Two sources should not automatically count as two independent pieces of evidence when they reuse the same dataset, assumptions, research lineage, or underlying result.

Independent replication may add substantial weight when it genuinely introduces new information.

### 9. Evaluate evidence multidimensionally

Use domain-appropriate criteria. Possible dimensions include:

- directness: how directly the evidence addresses the claim;
- methodological strength: how robustly the result was obtained;
- scope: how broadly the result applies beyond its specific conditions;
- validation depth: how far the finding has been tested;
- independence: how independent it is from other supporting evidence;
- replication: whether compatible results emerge independently;
- resistance over time: whether the claim has survived meaningful attempts at testing or falsification;
- relevance of counterevidence: whether negative evidence genuinely contradicts the claim or merely narrows it.

Do not use these dimensions mechanically. Some will be irrelevant in particular domains.

Do not reward age by itself. A long-standing claim gains weight only when longevity represents repeated meaningful testing, not mere survival without scrutiny.

### 10. Expose the judgment behind evidence ratings

Do not present a score without explaining why it was assigned.

When more than one assessment is reasonably defensible, use a range rather than a single value.

Example:

`Scope: 2–3 / 4`

Then explain why both values are plausible.

The goal is to make the researcher's discretion inspectable.

### 11. Use scoring only as a diagnostic tool

A numerical model may be useful for testing robustness, but do not treat its output as a probability that a claim is true.

Avoid presenting results such as:

`Claim A is 73% true.`

Instead, use scoring internally to examine whether the conclusion changes under reasonable alternative assumptions.

### 12. Run sensitivity analysis

Test at least two forms of sensitivity when numerical evaluation is used.

#### Weight sensitivity

Change the relative importance of evaluation criteria within reasonable bounds.

Ask whether the conclusion changes when, for example, replication is weighted more heavily than scope, or directness more heavily than independence.

#### Judgment sensitivity

Change the underlying evidence ratings within the range of reasonable interpretation.

Ask whether the conclusion changes when an evidence item reasonably receives 2 rather than 3 on a given dimension.

The purpose of sensitivity analysis is not to find the one correct set of numbers. It is to discover how much the conclusion depends on discretionary choices.

### 13. Classify conclusions by robustness

Prefer descriptive categories over pseudo-precise percentages.

Possible outputs include:

- **Strong and stable support**: the conclusion remains substantially unchanged across reasonable assumptions.
- **Conditional support**: the conclusion is plausible but materially depends on specific methodological judgments or conditions.
- **Unresolved**: reasonable methodological choices lead to materially different conclusions or current evidence does not clearly distinguish alternatives.

Explain what makes the result stable or unstable.

### 14. Allow the question to fail

A valid outcome is discovering that the original question should be reformulated.

Possible reasons include:

- key terms are ambiguous;
- the question combines substantially different phenomena;
- a presumed binary opposition is false;
- important contextual variables change the answer;
- available evidence does not measure the outcome the question assumes it measures.

Reformulating the question is not a research failure.

### 15. Publish or preserve the reasoning trail

When the result is intended for others, expose enough of the process that another person could challenge it.

Where relevant, preserve:

- the exact question;
- the scope and exclusions;
- the initial position;
- discovery channels;
- the alternatives considered;
- meaningful alternatives excluded and why;
- evaluation criteria;
- evidence used;
- reasoning behind evidence judgments;
- weighting assumptions;
- sensitivity analysis;
- remaining uncertainty;
- points where the process could reasonably have been designed differently.

A reader should be able to change a disputable assumption and understand whether the conclusion would change.

## Important distinctions

### Discovery is not evaluation

A weak or obscure source may reveal an alternative worth investigating without being strong evidence for that alternative.

Use a source's discovery value separately from its evidentiary value.

### Evidence against is not always contradiction

Some evidence disproves or directly weakens a claim.

Other evidence only narrows the conditions under which it holds.

Do not collapse these into the same category.

### Popularity is not validity

A well-represented position may have more evidence because it has received more attention.

A minority position should not receive equal final weight automatically, but it should not be excluded merely because it is less known.

### Transparency is not correctness

Making assumptions explicit does not make them good assumptions.

Transparency allows scrutiny, revision, and disagreement. It does not absolve weak reasoning.

### Numbers do not remove discretion

A quantitative model can hide subjective judgments behind apparent precision.

Use numbers to test robustness, not to disguise interpretation as objectivity.

## Role of AI

AI may assist with:

- widening discovery beyond familiar or highly ranked sources;
- identifying apparently missing positions;
- grouping variants of the same argument;
- tracing source relationships and possible redundancy;
- extracting candidate evaluation criteria from domain literature;
- finding supporting, contradicting, and limiting evidence;
- comparing how a conclusion changes under alternative reasonable assumptions.

AI should not:

- assume the user's first position is the thesis to prove;
- equate visibility, citation count, prestige, or search ranking with correctness;
- invent missing steps in a weak argument in order to make it viable;
- treat all minority positions as equally credible;
- claim that discovery was exhaustive;
- convert subjective evidence judgments into false certainty;
- hide its own role as a filtering layer in discovery.

## Depth modes

Use the lightest mode that can responsibly answer the question.

### Light

For forming an initial opinion or preparing a non-technical article.

- define the question;
- identify the strongest credible alternatives;
- gather a limited but diverse evidence set;
- expose major uncertainties and methodological choices;
- avoid formal scoring unless it materially clarifies robustness.

### Standard

For evidence-sensitive articles, analyses, or decisions.

Apply the full discovery and evaluation process, with explicit comparison of claims and at least qualitative sensitivity testing.

### Deep

For high-stakes, highly contested, or methodologically complex questions.

Use broader discovery, more explicit evidence mapping, stronger independence checks, numerical sensitivity analysis when useful, and a detailed reasoning trail.

Do not describe Deep mode as equivalent to a systematic review or validated scientific protocol unless it actually follows one.

## Adversarial self-check

Before finalizing a conclusion, ask:

1. Did the initial position receive any privilege merely because it was stated first?
2. Did the discovery process meaningfully search outside the most visible sources?
3. Are apparently competing positions actually incompatible?
4. Did any source receive more authority than its evidence warrants because of prestige?
5. Did a minority position receive artificial credibility merely because it was minority?
6. Are supporting sources genuinely independent?
7. Have counterevidence and scope-limiting evidence been distinguished?
8. Could another reasonable evaluator assign materially different evidence ratings?
9. Would reasonable changes in weights or ratings change the conclusion?
10. Is any numerical result creating more apparent precision than the evidence supports?
11. Did the research reveal that the original question should be changed?
12. Can another person inspect where discretion entered the process?

If important weaknesses remain, state them instead of forcing a definitive conclusion.

## Provisional status

This skill is experimental.

Revise it only when repeated real-world use reveals a stable improvement, a clear failure mode, or an explicit project decision.

Do not convert a single successful application into a permanent universal rule.
