# IrisOS package repository

pacman repository `[irisos]` for [IrisOS](https://pantr1x.com) – packages are attached to the [`x86_64` release](../../releases/tag/x86_64).

```ini
[irisos]
SigLevel = Optional TrustAll
Server = https://github.com/pantr1x/irisos-repo/releases/download/$arch
```

IrisOS adds this automatically. Packages are published by `package.sh` in the IrisOS project.
