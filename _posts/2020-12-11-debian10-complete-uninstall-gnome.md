---
layout: post
title: debian10 complete uninstall gnome desktop
categories: debian
tags: [kde, debian, command]
---

> This article describes how to remove the Gnome desktop environment from a Debian install.

    1. step

```# sudo apt-get autoremove gdm3```

    2. step

```# sudo apt-get autoremove --purge gnome*```

    3. step

```systemctl reboot```
