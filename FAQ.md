# FAQ

Status: public-facing draft  
Last updated: 2026-06-09

## Where should I start?

Start with the public site:

# https://ai-electronics-lab.pages.dev

## How can I try the beta app?

Use the protected beta app with the current public demo access:

- **App:** https://ai-electronics-lab.pages.dev/app/
- **Login:** `Ground_control`
- **Password:** `to_major_Tom`

Please treat this as an early prototype. Results are simulation-oriented artifacts, not hardware validation.

## What is AI Electronics Lab?

AI Electronics Lab is a working prototype for AI-assisted electronics simulation workflows.

It explores how a circuit idea can become a structured simulation task, artifacts, plots, explanations, caveats, and follow-up iterations.

## Is this a product, a research project, or a public notebook?

At this stage, it is all three:

- a working prototype;
- a product experiment;
- a public learning artifact about AI agents in engineering work.

The full implementation remains private-first. This repository contains public-facing documentation and approved example structure.

## Can it prove that my hardware will work?

No.

A generated result, simulation, plot, schematic, or explanation is not physical proof. Hardware work still requires engineering judgment, review, measurement, and safety practices.

## Is it a CAD or EDA replacement?

No.

AI Electronics Lab is not intended to replace CAD tools, EDA tools, lab instruments, measurement, safety review, or senior engineering judgment.

## Who is it for?

Early audiences include:

- electronics learners;
- makers and hobbyists;
- junior and mid-level engineers;
- embedded developers who need clearer analog intuition;
- educators preparing examples;
- R&D teams exploring AI-agent workflows;
- people interested in human-machine engineering collaboration.

## Why focus on junior and mid-level engineers?

Senior engineering judgment is valuable and hard to scale.

The project explores whether AI-assisted workflows can help less-experienced specialists work more systematically, ask better questions, make assumptions visible, and create artifacts that are easier to review.

## Does this replace senior engineers?

No.

The goal is not to replace senior engineers. The goal is to make parts of careful engineering reasoning more visible and easier to practice:

- clarify the goal;
- inspect the model;
- review plots;
- document caveats;
- compare iterations;
- separate simulation from real hardware.

## What is the first public demo?

The first public demo direction is an RC low-pass filter workflow.

Planned public route:

```text
https://ai-electronics-lab.pages.dev/experiments/rc-low-pass-001
```

## Why RC low-pass?

Because it is simple, inspectable, and useful for demonstrating the workflow without overclaiming.

It can show:

- a user prompt;
- a small circuit model;
- a schematic artifact;
- a frequency-response plot;
- an explanation;
- caveats;
- a natural what-if question.

## What is the protected beta app?

The protected app is the working application surface for early testing.

The current public demo credentials are intentionally listed in this FAQ and in the README. They are for early public prototype access, not for private administration or internal operations.

## Why is the full product source private?

The project is private-first while the product, runtime, and agent workflows are still being developed and reviewed.

This public repository exists to share the public narrative, examples, limitations, and evidence without exposing private implementation details.

## Who reviews technical claims?

Claims about electronics correctness, SPICE behavior, schematic validity, calculation accuracy, units, tolerances, safety, or hardware validity require technical review before publication.

## What should not be added here?

Do not add secrets, private credentials, internal hostnames, private runbook details, private artifact paths, raw logs, private screenshots, or unapproved operational evidence.

Public demo app credentials may be listed only when they are intentionally approved for public prototype access.
