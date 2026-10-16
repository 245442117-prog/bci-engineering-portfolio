# Learning Map / 技能学习地图

This learning map follows the projects in the portfolio. **A listed skill is a learning target, not a claim that it is already independently mastered.**

## Layer 1 — Programming and scientific computing

- Python fundamentals: functions, modules, virtual environments, file I/O, exceptions, typing
- NumPy arrays, pandas tables, numerical stability, plotting
- Git: commits, branches, pull requests, version tags and README-based documentation
- Tests and debugging: unit tests, fixtures, errors, reproducibility and dependency versions

## Layer 2 — Signal processing foundations

- Sampling theorem, signal bandwidth and aliasing
- Filtering, baseline correction, normalization and artifact handling
- FFT, power spectral density and Welch estimation
- Time-domain features: RMS, variance, percentiles, moving windows
- Physical sensors: calibration, force vs. torque units, coordinate frames and sensor limitations

## Layer 3 — EEG and machine learning

- EEG channels and reference, events, epochs, ERP and P300
- Train/validation/test separation and leakage prevention
- SVM, random forest, regularization, PCA and cross-validation
- EEGNet and representation learning; why deep models may not always win
- Balanced accuracy, macro-F1, confusion matrices and uncertainty intervals

## Layer 4 — Research engineering and multimodal systems

- Serial frames, producer–consumer queues, single-writer ownership, failure recovery
- Event identity vs. actual physical contact onset
- Time-base alignment, offset, jitter, drift and verification limits
- Multi-modal data contracts, metadata provenance, safe dataset partitioning

## Layer 5 — Independently explain and reproduce

For each released project, aim to:
1. Explain the scientific question and assumptions without notes.
2. Implement one core function from scratch.
3. Reproduce the minimal example, diagnose one injected bug and write a test.
4. Explain why the baseline and metrics are appropriate.
5. Describe confirmed achievements, failure cases, ownership and next improvements.

Project order will be adapted to actual code-publication readiness. Do not treat a planned result as an achieved result.