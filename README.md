# Audel

Audel is a desktop music player for Windows focused on local music libraries,
manual track ordering, playlists, downloads, and a customizable player panel.

## Download

- [Download the latest Audel release](https://github.com/DigitalGl/Audel/releases/latest)
- [Download Audel 1.1.4 installer](https://github.com/DigitalGl/Audel/releases/download/v1.1.4/Audel-Setup-1.1.4.exe)

Install `Audel-Setup-1.1.4.exe` once manually. Future versions can be delivered
through GitHub Releases auto-update.

## Run From Source

```powershell
npm install
npm start
```

## Build Installer

```powershell
npm run dist -- --publish never
```

The Windows installer is created in the `release` folder.
