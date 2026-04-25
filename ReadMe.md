## License
[LICENSE](LICENSE)

# Tierceron-succinctly

[![GitHub release](https://img.shields.io/github/release/trimble-oss/tierceron-succinctly.svg?style=flat-square)](https://github.com/trimble-oss/tierceron-succinctly/releases/latest)
[![Go Report Card](https://goreportcard.com/badge/github.com/trimble-oss/tierceron-succinctly)](https://goreportcard.com/report/github.com/trimble-oss/tierceron-succinctly)
[![PkgGoDev](https://img.shields.io/badge/go.dev-docs-007d9c?logo=go&logoColor=white&style=flat-square)](https://pkg.go.dev/github.com/trimble-oss/tierceron-succinctly/succinctly)

## What is it?
Tierceron-succinctly contains the `succinctly` package, a small dictionary-to-short-code mapper. It hashes words, assigns the shortest unique hexadecimal prefixes that fit within configured limits, and provides lookup in both directions.

## What is in this repo?
- `succinctly`: in-memory initialization, word-to-code lookup via `QCode`, and code-to-word lookup via `QWord`.
- `Makefile`: `depend`, `clean`, and `test` targets for maintaining the module.

## Key Features
- Deterministic short-code generation from a caller-supplied dictionary.
- Reverse lookup support for both words and generated codes.
- A small, focused package with no extra top-level commands.

## Getting started
To work with the module locally:

- Run `go test ./...`.
- Import the package from `github.com/trimble-oss/tierceron-succinctly/succinctly`.

## Trusted Committers
- [Joel Rieke](mailto:joel_rieke@trimble.com)
- [David Mkrtychyan](mailto:david_mkrtychyan@trimble.com)
- [Karnveer Gill](mailto:karnveer_gill@trimble.com)
- [Meghan Bailey](mailto:meghan_bailey@trimble.com)

## Security
Please review [SECURITY.md](SECURITY.md) for vulnerability reporting guidance.