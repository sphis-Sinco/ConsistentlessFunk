# Changelog

All notable changes to this project will be documented in this file.

The format is BASED on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0] (11/23/2024)
Based of P-Slice 2.1
### Changed
- Engine now checks the [SincoEngine Github](https://github.com/sphis-Sinco/SincoEngine) for an Outdated version
- Replaced every instance of `pSliceVersion` with `sincoVersion`
- Application Icons (from purple to green) (This is temporary)
- Title text to include ME! (sinco) in the beginning with the poeple who made it
- Save File
- Version Text in `MainMenuState`
### Added
- `sincoVersion` variable to `MainMenuState` - Sinco Engine Version
- VScode recommendations
- `.sinco` folder (for stuff related to THIS engine)
- Sinco Engine Credit tab
- Sinco Engine Version to `MainMenuState`
### Removed
- `openfl.display.Shader` traces in Debug Builds
### Fixed
- Results music playing when it shouldnt