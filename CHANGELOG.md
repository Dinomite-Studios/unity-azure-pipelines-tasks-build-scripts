# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.6]

### Added

- Added first version of build script inspired by current Build V3 script

## [1.0.5]

### Changed

- Instead of specifying override paths, clear to null, which should automatically set the internal SDK paths

## [1.0.4]

### Added

- Add debug logs

## [1.0.3]

### Changed

- It appears the -executeMethod command line argument does not detect static entrypoints within a package assembly and requires the script to be in an Editor folder within the assets folder of the project. Implemented new approach to solve this problem

## [1.0.2]

### Fixed

- Fixed missing EditorApplication.Exit(0); call

## [1.0.1]

### Changed

- Instead of using [InitializeOnLoad] for initiazing Android settings, we'll do it via -executeMethod

## [1.0.0]

Initial release