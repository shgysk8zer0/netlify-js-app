# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
<!-- markdownlint-disable -->
## [Unreleased]

## [v3.1.0] - 2023-06-12

### Changed
- Update `@shgysk8zer0/rollup-import`

## [v3.0.5] - 2023-06-12

### Changed
- Use `@shgysk8zer0/css-utils` instead of `postcss` & `stylelint`
- Use `@shgysk8zer0/js-utils` instead of `rollup` & `eslint`

### Fixed
- Update GitHub Release Action with correct permissions
- Prevent `.nvmrc` from being publishing

## [v3.0.4] - 2023-05-13

### Changed
- Update `@shgysk8zer0/rollup-import` to v1.0.0

## [v3.0.3] - 2023-05-12

### Changed
- Update `@shgysk8zer0/rollup-import`

## [v3.0.2] - 2023-05-11

### Fixed
- Missed bumping npm version, but tag created & pushed

## [v3.0.1] - 2023-05-11

### Removed
- `@rollup/plugin-babel`

## [v3.0.0] - 2023-05-11

### Removed
- Remove deprecated `rollup-plugin-terser`

### Fixed
- Update `rollup-plugin-terser` -> `@rollup/plugin-terser`

## [v2.1.4] - 2023-05-11

### Fixed
- Update `@shgysk8zer0/rollup-import` (hopefully won't cause conflicts anymore)

### Changed
- Update NPM ignore to omit unnecessary files

## [v2.1.3] - 2023-05-11

### Added
- `@shgysk8zer0/rollup-import` to handle importmaps (later all imports)

## [v2.1.2] - 2023-05-02

### Added
- Add PostCSS plugin for CSS nesting
- Add nesting and `:focus-within` to tests

## [v2.1.1] - 2023-01-09

### Fixed
- Fix various issues with node update

## [v2.1.0] - 2023-01-09

### Changed
- Update to node v18.13.0
- Misc dependency updates

## [v2.0.0] - 2022-03-21

### Added
- Tests for `lint` & `build` scripts

### Changed
- Update to using node v16.14.2
- Updated numerous dependencies

## [v1.1.0] - 2021-04-15

### Added
- `@babel/core` and `@rollup/plugin-babel`

### Changed
- Various package updates

### Removed
- `postcss-cssnext` and `postcss-custom-properties`

## [v1.0.12]

### Removed
- Comment out publishing to GitHub packages until publishing to two registries is resolved

## [v1.0.10]

### Changed
- More work trying to get workflows to work correctly
- Skip a few tags getting `npm publish` to work correctly

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
