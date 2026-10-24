# uhf-cores

Pinned builds of libretro cores used by UHF, an Android TV client for RomM. Each release holds one core's
build for `arm64-v8a` and `armeabi-v7a`, unmodified from libretro's buildbot. UHF pins every file by SHA-256
and downloads it at build time.

| Release | Core | Source | Licence |
|---|---|---|---|
| `ppsspp-2026-10-23` | PPSSPP (libretro) | [hrydgard/ppsspp@31e94fc](https://github.com/hrydgard/ppsspp/tree/31e94fcf68e55d4794e436236dfcde10c817c0fb) | GPL-2.0-or-later |

These binaries are redistributed under their own licences. The complete corresponding source for each is at
the commit linked above, built with libretro's buildbot recipe
([libretro/libretro-super](https://github.com/libretro/libretro-super)).
