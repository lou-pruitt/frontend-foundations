# Frontend Foundations — Project Principles

This document defines the non-negotiable principles that guide the design,
scope, and maintenance of Frontend Foundations.

These principles exist to protect beginners, preserve clarity, and ensure
that the project remains a trustworthy learning environment over time.

---

## 1. Beginner Safety Comes First

Frontend Foundations is designed for people with **zero coding experience**.

If a concept, instruction, or step would confuse a true beginner, it must be
rewritten, simplified, or delayed.

We optimize for clarity and reassurance, not speed or cleverness.

---

## 2. Sequential Learning Is Non-Negotiable

This project is designed to be followed **step by step, in order**.

Each step intentionally builds on previous knowledge. We do not introduce
shortcuts, jumps, or alternative paths that bypass understanding.

Skipping ahead may be tempting, but it undermines the learning model.

---

## 3. Understanding Over Output

The goal of this project is not to produce finished code quickly.

Learners are encouraged to:

- Explain what they are doing
- Modify examples
- Verify behavior in the browser
- Reflect on what changed and why

Copying code without comprehension defeats the purpose of this project.

---

## 4. Tools Are Chosen for Accessibility and Longevity

We prioritize tools that are:

- Free
- Open source
- Widely available
- Industry standard

Visual Studio Code is the reference IDE because it meets these criteria and
reduces friction for beginners.

Tooling should lower barriers, not create them.

---

## 5. AI Is a Mentor, Not an Author

AI tools are used as **guided mentors** to support learning, not as authoritative
sources or replacements for thinking.

Learners are taught how to:

- Ask good questions
- Evaluate AI responses
- Verify results in code
- Recognize uncertainty or mistakes

Blind trust in AI output is explicitly discouraged.

---

## 6. Scope Is Intentionally Limited

Frontend Foundations focuses on:

- HTML fundamentals
- CSS fundamentals
- JavaScript fundamentals
- Basic development tooling

Frameworks, build systems, advanced optimizations, and backend topics are
intentionally excluded in early stages to prevent overload.

A limited scope is a feature, not a limitation.

---

## 7. Pedagogy Over Preference

Decisions are made based on what helps beginners learn effectively, not on
personal preferences, trends, or debates within the developer community.

Technical elegance is secondary to conceptual clarity.

The primary question is always:
“Does this make learning clearer for a beginner?”

---

## 8. Contributions Must Preserve Beginner Clarity

Frontend Foundations uses a deliberate narrative voice: **“we”** speaking to
**“you.”**

“We” represents the maintainers, contributors, and mentors guiding the project.
“You” represents the learner — with the understanding that learners are
encouraged to grow into contributors over time.

This language is intentional. It reflects the idea that learning is a process
of joining a community, not consuming instructions.

All contributions must:

- Preserve this narrative voice (“we” → “you”)
- Respect sequential learning
- Avoid shortcuts or assumed knowledge
- Improve clarity without increasing complexity

Contributions should invite learners to see themselves as future contributors,
not permanent outsiders.

---

## 9. Maintainer Has Final Decision Authority

To preserve consistency, coherence, and beginner safety, final decisions
regarding scope, structure, and pedagogy rest with the project maintainer.

Open source collaboration is encouraged, but direction is intentionally
maintained.

---

## Closing Note

These principles are not intended to restrict collaboration.

They exist to ensure that Frontend Foundations remains a safe, clear, and
trustworthy starting point for people learning web development for the first
time.


### Single-Source Workbook During Structural Design

While the curriculum structure is still being designed and validated,  
**Frontend Foundations uses a single `WORKBOOK.md` file as the source of truth.**

This is intentional.

A single document:
- Preserves narrative continuity for beginners
- Makes pacing and pause points visible at a glance
- Prevents accidental skipping or modular reordering
- Keeps structural decisions easy to evaluate and revise

Steps may be split into separate files only **after**:
- The learning loop is complete
- Step boundaries are stable
- The curriculum is ready for external contributors or reuse

Until then, structural clarity takes priority over modular convenience.
