# Changelog

Format: [Keep a Changelog](https://keepachangelog.com/). Release stages: research → alpha → beta → stable.

## [Unreleased]
### Changed
- Scope set to one kext, **RyzentoshCPU.kext**, per the owner's layout decision (2026-11-27). It absorbs SMCProcessorAMD (as VirtualSMC CPU sensor keys), AppleMCEReporterDisabler (as the AppleMCEReporter-blocking personality) and the AMD-V backend for Hypervisor.framework (starting from RyzenHV, MIT). The AMD_Vanilla kernel patches stay in config.plist until this kext can replace some of them.
- README, BRIEF and CLAUDE.md scope lines updated to match.

### Added
- Repository created from the Ryzentosh skeleton (2026-11-27).
