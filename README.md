# Arcom Releases

Official release assets for the **Arcom** desktop POS application.

This repository does **not** contain source code. It hosts the compiled,
signed binaries served by the Tauri auto-updater and the manual download
links used by the product website.

## What is here

Each [GitHub Release](https://github.com/SebaAguiar/arcom-releases/releases)
contains:

- Signed binaries per platform (`Arcom_<version>_amd64.deb`, `.rpm`,
  `.AppImage`, `.msi`, `.nsis.exe`, `.dmg`)
- A `.sig` file next to every binary (Ed25519 signature generated with
  `tauri signer`)
- The updater endpoint used by the app:
  `https://api.github.com/repos/SebaAguiar/arcom-releases/releases/latest`

## Report an issue

Encontrá un bug o querés proponer una mejora? Creá un
[issue](https://github.com/SebaAguiar/arcom-releases/issues/new/choose)
seleccionando la plantilla correspondiente (reporte de bug o solicitud de función).
Incluí tu versión de Arcom y sistema operativo para que podamos reproducirlo.

## Source code

The Arcom source code lives in the private repository
[`SebaAguiar/arpos-v2`](https://github.com/SebaAguiar/arpos-v2).

## License

No license applies here: the content of this repository is proprietary
binary distribution of **Arcom**. "Arcom" is a trademark of SebaAguiar.
Redistribution or resale of these binaries is not permitted without
written authorization.

## How to publish a release

See [`docs/PUBLISHING.md`](docs/PUBLISHING.md) for the step-by-step
release workflow.
