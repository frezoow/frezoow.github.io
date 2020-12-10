---
layout: post
title: debian10 complete uninstall gnome desktop
categories: debian
tags: [kde, debian, command]
---

> This article describes how to remove the Gnome desktop environment from a Debian install.

```code
    # sudo apt-get autoremove gdm3

    # sudo apt-get autoremove --purge gnome*

    # systemctl reboot
```
