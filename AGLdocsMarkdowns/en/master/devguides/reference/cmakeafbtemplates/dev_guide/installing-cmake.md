---
edit_link: ''
title: Installing CMake Templates
origin_url: >-
  https://git.automotivelinux.org/src/cmake-apps-module/plain/docs/dev_guide/installing-cmake.md?h=master
---

<!-- WARNING: This file is generated by fetch_docs.js using /home/boron/Documents/AGL/docs-webtemplate/site/_data/tocs/devguides/master/cmake-apps-module-guides-devguides-book.yml -->

# Installing CMake Templates

You can install CMake templates on your native Linux system.

In order to use the templates, you need to install them as
a CMake module.
On your native Linux system, use your distribution's package manager.
See the
"[Prerequisites](../../2-download-packages.html)"
section for how to install packages using your distribution's package
manager.
Be sure to use the following with you install the packages:

```bash
export DISTRO="xUbuntu_16.10"
export REVISION=Master
```

**NOTE:** In order to use the CMake templates, you must be using the
AGL Guppy release.
You cannot use prior releases.

## Installing on Debian or Ubuntu

Use the following command to install AGL's CMake Application Module
on a native Debian or Ubuntu system:

```bash
sudo apt-get install agl-cmake-apps-module-bin
```

## Installing on OpenSUSE

Use the following command to install AGL's CMake Application Module
on a native OpenSUSE system:

```bash
sudo zypper install agl-cmake-apps-module
```

## Installing on Fedora

Use the following command to install AGL's CMake Application Module
on a native Fedora system:

```bash
sudo dnf install agl-cmake-apps-module
```


