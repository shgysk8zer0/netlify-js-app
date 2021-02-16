# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
<!-- markdownlint-disable -->
## [Unreleased]

## [v1.0.2] - 2021-02-16

### Changed
- Publish packages on release created instead of tag
- Do not upload entire root directory as artifact

## [v1.0.1]

### Added
- `publish-package.yml` workflow to publish tags to GitHub Packages and NPM

### Changed
- `github-release.yml` workflow has release body refer to `CHANGELOG`

## [v1.0.0] - 2021-02-15

### Added
- Common dependencies
- Super Linter & `npm test` workflows
- ESLint tests
- GitHub package release workflow
- Various config files
<!-- markdownlint-restore -->
