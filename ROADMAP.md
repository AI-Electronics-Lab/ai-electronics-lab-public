# Roadmap

Status: public-facing draft  
Last updated: 2026-06-09

This roadmap is intentionally phased rather than date-driven.

The project should grow through small public artifacts, not through broad promises.

## Phase 0 — stable public identity

Purpose: make it clear that the project exists and has a coherent direction.

Expected public surfaces:

- public site: https://ai-electronics-lab.pages.dev;
- public GitHub repository;
- Hackaday.io project page;
- LinkedIn professional framing.

Key message:

```text
AI Electronics Lab is a working prototype for AI-assisted electronics simulation workflows and human-machine engineering collaboration.
```

Success signal:

- a reader can understand the project in 1–2 minutes;
- the site and repository do not overclaim;
- the project has visible limitations;
- the protected beta app has a clear entry point.

## Phase 1 — first public demo: RC low-pass filter

Purpose: show one complete, understandable example.

Public demo route:

```text
/experiments/rc-low-pass-001
```

Expected content:

- user goal;
- circuit model;
- schematic artifact;
- plot artifact;
- explanation;
- assumptions;
- caveats;
- next what-if prompt;
- link to public GitHub example.

Why this matters:

A simple RC low-pass filter is enough to demonstrate the workflow:

```text
idea → model → simulation → plot → explanation → caveat → iteration
```

Success signal:

- public visitor can see a concrete artifact without entering the protected app;
- GitHub contains a corresponding public example;
- the limitations are visible and not hidden.

## Phase 2 — protected beta application flow

Purpose: allow selected or semi-public users to try the app with a password.

Expected app flow:

- initial simulation prompt;
- first result;
- schematic and plot;
- run details;
- what-if prompt;
- before/after comparison;
- iteration history;
- visible caveats;
- fail-closed behavior for unsupported or contextless prompts.

Success signal:

- supported RC low-pass prompts produce valid, non-blank artifacts;
- what-if requests preserve previous context;
- comparison views do not mix stale artifacts;
- users can understand what happened without inspecting backend logs.

## Phase 3 — public example library

Purpose: grow from one public experiment into a small library.

Candidate examples:

- RC low-pass filter;
- RC high-pass filter;
- resistive divider;
- BJT common-emitter before/after;
- tolerance or parameter-change example;
- simple “why this circuit does not behave as expected” walkthrough.

Success signal:

- examples are small and inspectable;
- each example includes limitations;
- examples are not presented as full feature commitments;
- examples connect public site, GitHub, and Hackaday logs.

## Phase 4 — agent-assisted product development narrative

Purpose: show not only the electronics product, but the operating system behind it.

Public themes:

- AI agents in product development;
- Scrum-like iteration;
- human approval gates;
- runtime truth over superficial green checks;
- public artifacts as trust surfaces;
- documentation as product memory.

Success signal:

- LinkedIn and Hackaday posts tell a coherent story;
- public GitHub materials support the story without exposing private implementation;
- the project becomes useful as a professional artifact for work, partners, or future business exploration.

## Phase 5 — community and feedback loop

Purpose: collect useful feedback without creating a support burden.

Possible channels:

- GitHub issues for public documentation or examples;
- Hackaday comments;
- LinkedIn discussion;
- semi-public app password sharing;
- direct feedback from trusted users.

Success signal:

- feedback produces better examples, limitations, and product backlog items;
- unsupported requests reveal useful gaps;
- no channel becomes an unmanaged helpdesk.

## Not committed yet

The following are not public commitments until reviewed and accepted:

- specific feature timelines;
- broad supported circuit categories;
- simulation accuracy guarantees;
- hardware correctness guarantees;
- integrations with CAD/EDA tools;
- commercial or pricing plans;
- public availability of the full product source code.
