# FusionSpace HPR for Scoop

This bucket installs `hpr`, the command line of [FusionSpace HPR](https://hpr.fusionspace.co), an
open-source flight simulator and flight-log analyzer for hobby and high-power rockets, on Windows
(x86-64, and 64-bit ARM from release 0.2).

```powershell
scoop bucket add fusionspace https://github.com/nrdptel/scoop-bucket
scoop install fusionspace/fusionspace-hpr
hpr --version
```

`scoop update fusionspace-hpr` picks up each new release. The manifest downloads the release's
own archive from [the project's releases](https://github.com/nrdptel/fusionspace-eridanus/releases)
and checks it against its SHA-256.

The manifest is written by the project's release workflow from the release's files; don't edit it
by hand. Report problems at
[the project's issues](https://github.com/nrdptel/fusionspace-eridanus/issues).

Licensed under either of [MIT](LICENSE-MIT) or [Apache-2.0](LICENSE-APACHE), at your option.
