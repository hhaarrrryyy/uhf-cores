# uhf-cores

Pinned builds used by UHF, an Android TV client for RomM. Each core release holds one libretro core's
build for `arm64-v8a` and `armeabi-v7a`, unmodified from libretro's buildbot. The LibretroDroid release is
UHF's patched build of that library, with its source. UHF pins every file by SHA-256 and downloads it at
build time.

| Release | What | Source | Licence |
|---|---|---|---|
| `ppsspp-2026-10-23` | PPSSPP (libretro core) | [hrydgard/ppsspp@31e94fc](https://github.com/hrydgard/ppsspp/tree/31e94fcf68e55d4794e436236dfcde10c817c0fb) | GPL-2.0-or-later |
| `flycast-2026-10-23` | Flycast (libretro core) | [flyinghead/flycast@6d81b99](https://github.com/flyinghead/flycast/tree/6d81b998169b916ad7d7d6f403f7dc2c18e2aea5) | GPL-2.0-or-later |
| `libretrodroid-0.14.0-uhf2` | LibretroDroid with UHF's two patches (current) | in the release: the patches and the full patched source | GPL-3.0 |
| `libretrodroid-0.14.0-uhf1` | LibretroDroid with UHF's first patch (superseded) | in the release: the patch and the full patched source | GPL-3.0 |

These binaries are redistributed under their own licences. For the cores, the complete corresponding source is
at the commit linked above, built with libretro's buildbot recipe
([libretro/libretro-super](https://github.com/libretro/libretro-super)).
