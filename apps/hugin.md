---
layout: app

permalink: /hugin/
description: Stitch photographs together

icons:
  - hugin/icons/48x48/hugin.png

screenshots:
  - hugin/screenshot.png

authors:
  - name: aferrero2707
    url: https://github.com/aferrero2707

links:
  - type: GitHub
    url: aferrero2707/hugin-appimage
  - type: Download
    url: https://github.com/aferrero2707/hugin-appimage/releases

desktop:
  Desktop Entry:
    Name: Hugin Panorama Creator
    Name[cs]: Hugin pro skládání panoramat
    Name[de]: Hugin - Panorama-Editor
    Name[fr]: Hugin - Créateur de panoramas
    Name[it]: Hugin - Assemblatore di panorami
    Name[ru]: Сшиватель панорам Hugin
    Name[sk]: Hugin pre skladanie panorám
    Name[hu]: Hugin panoráma készítő
    Comment: Stitch photographs together
    Comment[cs]: Skládání panoramatických snímků
    Comment[de]: Erzeugt Panoramabildern aus mehreren Einzelbildern.
    Comment[fr]: Assembler des photographies
    Comment[it]: Assembla fotografie
    Comment[ru]: Сшивка панорам из отдельных фотографий
    Comment[sk]: Skladanie panoramatických snímiek
    Comment[hu]: Fényképek összefűzése egymással
    GenericName: Panorama stitcher
    GenericName[de]: Panorama Stitcher
    GenericName[fr]: Assemblage de panoramas
    GenericName[it]: Crea dei panorami
    GenericName[cs]: Nástroj pro skládání panoramat
    GenericName[ru]: Сшиватель панорам
    GenericName[sk]: Nástroj pre skladanie panorám
    GenericName[hu]: Panoráma összefűző
    Categories: Graphics
    Exec: hugin.wrapper %f
    Icon: hugin
    StartupNotify: false
    Terminal: false
    Type: Application
    MimeType: application/x-ptoptimizer-script
    X-AppImage-Version: git-20180929
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
---
