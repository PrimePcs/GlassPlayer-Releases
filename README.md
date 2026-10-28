# GlassPlayer

Windows installers and in-app updates for this customized GlassPlayer build.

## Install

Download **GlassPlayerSetup.exe** from the [latest release](https://github.com/PrimePcs/GlassPlayer-Releases/releases/latest). Updates keep your playlists, uploaded covers, history, Spotify configuration, and playback settings.

## Updates

GlassPlayer checks for updates when it starts. You can also open **Settings → Updates → Check now**. When a newer version is available, choose **Update** to download the installer, verify its SHA-256 checksum, and restart to install.

The public update feed is [update-manifest.json](https://raw.githubusercontent.com/PrimePcs/GlassPlayer-Releases/main/update-manifest.json). The feed lists the version, exact installer URL, checksum, and release notes. Each release includes the installer and matching source archive.

## Features

- Saved playlists with custom images and rounded covers
- Recent songs on startup
- EQ graph and presets for local and YouTube Music playback
- Loudness normalization for local and YouTube Music playback
- Dark Liquid Glass appearance and transparent app icon
- Spotify playback and automatic updates

Spotify audio uses Spotify's own playback pipeline; GlassPlayer's EQ and normalizer apply to local and YouTube Music audio.

## Source and license

Based on [Jonzu00/GlassPlayer](https://github.com/Jonzu00/GlassPlayer), with customized UI, playlist management, playback settings, and updater changes. The application is distributed under **GPL-3.0**. Download the matching **GlassPlayer-Source.zip** release asset for the corresponding source code and build instructions. Third-party components retain their own licenses.
