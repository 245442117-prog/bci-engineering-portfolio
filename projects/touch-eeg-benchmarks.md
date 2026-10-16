# Touch-EEG Benchmarks — project card

**Scope:** evaluation of classical methods and EEG deep learning baselines using an existing public EEG dataset.

**Evidence currently available:** local research records document an OpenNeuro touch-related EEG benchmark on ds004563 v1.0.1 using held-out subjects. Models include PCA-SVM, EEGNet and LaBraM-based variants, with defined cross-subject testing, negative controls and signal-quality limitations.

**What the finished public repository should contain:** provenance to dataset license and version; preprocessing assumptions; fold/subject partition specification; training/evaluation scripts; run configurations; small non-identifiable fixtures; locked output tables and at least one scientifically readable figure.

**Scientific boundary:** this experiment concerns the public touch-task labels. It is not a real-world K-series surface-texture classification study or proof of EEG–ATI physical synchronization. Results must not imply a clinical diagnostic capability.

**Publication status: PENDING CODE REVIEW.** Public code, weights and figures have not yet been selected, redacted, environment-tested or separately attributed. No runnable release is claimed here.

Study prerequisites: Python array operations → filtering and epochs → classification metrics → cross-subject validation → EEGNet basics.