# Homebrew Tap

Homebrew tap for Sangwon Lee's macOS apps.

## Install DiskAtlas

After the first DiskAtlas GitHub Release is published, install it with:

```sh
brew tap sangwonl/tap
brew install --cask sangwonl/tap/diskatlas
```

The DiskAtlas release workflow updates `Casks/diskatlas.rb` with each release's
version, download URL, and SHA-256 checksum.

## Adding another app

Add one cask file per app under `Casks/`. Configure that app's release workflow
to update its cask after publishing its GitHub Release.
