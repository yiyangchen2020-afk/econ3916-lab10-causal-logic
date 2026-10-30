# Correlation & Causality: Confounders, Colliders and the Limits of Controls

## Objective
I explored why correlation does not necessarily imply causation and how different control variables affect regression estimates.

## Methodology
- Simulated three datasets with different causal relationships.
- Used DAGs to examine confounders, colliders, and mediators.
- Compared regression results with and without controls.
- Used the LaLonde data to compare experimental and observational estimates.
- Used NetworkX to identify a valid adjustment set.

## Key Findings
The three datasets had similar correlations despite different causal effects. Controlling for a collider introduced bias, while adjusting for the right variables improved the estimates.

In the LaLonde analysis, the experimental benchmark was $1,794, compared with -$8,498 without controls and $699 with controls. The controls closed 89% of the gap.

In the M-bias simulation, adding u1 changed the estimate from -0.191 to 0.006, close to the true effect of zero.
