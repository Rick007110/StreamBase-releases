# StreamBase downloads

Release APKs of **StreamBase**, an Android app for tracking the movies and series you want to
watch, are watching and have watched. The source code is private; this repository only holds the
downloads.

## Install

1. Open the [latest release](https://github.com/Rick007110/StreamBase-releases/releases/latest).
2. Download `StreamBase-<version>.apk` on your Android phone (Android 8.0 or newer) and open it.
3. Allow installing from that app when Android asks.

After that, StreamBase checks for new versions itself and offers to update in the app.

## What's here

- `StreamBase-<version>.apk`: the app, signed with the same key for every release.
- `update.json`: read by the in-app updater (latest version, changelog, download link). Only
  stable releases carry it, so pre-releases are never offered automatically.

Metadata and images in the app are provided by TMDB. StreamBase uses the TMDB API but is not
endorsed or certified by TMDB.
