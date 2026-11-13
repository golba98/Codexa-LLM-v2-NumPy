# Base-model evaluation

`evaluation/prompts_general.json` contains deterministic qualitative probes for
continuation, factual language, science, code, and proto-conversation. These
are base-model probes, not evidence of chat quality. Keep seed, temperature,
top-k, top-p, and maximum generation length fixed when comparing checkpoints.

Primary quantitative metrics are held-out general-language cross entropy and
perplexity. Shakespeare is not the production validation set.

## Historical consolidation validation

The October 2026 consolidation recorded 126 NumPy tests passing, including CPU/CuPy and migration checks. Bounded checkpoint inference comparisons preserved the original generated tokens; this does not establish every possible training trajectory. Reproduce current CPU checks with `.venv/bin/python -m pytest -q -p no:cacheprovider tests`. Public-clone checks skip unavailable private asset references. Historical checkpoint, relocation and workstation evidence remains private; these historical results do not certify the current tree or a fresh environment.
