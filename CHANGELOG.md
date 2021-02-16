# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
<!-- markdownlint-disable -->
## [Unreleased]

## [v1.0.7]

### Changed
- More work trying to get workflows to work correctly

## [v1.0.6]

### Changed
- Misc. workflow changes trying to get publishing to GitHub packages to publish
- Use `npm ci` instead of `npm install`
- Combine build and test scripts

## [v1.0.5]

### Changed
- Use Node 14.x

### Fixed
- Use correct registry for GitHub packages and NPM

## [v1.0.4]

### Removed
- Do not upload or download artifacts, as none are created

## [v1.0.3] - 2021-02-16

### Added
- Add pubishing status badge to README

### Changed
- Revert to publishing on tag

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
