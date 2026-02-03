# Background

Smartphones and wearables make it possible to measure health and behaviour day by day in the real world. For example, after knee replacement surgery, recovery is highly variable—people improve at different rates and fluctuate from day to day. At the same time, wearable/smartphone data are rarely complete: missing days and gaps are common.

This hackathon focuses on (1) **simulating realistic post-treatment activity trajectories with realistic missingness**, and (2) **testing how missingness changes the conclusions we draw about recovery**.

Below are the two tasks:

---

## Task 1: Simulation of post-treatment wearable/smartphone trajectories with realistic missingness

### Task overview
Build a **re-usable simulator** that generates **daily activity (e.g., steps)** after a treatment (e.g., knee replacement surgery) over Day 0 to Day T (e.g., T = 365 and T0 is the treatment day). The end goal is a realistic synthetic dataset that can be used for downstream method development and comparison.

More details will be provided during the hackathon.

### The challenge
Design a simulation that captures:
- **Diverse recovery patterns** across individuals (e.g., fast / moderate / slow), with clinically plausible shapes over time.
- **Realistic variability**, including day-to-day fluctuations and between-person differences (no identical trajectories).
- **Realistic missingness** as a configurable component (e.g., different missingness levels), aiming for patterns that look and feel like real wearable/smartphone data loss.

### Evaluation
Your simulator will be reviewed by domain experts, focusing on:
1. **Plausibility** of recovery shapes and variability
2. **Realism** of missingness patterns
3. **Usability** easy to re-run and adapt

---

## Task 2: Identify recovery trajectory groups under missing data

### Task overview
UUse an organiser-provided simulated dataset where the underlying recovery groups are predefined, but observations are incomplete by design under multiple missingness scenarios.

Your objective is to assess **how well recovery trajectory groups can be recovered from incomplete trajectories**, and how results change as missingness becomes more severe or more structured.

More details will be provided during the hackathon.

### The challenge
Develop an analysis approach that:
- Recovers meaningful recovery groups from incomplete step/activity trajectories
- Compares results across missingness mechanisms and missingness levels
- Provides a clear assessment of impact/tolerance: when do conclusions become unreliable, and which missingness patterns affect results the most??

### Evaluation
The analysis approach will be judged on:
1. **Rationale and fairness** (clear justification; fair comparisons)
2. **Communication** (interpretable visuals; concise conclusions)

