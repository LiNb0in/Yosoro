<p align="center">
  <img src="./app/views/assets/images/logo.png" width="200"/>
  <h3 align="center">Yosoro</h3>
  <p align="center">Beautiful Cloud Drive Markdown NoteBook Desktop App</p>
  <p align="center">
    <img src="https://img.shields.io/badge/platform-masOS%20%7C%20Linux%20%7C%20Windows-lightgrey.svg" />
  </p>
  <p align="center">
    <img src="https://img.shields.io/github/release/iceend/yosoro.svg" />
    <img src="https://travis-ci.org/IceEnd/Yosoro.svg?branch=master">
    <img src="https://img.shields.io/github/license/IceEnd/Yosoro.svg" />
  </p>
  <p align="center">
    <img src="https://img.shields.io/github/downloads/IceEnd/Yosoro/total.svg">
  </p>
</p>

## Download

The latest version of Yosoro for macOS, linux and Windows is available [here](https://github.com/IceEnd/Yosoro/releases).

**macOS 10.9+, Windows 7+ & Linux are supported.**

## Features

- Create notebook & Write note
- Support Markdown syntax
- Delete & Restore
- Synchronize with Cloud Drive(OneDrive is supported)
- Export notes as markdown or html or pdf
- Update Notification

You can read the [CHANGELOG](./CHANGELOG.md) to get more information.

## Demo

### Write Notes

![write](https://t1.picb.cc/uploads/2018/05/13/2vBxK7.gif)

### File Syncing

![sync](https://t1.picb.cc/uploads/2018/05/13/2vBRbs.gif)

## Screenshots

### macOS

![screenshot-osx](https://s1.ax1x.com/2018/05/13/CDVMcD.png)

### Windows

![screenshot-windows](https://s1.ax1x.com/2018/05/13/CDZC5t.png)

### linux

![screenshot-linux](https://s1.ax1x.com/2018/05/13/CDZF8f.png)

## Quick Start

### Install

```shell
yarn
```

### Dev Tools Extension

```shell
cp ./config/devconfig.example.json ./config/devconfig.json
```

### Run Main Process

```shell
npm run dev:main
```

### Run Renderer Process

```shell
npm run dev:renderer
```

### Build

```shell
npm run build:all|main|renderer
```

### Package

```
npm run packager:mac|win|win:64|linux
```

## License

GPL-3.0 © [Alchemy](./LICENSE)
