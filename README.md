# ALTHOM Publisher Releases

This repository holds release files of ALTHOM Publisher only: the signed update
lists (release `feed`), the installers (releases `app-<version>`) and the
encrypted layout packs (releases `layouts-<date>`). It holds no code.

The application checks the update lists' Ed25519 signature and each file's
SHA-256 before it uses them. A layout pack is useless without a license for
that layout.
