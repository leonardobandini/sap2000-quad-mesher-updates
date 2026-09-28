# SAP2000 Quad Mesher: public beta

This repository provides the **public update manifest and one current downloadable release** of SAP2000 Quad Mesher. Builds up to v1.0.78 were for development and testing. v1.0.79 was the first **educational beta** offered to users; v1.0.80 introduced conforming refined edges and a single FAST table batch, v1.0.81 fixed regular-meshing fallbacks and small circular holes, v1.0.82 added safe cancellation and explicit `m`, `cm`, `mm`, `ft` or `in` length inputs, and v1.0.83 preselected FAST. The current beta **v1.0.84** adds the plugin to the SAP2000 27 Tools menu automatically during installation while retaining other plug-ins; FAST can still be switched off. The project demonstrates practical ways to connect third-party software to SAP2000 to improve a workflow. The development repository and model fixtures remain private.

- [Latest release](https://github.com/leonardobandini/sap2000-quad-mesher-updates/releases/latest): download the current ZIP, matching source and checksums.
- [`manifest.json`](manifest.json): machine-readable latest version, release page, ZIP URL and publication date. The plugin checks this file asynchronously without requiring a GitHub account.
- [`source-archive` branch](https://github.com/leonardobandini/sap2000-quad-mesher-updates/tree/source-archive): permanent corresponding source for older GPL builds, even after their binary release pages have been removed.

SAP2000 27 x64 is required. Extract the release ZIP and run `install_plugin.cmd` after closing SAP2000. Reopen SAP2000 to use the automatically added Tools menu entry; if the installer reports that menu preferences were not initialized, add `SapQuadTransitionPlugin` from **Tools > Add/Show Plugins**.
