# Matched-filter CNN modules — early snapshot

An early source snapshot of the domain-informed matched-filter CNN implementation.

**For the dissertation experiments, results and research-material release, use [DI-WMF-FYP](https://github.com/RRRRFGCK/DI-WMF-FYP).** That repository contains the documented experiment protocols, provenance manifests and verification script.

This smaller repository contains implementation modules only:

- `initializers.py`, `models.py`: initialisation and network definitions.
- `data.py`, `trainer.py`: data and training utilities.
- `corruptions.py`, `faithfulness.py`, `interpretability.py`: evaluation utilities.
- `regression.py`, `adaptive.py`, `energy.py`: supporting implementations.

It does not include the complete experiment runner, released checkpoints or final results. Do not treat this snapshot as the canonical reproduction package.
