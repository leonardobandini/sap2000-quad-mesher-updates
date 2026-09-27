# SAP2000 Quad Mesher: public beta

This repository provides the **public update manifest and one current downloadable release** of SAP2000 Quad Mesher. Builds up to v1.0.78 were for development and testing. Starting with v1.0.79, the plugin is offered to users as an **educational beta**: it demonstrates practical ways to connect third-party software to SAP2000 to improve a workflow. Future features and optimizations will reflect users' requests and the author's ideas. The development repository and model fixtures remain private.

- [Latest release](https://github.com/leonardobandini/sap2000-quad-mesher-updates/releases/latest): download the current ZIP, matching source and checksums.
- [`manifest.json`](manifest.json): machine-readable latest version, release page, ZIP URL and publication date. The plugin checks this file asynchronously without requiring a GitHub account.
- [`source-archive` branch](https://github.com/leonardobandini/sap2000-quad-mesher-updates/tree/source-archive): permanent corresponding source for older GPL builds, even after their binary release pages have been removed.

SAP2000 27 x64 is required. Extract the release ZIP and run `install_plugin.cmd` after closing SAP2000; reopen SAP and use **Tools > Add/Show Plugins** if the menu entry is not already present.
