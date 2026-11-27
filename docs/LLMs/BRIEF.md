# BRIEF: Ryzentosh-CPU

**Scope:** ships **RyzentoshCPU.kext**: CPU sensors as VirtualSMC keys (replaces SMCProcessorAMD), CPU power management, CCD/V-Cache topology, the AMD-V backend for Hypervisor.framework (starting from RyzenHV, MIT), and the AppleMCEReporter-blocking personality (replaces AppleMCEReporterDisabler). The AMD_Vanilla kernel patches stay in config.plist; reducing them is in scope.

**Release artifact:** `RyzentoshCPU.kext`.

**Depends on:** [Ryzentosh-EFI]

**Parity targets:** see the rows for this project in the control plane's COMPATIBILITY_MATRIX.md.

**Out of scope:** anything another Ryzentosh repo owns (see projects.yaml). In particular: the RX 7900 XTX and Raphael iGPU (Ryzentosh-GPU), Wi-Fi, Bluetooth and AWDL (Ryzentosh-WIRELESS), NVMe, USB port map and RestrictEvents (Ryzentosh-PLATFORM), and the SSDTs (Ryzentosh-ACPI).
