# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [1.2.0](https://github.com/K3Progetti/multiple-database/compare/v1.1.0...v1.2.0) (2024-03-04)


### Features

* update composer for symfony 7 ([2ff51fe](https://github.com/K3Progetti/multiple-database/commit/2ff51fea52b39455ec02318556d96eda834e8e14))

## 1.1.0 (2024-01-31)


### Bug Fixes

* name multiple ([074d643](https://github.com/K3Progetti/multiple-database/commit/074d643c318b8f2e645150924a7564891ef613dd))

## [0.1.1]
### Added
- Project cleanup

## [0.1]
### Added
- Initial support for configuration files
- Initial override of [DoctrineMigrationsBundle](https://github.com/doctrine/DoctrineMigrationsBundle) commands
  - Ability to execute migrations commands to all entity managers, or filtered by the option `--em=default`
  - Supported command `doctrine:migrations:diff`
  - Supported command `doctrine:migrations:migrate`
  - Supported command `doctrine:migrations:version`