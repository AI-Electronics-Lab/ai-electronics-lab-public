# RC Low-Pass 001 Caveats

Status: draft scaffold  
Last updated: 2026-06-09

## Core caveat

This example shows the behavior of a simple model and simulation-oriented workflow.

It is not a guarantee of real hardware behavior.

Real circuits require review, measurement, and safety-aware validation.

## Possible real-world differences

A physical RC low-pass circuit can differ from the model because of:

- resistor tolerance;
- capacitor tolerance;
- capacitor type and frequency behavior;
- source impedance;
- load impedance;
- breadboard or PCB parasitics;
- measurement setup;
- signal amplitude;
- supply or grounding issues;
- temperature effects;
- incorrect assumptions in the prompt or model.

## Simulation/model caveats

Before treating the result as meaningful, check:

- the chosen R and C values;
- the expected cutoff frequency;
- the analysis type;
- the plotted quantity;
- the frequency range;
- the unit labels;
- whether the schematic and plot match the same iteration.

## Public wording note

Do not say:

```text
This circuit will work in hardware.
```

Prefer:

```text
The model suggests this frequency-response behavior under the stated assumptions.
```
