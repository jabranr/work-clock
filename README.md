# Work Clock

A macOS menubar app to display time for a different timezone.

> This repository contains the code for the Work Clock website, [work-clock.jabran.dev](https://work-clock.jabran.dev/), and hosts the app's downloadable releases.

## Download

Get the latest `WorkClock.dmg` from the [website](https://work-clock.jabran.dev/) or the [releases page](https://github.com/jabranr/work-clock/releases/latest). Requires macOS 10.13 or later.

Work Clock is not notarized by Apple, so macOS blocks it the first time you open it. To allow it, open **System Settings → Privacy & Security** and click **Open Anyway**, or run:

```sh
xattr -dr com.apple.quarantine "/Applications/WorkClock.app"
```

## Publishing a release

1. Build the DMG from the app repository.
2. Create a release in this repository tagged with the app version (e.g. `v1.2`).
3. Attach the DMG named exactly `WorkClock.dmg`. The website's download button links to `releases/latest/download/WorkClock.dmg`, so the name must not change between releases.

## Local development

```sh
npm install
npm start
```

## License

MIT License

Copyright © 2021–2026 Jabran Rafique
