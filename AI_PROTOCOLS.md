# AI Protocols — Frontend Foundations

This document defines how AI tools (including GitHub Copilot, ChatGPT, and similar systems) may be used in the development and maintenance of **Frontend Foundations**.

These protocols exist to protect beginner safety, preserve sequential learning, and ensure that AI supports understanding rather than replacing it.

AI is treated as a **tool and mentor**, not an authority or curriculum driver.

---

## Core Principle

> **AI may assist with execution, but must never direct learning, pace, or scope.**

AI suggestions are optional, reviewable, and subordinate to the project’s pedagogical goals.

---

## Allowed Uses of AI

AI tools may be used for:

- Syntax recall (e.g. tag names, attribute spelling)
- Small, local code suggestions within the current step
- Boilerplate after a concept has already been introduced
- Verifying that code matches stated intent
- Mechanical edits that do not add new concepts

AI assistance is appropriate only when the maintainer already understands **what** is being done and uses AI to help with **how** to express it.

---

## Disallowed Uses of AI

AI tools must **not** be used to:

- Introduce new concepts before the workbook does
- Suggest future steps or learning paths
- Expand project scope
- Optimize, refactor, or “improve” code
- Recommend best practices, patterns, or tooling
- Introduce frameworks, libraries, or build systems
- Generate large blocks of code without explicit need
- Replace explanation with output

If AI output feels clever, advanced, or efficiency-driven, it is out of bounds.

---

## Step Discipline

AI assistance is limited to the **currently active step**.

AI must not:

- Reference future steps
- Preview upcoming concepts
- Pull in knowledge from later parts of the curriculum

Sequential integrity is non-negotiable.

---

## Explanation Requirement

Any AI-assisted change must remain explainable by the maintainer.

After using AI, the maintainer should be able to answer:

1. What changed?
2. Why did it change?
3. What stayed the same?
4. How could this be undone safely?

If this is not possible, the AI assistance is invalid and should be reverted.

---

## Authority & Tone

AI output is always treated as:

- A suggestion
- A draft
- A hypothesis

AI is never treated as:

- “The correct answer”
- “Best practice”
- “Industry standard”

Human judgment and project principles always take precedence.

---

## Stop Signals

AI use must stop immediately if it:

- Introduces jargon not yet defined
- Encourages faster progression
- Encourages skipping steps
- Mentions performance, optimization, or scalability
- Mentions tools or concepts outside project scope
- Makes the learning process feel more confusing

Stopping is a successful outcome.

---

## Enforcement

These protocols apply to all contributors and maintainers.

If AI usage conflicts with beginner safety, clarity, or sequence, the AI output must be rejected regardless of perceived usefulness.

---

## Summary

> **AI supports learning only when it remains constrained, explainable, and subordinate to pedagogy.**

These protocols exist to ensure that Frontend Foundations remains a calm, trustworthy starting point for beginners.

These protocols complement the project’s core principles in PRINCIPLES.md.
