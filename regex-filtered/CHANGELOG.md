# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.1](https://github.com/masklinn/uap-rust/compare/regex-filtered-v0.2.0...regex-filtered-v0.2.1) - 2026-03-17

### Other

- Don't use an IntSet for the regexps when mapping atoms to regex
- Fix unicode casefolding
- Make sure an alternation with an empty literal doesn't break
- Fix resource exhaustion risk
- Produce better atoms on Concat
- Fix stupid short atoms on repetitions
- Update to edition 2024
- CI compatibility bumps
- Change the bench programs to atoms of size 2
- Make regex-filtered re2 bench easier to run
- Update dependencies
- Update dependencies to latest
- cargo fmt
- Fix for gcc being a dummy
- Implement bespoke cut down IntMap
- Minor styllistic improvements to mapper builing
