# Limitations

Status: public-facing draft  
Last updated: 2026-06-09

## Core caveat

AI Electronics Lab may produce explanations, generated artifacts, and simulation-oriented outputs.

These outputs are not physical proof.

A model can be incomplete. A simulation can be misconfigured. A generated schematic or netlist can contain mistakes. A result that looks plausible can still be wrong.

## Simulation is not hardware validation

A simulation can help reason about a model.

It does not guarantee that a real circuit will work on a breadboard, PCB, module, or product.

Real hardware can differ because of:

- component tolerances;
- parasitics;
- supply behavior;
- temperature;
- layout;
- measurement setup;
- model limitations;
- missing real-world effects;
- wrong assumptions in the prompt or generated model.

## Public wording rules

Avoid claims that imply:

- guaranteed hardware correctness;
- guaranteed design success;
- production-grade safety;
- compliance readiness;
- complete replacement of an electronics engineer;
- physical validation without measurement;
- broad support for arbitrary circuit categories.

Prefer bounded language:

- "simulation-oriented workflow";
- "generated artifact";
- "model evidence";
- "draft explanation";
- "requires review";
- "prototype workflow";
- "public beta" when applicable;
- "visible caveat";
- "what-if iteration".

## Required review for claims

Technical review is required before publishing claims about:

- electronics correctness;
- SPICE behavior;
- schematic validity;
- calculation accuracy;
- units and tolerances;
- hardware safety;
- physical behavior;
- production readiness;
- component-specific behavior;
- feature completeness.

## What the project can responsibly claim now

Safe claims:

- AI Electronics Lab is a working prototype.
- The project explores AI-assisted electronics simulation workflows.
- The public site is available at https://ai-electronics-lab.pages.dev.
- The first public demo direction is an RC low-pass filter workflow.
- The public repository contains documentation, limitations, and example structure.
- The protected app is intended for selected or semi-public beta access.
- Current public demo app credentials may be listed when intentionally approved for public prototype access.

## What the project should not claim now

Do not claim:

- arbitrary circuit support;
- production-grade simulation accuracy;
- fully autonomous electronics design;
- safety or compliance validation;
- replacement of CAD/EDA tools;
- replacement of senior engineers;
- guaranteed correctness of generated circuits.

## AI-agent limitation

AI agents can help structure work, generate drafts, preserve context, and propose next steps.

They can also misunderstand, hallucinate, overgeneralize, lose context, or produce plausible but wrong artifacts.

Therefore, public claims, technical examples, and user-facing outputs should remain reviewable and bounded.

## Private information boundary

Do not publish:

- secrets or private credentials;
- internal hostnames;
- private operational paths;
- private runbook details;
- unapproved screenshots;
- internal artifact paths;
- private evidence packets;
- raw internal logs;
- private infrastructure details;
- privileged admin access;
- non-public operational credentials.

Public demo app credentials may be published only when they are intentionally approved for public prototype access and do not grant administrative or internal access.

## Good public caveat pattern

Use:

```text
This example shows the behavior of a simple model and simulation-oriented workflow. It is not a guarantee of real hardware behavior. Real circuits require review, measurement, and safety-aware validation.
```
