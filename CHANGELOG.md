# Changelog

## Repository retirement — 2026-10-09

- Deprecated this standalone repository in favor of
  `github.com/hollis-labs/substrate/agent@v0.2.0`
  ([migration guide](https://github.com/hollis-labs/substrate/blob/agent/v0.2.0/agent/loopdetect/MIGRATION.md)).
- Preserved existing release tags and history. This documentation change does
  not create a new standalone release or migrate applications.

All notable changes to go-loopdetect are documented here. The format
follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and the project
adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Write the entry for a release here BEFORE cutting its tag: the release workflow
refuses a tag whose CHANGELOG has no heading for it.

## v0.1.0 — 2026-09-29

### Added

- Initial extraction of Nanite's `internal/loopdetect`: `Detector`, `Signal`, `Detection`, `Fingerprint`, `New`, `Record`, `Reset`, the `With*` options and the `Default*` constants. This is an extraction ahead of adoption; no application uses the module yet.
- `doc.go`, `ExampleDetector_Record`, `FuzzNormalizeArgs`, and tests pinning the unvalidated-option behavior and per-session suppression.
