# Contributing

## Authority

Resolve conflicts using the order in [`docs/PROTOCOL.md`](docs/PROTOCOL.md) and the repository operating contract.

## Local checks

```bash
pip install -e ".[dev]"
iepe-validate
pytest
```

CI runs `python3 tools/validate.py` and `python3 -m pytest -v` on every pull request.

## Changes

- Prefer issue contracts for material work (intent, acceptance, evidence, stop conditions).
- Keep core artifacts domain-neutral; domain specifics belong in adoption profiles.
- Preserve status honesty: documented ≠ implemented ≠ tested ≠ empirically validated.
- Do not add AI assistant co-author trailers or tooling-only files to the public scholarly surface.

## Conventions

- Commit messages are short and descriptive. The history uses prefixes such as `feat:` and `ci:` on some commits.
- Open a pull request against `main` and fill in the pull request template: what and why, how it was verified, and notes.
- Record notable changes under `## Unreleased` in [`CHANGELOG.md`](CHANGELOG.md).

## Agent guidance

[`AGENTS.md`](AGENTS.md) is the operating contract for coding agents working in this repository; it applies to people as well.

## Conduct, support and security

See [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md), [`SUPPORT.md`](SUPPORT.md) and [`SECURITY.md`](SECURITY.md).

## Citation

See [`CITATION.cff`](CITATION.cff).
