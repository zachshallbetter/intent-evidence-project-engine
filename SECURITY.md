# Security Policy

## Reporting a vulnerability

Please report security issues privately rather than opening a public issue. Use GitHub private
vulnerability reporting:

**https://github.com/zachshallbetter/intent-evidence-project-engine/security/advisories/new**

Include a description of the issue and its impact, steps to reproduce (a minimal example is ideal),
and the affected path and version.

This is a solo-maintained project. Handling is best-effort with no SLA: there is no guaranteed
response or fix time.

## Scope

IEPE is a protocol, a set of JSON schemas and a Python reference implementation (`iepe_core/`) with
command-line tools (`iepe-init`, `iepe-compile`, `iepe-validate`). The tools read and write files in a
project root you point them at, and read schema, evidence and package-source files. Reports about unsafe
file writes or path handling in the tools, unsafe handling of those input files, and the repository's
CI workflow are in scope. The protocol documents describe a process and are not a security boundary.

## Supported versions

Only the latest tagged release receives fixes. Fixes land on `main` and ship in the next release.
