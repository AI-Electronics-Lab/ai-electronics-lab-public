# AI Electronics Lab

## 🌐 Public site — start here

# https://ai-electronics-lab.pages.dev

**AI Electronics Lab** is a working prototype for AI-assisted electronics simulation workflows.

It explores how a circuit idea can become a structured simulation task, artifacts, plots, explanations, caveats, and follow-up iterations.

The public site is the main entry point. It shows the product concept, the protected beta application link, and the first public demo direction.

---

## What this repository is

This repository is the **public evidence and documentation layer** for AI Electronics Lab.

The full product implementation is private-first. This repository contains public-facing material that can be safely shown to people who want to understand the project without seeing the private product source code.

Use this repository to inspect:

- the product narrative;
- current public positioning;
- limitations and caveats;
- safe public claims;
- example structure;
- roadmap direction;
- publication and claim-review rules.

## What the product does

The intended workflow is:

```text
human circuit idea
→ structured simulation request
→ circuit model / schematic artifact
→ simulation or calculation path
→ plot / result artifact
→ explanation
→ caveats
→ what-if iteration
→ before/after comparison
```

This is not a generic chatbot page. The goal is to make engineering reasoning more visible and reviewable.

## Current public demo direction

The first public demo is centered on a simple **RC low-pass filter**.

Why this example?

- It is small enough to understand quickly.
- It has a clear expected plot.
- It makes assumptions and caveats easy to show.
- It demonstrates the full workflow: request, schematic, plot, explanation, limitations, and next what-if questions.

Planned public demo route:

```text
https://ai-electronics-lab.pages.dev/experiments/rc-low-pass-001
```

## Protected beta application

The working application is protected during early testing.

Entry point through the public site:

```text
https://ai-electronics-lab.pages.dev
```

The protected app is intended for invited or semi-public beta users who already know the access password.

## What this project is not

AI Electronics Lab is not:

- a CAD or EDA replacement;
- proof that a physical circuit will work;
- a replacement for engineering judgment;
- a replacement for real measurements;
- a safety, compliance, or production-readiness validator;
- a claim that AI can automatically design correct hardware.

Simulation output is evidence about a model and workflow. It is not physical proof.

## Why this matters

Senior engineering judgment is valuable and hard to scale.

AI Electronics Lab explores whether AI agents can help learners, junior and mid-level engineers, makers, and embedded developers work more systematically by making assumptions, artifacts, plots, caveats, and iteration history visible.

The goal is not to replace senior engineers.

The goal is to help people practice better engineering habits and produce more reviewable artifacts.

## Human-machine engineering experiment

The project is also an experiment in AI-agent-assisted product development:

- backlog-driven work;
- Scrum-like iteration;
- human approval gates;
- runtime truth checks;
- public artifacts;
- explicit claim boundaries;
- visible limitations.

The deeper question is:

> Can AI agents help build and operate a technical product while keeping human responsibility, engineering evidence, and reviewability visible?

## Repository map

| File | Purpose |
| --- | --- |
| [`MANIFESTO.md`](MANIFESTO.md) | Core principles and public narrative. |
| [`PRODUCT.md`](PRODUCT.md) | What the product is, what it is not, and who it is for. |
| [`ROADMAP.md`](ROADMAP.md) | Phased direction without overcommitting timelines. |
| [`LIMITATIONS.md`](LIMITATIONS.md) | Caveats, boundaries, and safe wording. |
| [`EXAMPLES.md`](EXAMPLES.md) | Public example strategy and approval rules. |
| [`FAQ.md`](FAQ.md) | Short answers for public readers. |
| [`CHANGELOG.md`](CHANGELOG.md) | Public repository changes. |
| [`docs/claim-review.md`](docs/claim-review.md) | Checklist for safe public claims. |
| [`docs/publication-checklist.md`](docs/publication-checklist.md) | Publication gate checklist. |

## External links

- **Public site:** https://ai-electronics-lab.pages.dev
- **Public repository:** https://github.com/AI-Electronics-Lab/ai-electronics-lab-public
- **Organization:** https://github.com/AI-Electronics-Lab

## Publication rule

Public content should remain bounded and reviewable.

Do not publish claims about electronics correctness, SPICE behavior, schematic validity, calculation accuracy, units, tolerances, hardware safety, physical behavior, or production readiness unless they have passed the appropriate review path.

No secrets, credentials, internal hostnames, private runbooks, private artifact paths, or unapproved operational evidence should be added here.
