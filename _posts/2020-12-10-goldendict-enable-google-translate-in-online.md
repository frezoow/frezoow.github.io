---
layout: post
title: "Goldendict enable google translate"
categories: goldendict
tags: [dict, debian]
---

Goldendict enable google translate

> system: debian 10;gdict version: offical.

## Installing pip for Python 3

Perform the following steps as a user with sudo privileges to install Pip for Python 3 on Debian 10:

1. Start by updating the package list:

    ```sudo apt update```

2. Install pip for Python 3 and all of its dependencies with the following command:

    ```sudo apt install python3-pip```

    Print the pip3 version to verify the installation:

    ```pip3 --version```

    The version number may be different, but it will look something like the one below:
    > output pip 18.1 from /usr/lib/python3/dist-packages/pip (python 3.7)
    > from !(how-to-install-pip-on-debian-10)<https://linuxize.com/post/how-to-install-pip-on-debian-10/>

## used

> download file from github, link<https://github.com/xinebf/google-translate-for-goldendict>.

GoldenDict - 编辑 - 字典 - 字典来源 - 程式

类型: html

名称: Google Translate

命令行: python3 H:/PathTo/googletranslate.py zh-CN %GDWORD%

图示: H:/PathTo/google_translate.png
