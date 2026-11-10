# diffutils

GNU diffutils 3.10: diff, cmp, diff3, sdiff

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install diffutils
```

| | |
|---|---|
| Version | 3.10 |
| Licence | GPL-3.0-or-later |
| Upstream | - |
| Needs | none |
| Needs tOS build | 619 or newer |
| Size | 141257 bytes (296240 unpacked) |
| SHA-256 of the `.tpkg` | `4182add67b65943ded50dff97da2d0dad2094681c9b8ece1af9dceb82b096208` |

## Commands it adds

| Command | Runs |
|---|---|
| `cmp` | `bin/cmp` |
| `diff` | `bin/diff` |
| `diff3` | `bin/diff3` |
| `sdiff` | `bin/sdiff` |

## Download

The package file (`diffutils-3.10.tpkg`) and the sources it was built from are the assets of the
[v3.10 release](https://github.com/Artfical/tpkg-diffutils/releases/tag/v3.10).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `diffutils-3.10.tar.xz`

Check a download: `sha256sum diffutils-3.10.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0-or-later. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
