# Arcon Releases

Official release assets for the **Arcon** desktop POS application.

This repository does **not** contain source code. It hosts the compiled,
signed binaries served by the Tauri auto-updater and the manual download
links used by the product website.

## What is here

Each [GitHub Release](https://github.com/SebaAguiar/arcon-releases/releases)
contains:

- Signed binaries per platform (`Arcon_<version>_amd64.deb`, `.rpm`,
  `.AppImage`, `.msi`, `.nsis.exe`, `.dmg`)
- A `.sig` file next to every binary (Ed25519 signature generated with
  `tauri signer`)
- The updater endpoint used by the app:
  `https://api.github.com/repos/SebaAguiar/arcon-releases/releases/latest`

## Source code

The Arcon source code lives in the private repository
[`SebaAguiar/arpos-v2`](https://github.com/SebaAguiar/arpos-v2).

## License

No license applies here: the content of this repository is proprietary
binary distribution of **Arcon**. "Arcon" is a trademark of SebaAguiar.
Redistribution or resale of these binaries is not permitted without
written authorization.

## How to publish a release

See [`docs/PUBLISHING.md`](docs/PUBLISHING.md) for the step-by-step
release workflow.
