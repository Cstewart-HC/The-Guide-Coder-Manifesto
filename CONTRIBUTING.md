---

# Contributing to the Guide Coding Manifesto

Thank you for reading the manifesto carefully enough to want to change it. That alone puts you in the small group of people this document is for.

This file explains how to propose refinements, what kinds of changes the maintainers are looking for, and — just as importantly — what kinds of changes the manifesto is *not* trying to accumulate. Please read it before opening a PR.

## The manifesto is meant to be short

Thirteen principles is already more than Agile (twelve) and fewer than Zen of Python (nineteen). That range is deliberate. A manifesto that grows past twenty principles stops being a manifesto and becomes a checklist.

The strong default is **fewer, sharper principles**. A PR that removes a principle by folding its idea into a stronger one is more valuable than a PR that adds a new principle. A PR that sharpens the wording of an existing principle without changing its meaning is more valuable than both.

If you want to add a principle, the burden is on the PR to show that the idea is not already carried by an existing one — and that the document is meaningfully weaker without it.

## What this manifesto is

- A statement of values and principles for guiding AI code generation through intentional human design.
- A working document, versioned openly, refined in public through pull requests.
- A reference practitioners can point at when defending their choices.
- A creed practitioners can internalize to shape their working disposition.

## What this manifesto is not

- Not anti-AI. Guide Coding assumes AI-assisted development and argues for doing it well.
- Not a prompt engineering methodology. Prompts are tactics; this document is about stance.
- Not a certification, a framework, or a brand. There is no Guide Coding Institute.
- Not a tooling recommendation. The principles are tool-agnostic on purpose.
- Not a rejection of Vibe Coding as a phrase so much as a correction of its worst forms.
- Not a finished document. It is v0.1 and it will change.

PRs that pull the manifesto toward any of these non-goals will be closed with thanks.

## How to propose a change

1. **Open an issue first for substantive changes.** Wording tweaks can go straight to PR. Anything that changes the meaning of a principle, adds a principle, removes one, or restructures the values should start as an issue so the discussion is visible before the diff exists.
2. **One change per PR.** Do not bundle a wording fix with a new principle with a values-layer reorganization. Each idea gets its own PR and its own conversation.
3. **Explain the *why* in the PR description.** What is the current text failing to do? What is your proposed text doing better? Manifesto edits are philosophical before they are editorial — show the reasoning.
4. **Tag the draft.** Reference the draft number the change is proposed against (currently v0.1). If a newer draft has landed by the time your PR is reviewed, you may be asked to rebase onto it.

## What good PRs look like

- **Sharpening.** Removing a word that isn't earning its place. Replacing a soft verb with an active one. Breaking a triple into a double if the third beat is weak.
- **Clarifying.** Resolving ambiguity in a principle without changing its meaning. Making an abstract principle actionable.
- **Consolidating.** Merging two principles that are saying the same thing into one stronger principle.
- **Translating.** Producing a faithful translation of the manifesto into another language. These go into `/translations/` and should preserve the two-altitude structure.

## What weak PRs look like

- **Adding without removing.** A new principle that doesn't displace an existing one bloats the document.
- **Hedging.** Softening a principle to accommodate edge cases. The principles are meant to be strong defaults, not exception-proof rules.
- **Genericizing.** Rewriting a specific claim into something that could appear in any software manifesto. Specificity to the AI-assisted moment is the document's point.
- **Proliferating examples.** The manifesto does not contain examples. It is meant to be referenced against cases, not filled with them.
- **Tooling mentions.** No principle should name a model, a framework, a vendor, or a language.

## The value pairs

The four values are the most stable part of the document. PRs that touch the values need to argue against the whole rather than against a single pair — the values are a set, and changing one changes the balance of the set.

If you believe a value is missing, an issue is probably the right venue for at least a week of discussion before a PR exists.

## On signatories

Contributors whose PRs are merged are acknowledged in `CONTRIBUTORS.md`. This is distinct from the list of signatories who endorse the current draft as a whole, which lives in `SIGNATORIES.md` and is opt-in — adding yourself is a pull request in its own right.

We are explicitly *not* using "signatory" as a gatekeeping mechanism. If you work in the spirit of the manifesto, you are a Guide Coder regardless of whether your name appears anywhere in this repository.

## On disagreement

Manifestos attract principled disagreement. If you read the document and think a principle is wrong — not poorly worded, but wrong — open an issue and make the case. Dissent that sharpens the document is welcome. Dissent that would convert the document into a different document is better served by writing your own.

The essay accompanying the manifesto is the longer argument the principles are compressing. If a PR feels like it's arguing against something the manifesto doesn't quite say, the essay may clarify the underlying claim before the PR is necessary.

## A note on tone

The manifesto is written in declarative sentences, active voice, minimal ornament. Proposed changes should match that register. Contributions written in marketing voice, in academic voice, or in the voice of an internal style guide will be asked to revise.

## Maintainers

The current maintainers are listed in `MAINTAINERS.md`. Maintainer decisions on PRs are final for the purpose of merging, but every closed PR remains in the repository's history and can be reopened by a future maintainer or revived in a later draft. Nothing about this process is permanent.

---

*This CONTRIBUTING.md is itself open to PRs. It is a draft.*

---
