# Contributing

## Authority

Resolve conflicts using the order in [`docs/PROTOCOL.md`](docs/PROTOCOL.md) and the repository operating contract.

## Local checks

```bash
pip install -e ".[dev]"
iepe-validate
pytest
```

## Changes

- Prefer issue contracts for material work (intent, acceptance, evidence, stop conditions).
- Keep core artifacts domain-neutral; domain specifics belong in adoption profiles.
- Preserve status honesty: documented ≠ implemented ≠ tested ≠ empirically validated.
- Do not add AI assistant co-author trailers or tooling-only files to the public scholarly surface.

## Citation

See [`CITATION.cff`](CITATION.cff).
