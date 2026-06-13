# DreamCity updater

This directory publishes the DreamCity runtime used by `DreamLauncher.exe`.

- Update heads and manifests are committed under `update/`.
- Runtime objects are attached to the GitHub release tagged `runtime-v1`.
- Generated logs, crash dumps, debug symbols, backups and local caches are excluded.
- GTA V installation files are never modified or uploaded.

Run `publish.ps1` from this directory after building the release runtime.
