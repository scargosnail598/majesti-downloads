# Majesti downloads

Download Android 0.2.37 from the [manual-download release](https://github.com/scargosnail598/majesti-downloads/releases/tag/android-0.2.37). The existing [signed automatic-update channel](https://github.com/scargosnail598/majesti-downloads/releases/latest) remains available separately.

| Client | Current download |
| --- | --- |
| Android 13 or later | [Majesti Android 0.2.37 APK — manual install](https://github.com/scargosnail598/majesti-downloads/releases/download/android-0.2.37/MajestiLab-0.2.37.apk) |
| Windows x64 (experimental) | [Majesti Windows 0.5.6 EXE](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261105-002/MajestiWindows-0.5.6-win-x64.exe) |

Install the Android APK over an existing Majesti installation when Android accepts the matching signing identity. Do not uninstall just to update. Windows remains experimental and is not Authenticode-signed.

Android 0.2.37 adds a free-hour reminder, a reconnect option after 45 connected minutes confirmed by the server, and a dismissible full-screen presentation of the existing AADS unit after successful foreground connections. This is a manual-install release; automatic update checks continue to advertise Android 0.2.36 and Windows 0.5.6. Existing service-channel versions also need manual installation. GitHub hosts downloads; sign-in and VPN connections still use the Majesti service.

[Android 0.2.37 SHA256SUMS](https://github.com/scargosnail598/majesti-downloads/releases/download/android-0.2.37/SHA256SUMS) covers its APK and corresponding source. [Signed-channel checksums](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261105-002/SHA256SUMS) cover the retained Android 0.2.36 and Windows 0.5.6 files. Automatic updaters continue to verify the existing signed release information.

## Android source and notices

[Corresponding Android source for 0.2.37](https://github.com/scargosnail598/majesti-downloads/releases/download/android-0.2.37/MajestiAndroid-source-0.2.37.tar.gz) includes build instructions, engine source, local patches and license notices. See [NOTICE.md](NOTICE.md).

GitHub's automatic “Source code” ZIP/TAR contains this downloads repository. Use the separately named Android source archive for the app's corresponding source.

Do not put passwords, account tokens, private activation files or identifying diagnostic logs in public issues.
