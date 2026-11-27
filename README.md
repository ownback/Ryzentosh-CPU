# Ryzentosh-CPU

One repo ships one kext: **RyzentoshCPU.kext**. It covers:

- CPU sensors as VirtualSMC keys (replaces SMCProcessorAMD)
- CPU power management
- CCD/V-Cache topology
- The AMD-V backend for Hypervisor.framework (starting from RyzenHV, MIT)
- The AppleMCEReporter-blocking personality (replaces AppleMCEReporterDisabler)

The AMD_Vanilla kernel patches stay in `config.plist` (Ryzentosh-EFI). Reducing them is in scope.

Part of [Ryzentosh](https://github.com/ownback/Ryzentosh): macOS Tahoe on an AMD PC, built to behave like a Mac Apple designed and
supports. Written by AI agents. Apple is not involved in this project.

**Status:** research. Nothing here is ready to install yet. See [docs/Humans](docs/Humans/) and the
[compatibility matrix](https://github.com/ownback/Ryzentosh/blob/main/docs/Hardware/COMPATIBILITY_MATRIX.md).

**Releases:** `RyzentoshCPU.kext`.

## Reference hardware
AMD Ryzen 9 7900X3D · Radeon RX 7900 XTX (XFX) · ASUS ROG STRIX B650E-I · macOS 26.7.1 (25G241) · OpenCore 1.0.8.

## Contributing
See [CONTRIBUTING.md](https://github.com/ownback/Ryzentosh/blob/main/CONTRIBUTING.md). AI agents: read [AGENTS.md](AGENTS.md).

License: MIT. Third-party code and its origins are listed in [PROVENANCE.md](PROVENANCE.md).
