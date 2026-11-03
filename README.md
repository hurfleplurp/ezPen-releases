# ezPen

A native Windows whiteboard, pressure-sensitive sketchbook and transparent
desktop annotation layer.

Draw with six distinct instruments, paste reference images, explore and replay
your drawing history, or annotate the applications on your desktop.

## Downloads

- **[Download ezPen for Windows](https://github.com/hurfleplurp/ezPen-releases/releases/latest/download/ezPen.exe)**
- [Download the application and technology overview](https://github.com/hurfleplurp/ezPen-releases/releases/latest/download/EZPEN-OVERVIEW.md)
- [Download the executable SHA256 checksum](https://github.com/hurfleplurp/ezPen-releases/releases/latest/download/SHA256SUMS.txt)
- [Latest release and notes](https://github.com/hurfleplurp/ezPen-releases/releases/latest)
- [All releases](https://github.com/hurfleplurp/ezPen-releases/releases)

**Requirements:** 64-bit Windows 10 or 11 and an OpenGL 3.3-capable graphics
driver. Download the executable and run it; no separate runtime installation
is required. Mouse and pressure-sensitive drawing tablets are supported.

Windows may display a reputation warning for a newly downloaded executable.
Only obtain builds from these official releases.

## About this repository

This is the public distribution repository for ezPen, not its source repository.
Builds and documentation are attached to GitHub Releases.

The download links above always point to assets on the latest stable release.
They can be used directly by a website; GitHub redirects the request to the
current version. Version-specific links remain available on each release page.

## Publishing updates

Create a new release with a unique version tag, attach the new build and
documentation, and mark it as the latest stable release. Keep these filenames
unchanged so website links continue to work:

- `ezPen.exe`
- `EZPEN-OVERVIEW.md`
- `SHA256SUMS.txt` (SHA256 of `ezPen.exe`)

Upload all assets to a draft before publishing. Do not mark the release as a
prerelease if it should be served by the stable download links.
