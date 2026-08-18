# Apple Platform Security Case Studies

Vulnerabilites I've found in *OS systems

| CVE/bug | Summary |
| --- | --- |
| [CVE-2026-39868](./CVE-2026-39868/) | XNU/DTrace memory corruption through malformed lazy DOF sections. Fixed in *OS 26.5.2. |
| [CVE-2026-28827](./CVE-2026-28827/) | macOS sandbox escape through path traversal and unsafe plugin loading in `NetFS.framework`. |
| [CVE-2026-65371](./CVE-2026-65371) | `gRegistryRoot` KVA disclosure through console-security interest notifications. Fixed in *OS 26.6. |
| [CVE-2026-43748](./CVE-2026-43748) | Kernel heap OOB write in the ANE direct path (`ANE_ProgramCheckandPrewireBuffers_gated`) |
| [AppleM2ScalerCSCDriver IOSurface leak](./no-cve/m2scaler-leak-26.5.2/) | IOSurface KVA and MTE-tag disclosure through an unsanitized diagnostic-log payload. Fixed in *OS 26.6; possibly CVE-2026-64709. |
| [dyld4 protected-stack overflow](./no-cve/dyld-bug-jan2026/) | Protected-stack overflow caused by an excessive chained-fixup bind-target count. Silently fixed in *OS 26.2. |


