# Changelog

All Notable changes to `json-api-server` will be documented in this file.

Updates should follow the [Keep a CHANGELOG](http://keepachangelog.com/) principles.

## 0.3.0

### Changed

- Added support for recent Laravel versions.
- Run tests on Travis instead of Shippable

## 0.2.1

### Changed

- Change LICENSE.md to default GitHub contents.

### Fixed

- Bugfix when using the 'all' parameter and the query returns an empty collection.

## 0.2 - 2018-03-12

### Added
- Changed namespace from `Swis\LaravelApi` to `Swis\JsonApi\Server`
- Changed commands from `laravel-api:generate` to `json-api-server:generate`
- Tests for commands
- Tests for BaseApiRepository
- Tests for BaseApiController
- Explanation on how to use laravel/passport

### Deprecated
- laravel-api:generate commands
- Swis\LaravelApi namespace

### Fixed
- README to reflect new changes
- laravel_api.php to reflect new namespace
- Stubs to use the proper namespaces
- Commands to reflect new namespaces
- Improved exception handling
- Repository interface so you can implement it 

### Removed
- Unnecessary packages from composer.json
- PermissionsMiddleware
- Exception renderers
- HasPermissionsChecks


## 0.1 - 2018-02-09

### Added
- Everything, initial release.

