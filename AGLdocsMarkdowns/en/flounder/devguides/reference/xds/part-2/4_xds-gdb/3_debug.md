---
edit_link: ''
title: Debugging
origin_url: >-
  https://git.automotivelinux.org/src/xds/xds-docs/plain/docs/part-2/4_xds-gdb/3_debug.md?h=flounder
---

<!-- WARNING: This file is generated by fetch_docs.js using /home/boron/Documents/AGL/docs-webtemplate/site/_data/tocs/devguides/flounder/xds-docs-guides-flounder-devguides-book.yml -->

# Debugging

## XDS gdb architecture

This tool is written in *Go*.

```bash
|
+-- bin/                # where xds-gdb binary will be built
|
+-- gdb-XXX.go          # xds-gdb Go sources
|
+-- conf.d/             # Linux configuration and startup files (systemd user service)
|
+-- glide.yaml          # Go package dependency file
|
+-- LICENSE             # XDS gdb license
|
+-- main.go             # main entry point (Go)
|
+-- Makefile            # makefile including
|
+-- README.md           # readme
|
+-- scripts/            # hold various scripts used for installation
|
+-- vendor/             # temporary directory to hold Go dependencies packages
```

## Debug

Install first [Visual Studio Code](https://code.visualstudio.com/) and
[Go plugin](https://marketplace.visualstudio.com/items?itemName=lukehoban.Go)
(`ext install lukehoban.Go`)

Visual Studio Code launcher settings can be found into `.vscode/launch.json`.

Please follow instructions of xds-agent [debugging chapter](../2_xds-agent/4_debug.html#debug-xds-agent-go-code),
knowing that you execute these same instructions in `xds-gdb` repo, in other words
by replacing *xds-agent* references by *xds-gdb*.
