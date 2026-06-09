# Public Claim Review Checklist

Status: draft  
Last updated: 2026-06-09

Use this checklist before publishing public-facing content on GitHub, the public site, Hackaday.io, LinkedIn, Facebook, Telegram, or any other public channel.

## 1. Claim classification

For each meaningful public claim, classify it as one of:

- Current capability
- Known limitation
- Roadmap / future work
- Speculation / proposal
- Product principle
- Community/narrative statement
- Personal/professional positioning

## 2. Technical review required

Technical review is required for claims about:

- electronics correctness;
- SPICE behavior;
- schematic validity;
- netlist validity;
- calculation accuracy;
- units and tolerances;
- component behavior;
- safety;
- hardware validity;
- production readiness;
- physical performance;
- supported circuit categories.

## 3. Safe wording pattern

Prefer:

```text
AI Electronics Lab helps explore electronics workflows and produce simulation-oriented artifacts with visible assumptions and caveats.
```

Also safe:

```text
This is a working prototype for AI-assisted electronics simulation workflows.
```

```text
This example shows a simple model and workflow. It is not a guarantee of real hardware behavior.
```

## 4. Unsafe wording pattern

Avoid:

```text
AI Electronics Lab guarantees that the circuit will work.
```

```text
AI Electronics Lab replaces electronics engineers.
```

```text
The AI designed a production-ready circuit.
```

```text
This simulation proves the hardware is correct.
```

## 5. Publication safety check

Before publication, confirm:

- [ ] The claim does not imply hardware correctness unless technically reviewed.
- [ ] Simulation is not presented as physical proof.
- [ ] Current capability and future roadmap are separated.
- [ ] Limitations are visible near the relevant claim.
- [ ] No private/internal infrastructure details are exposed.
- [ ] No protected beta password is exposed.
- [ ] Public links point to approved surfaces.

## 6. Public link check

Preferred general project link:

```text
https://ai-electronics-lab.pages.dev
```

Preferred public repository link:

```text
https://github.com/AI-Electronics-Lab/ai-electronics-lab-public
```

## 7. Review record template

For each public document or page, record:

| Field | Value |
| --- | --- |
| Document/path |  |
| Claim summary |  |
| Classification |  |
| Technical review needed | yes/no |
| UX/readability review needed | yes/no |
| QA check needed | yes/no |
| Human publication approval | pending/approved/not requested |
| Notes |  |
