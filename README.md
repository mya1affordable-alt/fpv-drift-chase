# FPV Drift Chase

A Lifted Media game for Android. Fly a 5" FPV drone with your RC radio and chase drift cars to film them.

Builds only: this repo holds no source code. Downloads are on the [Releases](../../releases) page.

## Android (APK)

1. Download `FPV-Drift-Chase-<version>-test.apk` from the latest release on your phone.
2. Open it and allow installs from that app when Android asks.
3. Plug in your radio over USB-OTG (EdgeTX/OpenTX USB joystick mode). Set it up with **RADIO** on the main menu.

Test build: debug-signed, so Android may warn that it's from an unknown developer.

## Browser

`FPV-Drift-Chase-<version>-web.zip` is a WebGL build: unzip it and serve the folder over HTTP
(for example `python -m http.server`), then open `index.html`. The browser version has no drone or car engine sound yet.

## Maps

- **Circuit**: a procedural track.
- **Drift Mansion**: built from public USGS imagery and elevation data. The track name and logo are used with permission.

## Credits

Third-party models, music and sounds are listed in [CREDITS.txt](CREDITS.txt), with their licenses
(CC BY, CC BY 3.0, Sketchfab Standard, SIL OFL). No real car-brand logos are used.
