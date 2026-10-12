# Fair Research

**An experimental skill for exploring credible alternatives, comparing evidence, and making research decisions inspectable.**

Fair Research asks an AI-assisted research workflow to investigate a question without automatically treating the first hypothesis as the position to defend. It is intended for article research, problem analysis, and evidence-sensitive reasoning.

> **Status:** Experimental v0.1. This is not a validated scientific protocol, a systematic-review replacement, or an automated truth detector. Its effectiveness has not been systematically evaluated against other methods.

## What it does

The workflow asks the researcher to:

1. Define the question, outcome, scope, and applicable conditions.
2. Establish and explain evaluation standards before favoring an answer.
3. Record any initial position without privileging it.
4. Look iteratively for credible alternative explanations, including less visible ones.
5. Decide whether purported alternatives genuinely compete or are compatible.
6. Evaluate evidence for specific claims, including contradictions, scope limitations, independence, and replication.
7. Probe whether reasonable methodological judgments would change the conclusion.
8. Preserve enough of the reasoning trail for someone else to challenge it.

The complete operational procedure is in [`SKILL.md`](SKILL.md). The skill also defines an adversarial self-check and three depth modes.

## When to use it

Use it when selection of sources, framing of the question, or weighting of evidence could materially influence an article, analysis, or decision. It can be helpful when an initial opinion already exists, but does not require one.

Choose the lightest responsible depth mode:

| Mode | Appropriate for | Typical output |
| --- | --- | --- |
| Light | Initial exploration and nontechnical articles | Key alternatives, relevant evidence, material uncertainties |
| Standard | Evidence-sensitive research and decisions | Claim-by-claim comparison and qualitative sensitivity checks |
| Deep | Contested or complex questions | Broader evidence map, dependence checks, detailed reasoning trail, numerical sensitivity checks when useful |

Deep mode is **not** automatically a systematic review.

## Installation and use

The root [SKILL.md](SKILL.md) is self-contained. In Codex, place it in a directory named `fair-research` under your user skills directory (`~/.agents/skills`) or the target repository's `.agents/skills` directory. Review an existing installation before replacing it. See the [official Codex skills guide](https://learn.chatgpt.com/docs/build-skills).

### Install locally in Codex

Download this repository using GitHub's **Code → Download ZIP** and extract it,
or clone it with Git:

```sh
git clone https://github.com/francesco-castronuovo/fair-research.git
cd fair-research
```

From the extracted or cloned repository root, run:

```sh
mkdir -p "$HOME/.agents/skills/fair-research"
cp -n SKILL.md "$HOME/.agents/skills/fair-research/SKILL.md"
cmp SKILL.md "$HOME/.agents/skills/fair-research/SKILL.md"
```

The copy does not overwrite an existing file. If the comparison fails, inspect
the existing installation before replacing it. To install only for a project,
use `<your-project>/.agents/skills/fair-research/SKILL.md` instead.

Confirm `fair-research` appears in the skill selector, then use the prompt below.
Codex detects skill changes automatically; restart it if the skill does not appear.
Cloning the repository alone does not install the skill. No package manager or
additional dependency is needed. This repository distributes a manually
installable skill folder, not a Codex plugin.

### Claude and other hosts

For Claude, see the [official skills guide](https://support.claude.com/en/articles/12512180-use-skills-in-claude). Local Codex recognition and two Standard applications have been observed; Claude execution and Light/Deep behavior have not been tested.

Give the assistant your actual question, for example:

```text
Use $fair-research in Standard mode to investigate this question:
For adults over 30, does studying independently with an AI assistant
help them learn a language better than school lessons or private tutoring?
```

You do not need to repeat the workflow instructions in your request. Source access depends on the assistant's tools. No API keys, proprietary database or writing skill are bundled.

## Examples

- [Choice overload](examples/choice-overload.md): illustrative workflow, not a completed validation.
- [Output template](examples/output-template.md): a hypothetical reporting structure.

## Evidence and limits

Two Standard applications on language learning and a follow-up introducing the author's expectation have been observed in Codex. Review found missing source-level access details, grouped school/tutor comparisons and no explicit reason for stopping the search. Later review addressed the first two gaps. These observations do not establish improved accuracy, reduced bias or superiority over research without the skill. No independent expert assessment or no-skill baseline has been completed.

The assistant can miss sources or misread findings. Shared underlying studies must not be counted as independent evidence. Scores, if used, are diagnostic judgments rather than probabilities of truth. A stable answer can still be wrong when important evidence is missing.

## Licensing and provenance

Fair Research is by Francesco Castronuovo and licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See [LICENSE](LICENSE), retain attribution and identify changes.

The v0.1 instruction body is unchanged from the author's original handoff. The approved distribution moves version/status into YAML metadata for compatibility. Fair Research remains experimental and has not been systematically evaluated.
