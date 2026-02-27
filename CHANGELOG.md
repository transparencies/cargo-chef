# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.74](https://github.com/transparencies/cargo-chef/compare/v0.1.73...v0.1.74) - 2026-02-27

### Other

- Only build Docker images on a schedule and on tags
- Don't build twice for PRs
- Modernize publishing pipeline
- Minimize read API calls ([#329](https://github.com/transparencies/cargo-chef/pull/329))
- Fix Docker publishing workflow ([#328](https://github.com/transparencies/cargo-chef/pull/328))
- Start testing caching behaviour with real builds ([#327](https://github.com/transparencies/cargo-chef/pull/327))
- Use latest debian stablee release, trixie.
