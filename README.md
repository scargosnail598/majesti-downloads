# Majesti downloads

Download Majesti clients from the [latest release](https://github.com/scargosnail598/majesti-downloads/releases/latest).

| Client | Current download |
| --- | --- |
| Android 13 or later | [Majesti Android 0.2.36 APK](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261105-002/MajestiLab-0.2.36.apk) |
| Windows x64 (experimental) | [Majesti Windows 0.5.6 EXE](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261105-002/MajestiWindows-0.5.6-win-x64.exe) |

Install the Android APK over an existing Majesti installation when Android accepts the matching signing identity. Do not uninstall just to update. Windows remains experimental and is not Authenticode-signed.

Existing versions that download updates from the previous service channel need manual installation of this first GitHub-capable version. Later update checks use the signed GitHub channel. GitHub hosts downloads; sign-in and VPN connections still use the Majesti service.

[SHA256SUMS](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261105-002/SHA256SUMS) lists checksums for the client files and corresponding Android source. The app updaters also verify signed release information.

## Android source and notices

[Corresponding Android source for 0.2.36](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261105-002/MajestiAndroid-source-0.2.36.tar.gz) includes build instructions, engine source, local patches and license notices. See [NOTICE.md](NOTICE.md).

GitHub's automatic “Source code” ZIP/TAR contains this downloads repository. Use the separately named Android source archive for the app's corresponding source.

Do not put passwords, account tokens, private activation files or identifying diagnostic logs in public issues.
