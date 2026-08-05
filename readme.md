# Apple Platform Security Case Studies

Reverse-engineering write-ups and PoCs for iOS, macOS, and other Apple platforms.

| Case study | Summary |
| --- | --- |
| [CVE-2026-39868](./CVE-2026-39868/) | XNU/DTrace memory corruption through malformed lazy DOF sections. Fixed in *OS 26.5.2. |
| [CVE-2026-28827](./CVE-2026-28827/) | macOS sandbox escape through path traversal and unsafe plugin loading in `NetFS.framework`. |
| [AppleM2ScalerCSCDriver IOSurface leak](./m2scaler-leak-26.5.2/) | IOSurface KVA and MTE-tag disclosure through an unsanitized diagnostic-log payload. Fixed in *OS 26.6; possibly CVE-2026-64709. |
| [IOService address leak](./io-service-leak-26.6/) | `gRegistryRoot` KVA disclosure through console-security interest notifications. Fixed in *OS 26.6. |
| [dyld4 protected-stack overflow](./dyld-bug-jan2026/) | Protected-stack overflow caused by an excessive chained-fixup bind-target count. Silently fixed in *OS 26.2. |
