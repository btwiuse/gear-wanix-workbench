# GearShell Wanix Workbench Assets

This repository packages the static files required by the Wanix `<wanix-workbench>` element:

- Code - OSS web workbench assets under `code/`
- GearShell's Wanix workbench extension under `dist/`
- Extension manifest files at the repository root

GearShell consumes this repository as the `wanix-workbench` submodule and serves it at `/wanix-workbench/`. The assets are built from the `workbench/` directory in [Wanix](https://github.com/tractordev/wanix).

To refresh the bundle, build Wanix's workbench, replace `code/`, `dist/`, `package.json`, and `package.nls.json`, then commit the resulting static artifact update here.
