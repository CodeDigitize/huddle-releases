# Huddle — desktop app

Installers for the Huddle desktop client. Download the latest release from the
[Releases](https://github.com/CodeDigitize/huddle-releases/releases/latest) page:

| Platform | File |
| --- | --- |
| macOS (Apple Silicon, M1/M2/M3/M4) | `Huddle-<version>-mac-arm64.dmg` |
| macOS (Intel) | `Huddle-<version>-mac-x64.dmg` |
| Windows (64-bit) | `Huddle-Setup-<version>.exe` |

## macOS first launch

The app is not notarized yet, so macOS may say it is damaged or from an
unidentified developer. Either right-click the app → **Open**, or run once:

```
xattr -cr "/Applications/Huddle.app"
```

## Updates

The app checks this repository for new releases and offers to install them.
