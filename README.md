# xz

XZ Utils 5.8.4: xz, unxz, xzcat (compress and decompress .xz and .lzma; 64-bit tOS)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install xz
```

| | |
|---|---|
| Version | 5.8.4 |
| Licence | 0BSD; GPL-2.0+ (tools); LGPL-2.1+ |
| Upstream | https://tukaani.org/xz/ |
| Needs | none |
| Needs tOS build | 612 or newer |
| Size | 133008 bytes (265096 unpacked) |
| SHA-256 of the `.tpkg` | `069e13bbf8ce95a2cc2d0d3d7629de0e83c2c7b0f5cd61593a914a50a2a2fce7` |

## Commands it adds

| Command | Runs |
|---|---|
| `xz` | `bin/xz` |
| `unxz` | `bin/xz -d` |
| `xzcat` | `bin/xz -dc` |

## Download

The package file (`xz-5.8.4.tpkg`) and the sources it was built from are the assets of the
[v5.8.4 release](https://github.com/Artfical/tpkg-xz/releases/tag/v5.8.4).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `xz-5.8.4.tar.xz`

Check a download: `sha256sum xz-5.8.4.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: 0BSD; GPL-2.0+ (tools); LGPL-2.1+. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
