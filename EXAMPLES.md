# Examples

Status: public-facing draft  
Last updated: 2026-06-09

## Public demo strategy

Examples should be small, honest, inspectable, and caveated.

The goal is not to show that AI can solve all electronics problems.

The goal is to show a visible workflow:

```text
idea → model → simulation/calculation → artifact → plot → explanation → caveat → next iteration
```

## First example: RC low-pass filter

The first public example is planned around a simple RC low-pass filter.

Planned public route:

```text
https://ai-electronics-lab.pages.dev/experiments/rc-low-pass-001
```

Repository example path:

```text
examples/rc-low-pass-001/
```

## Why RC low-pass?

This example is intentionally simple because it helps make the workflow visible:

- the user goal is easy to understand;
- the circuit model is small;
- the frequency-response plot is meaningful;
- the cutoff-frequency concept is explainable;
- caveats are easy to state;
- what-if changes are natural.

## Example approval rules

Every public example should include:

- user-visible goal;
- what the workflow demonstrates;
- current capability vs roadmap status;
- input prompt or sanitized prompt summary;
- circuit model or schematic artifact;
- plot or output artifact;
- explanation;
- assumptions;
- limitations and caveats;
- whether the result came from simulation, calculation, fallback, or another path;
- technical review status for electronics claims;
- QA check status for links and Markdown rendering.

## Required caveat in examples

Every example should include a caveat similar to:

```text
This example shows the behavior of a simple model and simulation-oriented workflow. It is not a guarantee of real hardware behavior. Real circuits require review, measurement, and safety-aware validation.
```

## Candidate future examples

These are candidates, not public commitments:

- RC high-pass filter;
- resistive divider;
- BJT common-emitter before/after;
- tolerance or parameter-change walkthrough;
- generated report reading guide;
- limitation-aware troubleshooting example;
- simple “why this circuit does not behave as expected” workflow.

## Example status table

| Example | Status | Public route | Notes |
| --- | --- | --- | --- |
| RC low-pass filter | planned first public demo | `/experiments/rc-low-pass-001` | Small, inspectable workflow. |
| BJT common-emitter before/after | candidate | not published | Needs careful technical caveats. |
| Resistive divider | candidate | not published | Good beginner example. |
| RC high-pass filter | candidate | not published | Natural follow-up to low-pass. |

## Do not treat candidates as promises

The candidate list is not a public feature commitment.

Each example needs review before being described as supported capability.
