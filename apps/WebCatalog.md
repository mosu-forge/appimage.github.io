---
layout: app

permalink: /WebCatalog/
description: WebCatalog helps you turn any website into desktop app with just one click.
license: MPL-2.0

icons:
  - WebCatalog/icons/128x128/webcatalog.png

screenshots:
  - WebCatalog/screenshot.png

authors:
  - name: webcatalog
    url: https://github.com/webcatalog

links:
  - type: GitHub
    url: webcatalog/webcatalog
  - type: Download
    url: https://github.com/webcatalog/webcatalog/releases

desktop:
  Desktop Entry:
    Name: WebCatalog
    Comment: WebCatalog helps you turn any website into desktop app with just one click.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: webcatalog
    X-AppImage-Version: 12.3.1.223
    X-AppImage-BuildId: 8f251f70-558b-11a8-229d-4f724fc923e9
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MPL-2.0

electron:
    click.
  main: build/electron.js
  repository: https://github.com/webcatalog/webcatalog
  author:
    name: Quang Lam
    email: quang.lam2807@gmail.com
    url: https://twitter.com/quanglam2807
  license: MPL-2.0
  dependencies:
    command-exists: 1.2.2
    electron-is-dev: 0.3.0
    electron-settings: 3.1.4
    electron-updater: 2.21.4
    electron-window-state: 4.1.1
    file-type: 7.6.0
    follow-redirects: 1.4.1
    fs-extra: 5.0.0
    icon-gen: 1.2.0
    is-url: 1.2.4
    jimp: 0.2.28
    read-chunk: 2.1.0
    tmp: 0.0.33
    windows-shortcuts: 0.1.6
    yargs-parser: 9.0.2
  homepage: "./"
  private: true
---
