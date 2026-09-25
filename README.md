# SAP2000 Quad Mesher: public releases

This repository publishes the **public update manifest and binary desktop releases** for SAP2000 Quad Mesher. The development repository and model fixtures remain private.

- [Latest release](https://github.com/leonardobandini/sap2000-quad-mesher-updates/releases/latest): download the installer ZIP and its `.sha256` checksum.
- [`manifest.json`](manifest.json): machine-readable latest version, release page, ZIP URL and publication date. The plugin checks this file asynchronously without requiring a GitHub account.

SAP2000 27 x64 is required. Extract the release ZIP and run `install_plugin.cmd` after closing SAP2000; reopen SAP and use **Tools > Add/Show Plugins** if the menu entry is not already present.
