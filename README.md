# UVIF Educational Resilience Dynamics

## Overview

This repository provides a reproducible framework for modeling educational resilience, learner-state evolution, temporal educational stability, and intervention-aware learning analytics using a dynamic-equilibrium formulation: a bounded composite educational-equilibrium index updated recursively at each learning window.

The framework models learning behavior as a dynamic equilibrium process governed by competing educational factors including:

- engagement,
- overload,
- instability,
- resilience,
- persistence,
- intervention support.

Rather than treating educational analytics as a purely prediction-centric task, the framework focuses on:

- learner-state transitions,
- temporal equilibrium dynamics,
- educational resilience analysis,
- intervention governance,
- longitudinal educational trajectories,
- counterfactual educational support simulation.

---

## Main Components

### Educational Equilibrium Modeling
Learner states are represented through an equilibrium-aware educational formulation that evolves over time under competing educational forces.

### Learner-State Dynamics
The framework models transitions between critical, fragile, recovering, and stable educational states.

### Educational Resilience Analysis
The repository includes resilience-aware temporal stability analysis and equilibrium preservation behavior.

### Intervention Governance
Governance-oriented educational support priorities are generated from equilibrium and stability conditions.

### Counterfactual Educational Support
The framework evaluates alternative educational-support strategies and their effect on equilibrium recovery.

### Sensitivity and Robustness Analysis
The notebook repeats the simulation in 430 runs across 33 configurations (attrition constant, individual and joint weight scaling, threshold shifts, noise level, index feedback) and reports means and standard deviations across random seeds.

### Propagated Counterfactual Support
Support scenarios are also applied inside the simulation with common random numbers, so that their effect is carried through the dynamics. All counterfactual values are model-based estimates under stated assumptions, not causal effect estimates.

---

## Repository Structure

```text
.
├── notebooks/
├── figures/
├── tables/
├── outputs/
├── data/
├── README.md
└── requirements.txt
```

---

## Generated Outputs

The framework generates:

- equilibrium-state summaries,
- learner-state transition matrices,
- temporal stability analysis,
- resilience-group summaries,
- governance-priority analysis,
- counterfactual intervention analysis,
- educational equilibrium visualizations,
- learner-trajectory figures.

---

## Example Research Themes

This repository may support research in:

- learning analytics,
- educational resilience,
- temporal educational modeling,
- educational governance,
- intervention-aware educational systems,
- human-centered educational AI,
- trustworthy educational intelligence.

---

## Reproducibility

The notebook automatically generates:

- datasets,
- figures,
- tables,
- manuscript-ready outputs,
- summary reports.

Outputs are saved to structured directories for reproducible experimentation and educational-analysis workflows.

---

## License

This repository is intended for research and educational purposes.
