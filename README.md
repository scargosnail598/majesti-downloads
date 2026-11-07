# Majesti downloads

Install [Android 0.2.38 — updater migration](https://github.com/scargosnail598/majesti-downloads/releases/tag/clients-20261107-002) manually once over the original app. This version uses the independent signed Android channel for subsequent in-app updates. The [legacy release channel](https://github.com/scargosnail598/majesti-downloads/releases/latest) remains separate for older clients and Windows.

| Client | Current download |
| --- | --- |
| Android 13 or later | [Majesti Android 0.2.38 APK — one-time manual migration](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261107-002/MajestiLab-0.2.38.apk) |
| Windows x64 (experimental) | [Majesti Windows 0.5.6 EXE](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261105-002/MajestiWindows-0.5.6-win-x64.exe) |

Install the Android APK over an existing Majesti installation when Android accepts the matching signing identity. Do not uninstall just to update. Windows remains experimental and is not Authenticode-signed.

Android 0.2.37 adds a free-hour reminder, a reconnect option after 45 connected minutes confirmed by the server, and a dismissible full-screen presentation of the existing AADS unit after successful foreground connections. Install 0.2.38 manually once to enable the new signed Android updater. Older Android installations still see the legacy 0.2.36 channel until manually migrated. Windows remains on 0.5.6. Existing service-channel versions also need manual installation. GitHub hosts downloads; sign-in and VPN connections still use the Majesti service.

[Android 0.2.38 SHA256SUMS](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261107-002/SHA256SUMS) covers its APK and corresponding source. [Signed-channel checksums](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261105-002/SHA256SUMS) cover the retained Android 0.2.36 and Windows 0.5.6 files. Automatic updaters continue to verify the existing signed release information.

## Android source and notices

[Corresponding Android source for 0.2.38](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261107-002/MajestiAndroid-source-0.2.38.tar.gz) includes build instructions, engine source, local patches and license notices. See [NOTICE.md](NOTICE.md).

GitHub's automatic “Source code” ZIP/TAR contains this downloads repository. Use the separately named Android source archive for the app's corresponding source.

Do not put passwords, account tokens, private activation files or identifying diagnostic logs in public issues.
