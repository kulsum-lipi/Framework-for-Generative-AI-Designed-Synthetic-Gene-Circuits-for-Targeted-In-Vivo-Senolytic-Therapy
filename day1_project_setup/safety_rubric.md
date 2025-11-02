# Initial Safety Rubric - Senolytic AI: Paper 4

This rubric defines the safety checks for generated gene circuits. It is a guide for evaluation in silico and ensures reproducibility and responsible design.

## 1. Leak Tests
- Assess whether circuits activate unintentionally.
- Threshold: Leakiness < 5% of maximum output.

## 2. Off-Target Panels
- Evaluate potential effects on unintended genes.
- Tools: DeepBind, Enformer, Basenji.
- Record any predicted off-target activity.

## 3. Burden Proxies
- Estimate cellular resource usage or metabolic burden.
- Metrics: ribosome load, energy consumption in simulations.

## 4. Simulation Success
- Circuits must run without errors in simulators.
- Tools: BioCRNpyler, Tellurium, gillespy2.

## 5. Thresholds / Pass Criteria
- Define numeric or qualitative rules for each metric.
- Example: pass if leakiness < 5%, off-target score < defined threshold, burden within acceptable limits, and simulation completes successfully.
