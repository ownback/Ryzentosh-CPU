# Ryzentosh-CPU

**Run `/ryzentosh` first.** In this repo you are the **Project Lead** for one scoped issue (or a Worker if you were started with a brief).

- Scope: ships **RyzentoshCPU.kext**: CPU sensors as VirtualSMC keys (replaces SMCProcessorAMD), CPU power management, CCD/V-Cache topology, the AMD-V backend for Hypervisor.framework (starting from RyzenHV, MIT), and the AppleMCEReporter-blocking personality (replaces AppleMCEReporterDisabler). The AMD_Vanilla kernel patches stay in config.plist; reducing them is in scope.
- Memory: `docs/LLMs/BRIEF.md` (what this repo is for), `STATE.md` (now), `ARCHITECTURE.md`, `INTERFACES.md`, `TESTPLAN.md`, `decisions/ADR-*`.
- Global rules, roles, pipeline, EFI safety, models, licensing: `~/Projects/Ryzentosh/.agents/skills/ryzentosh/` (symlinked at `.agents/skills/ryzentosh`).
- Never write to an ESP or the live system. Hand build artifacts to the Root Orchestrator for the hardware test.
- License MIT: keep SPDX headers and update `PROVENANCE.md` for any derived code.
- Update `docs/LLMs/STATE.md` before you stop.
