# Majesti downloads

Download [Android 0.2.44](https://github.com/scargosnail598/majesti-downloads/releases/tag/clients-20261115-005), or use the signed in-app updater from Android 0.2.38 or later. Earlier versions need one manual installation over the original app. The [legacy release channel](https://github.com/scargosnail598/majesti-downloads/releases/latest) remains separate for older clients and Windows.

| Client | Current download |
| --- | --- |
| Android 13 or later | [Majesti Android 0.2.44 APK](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261115-005/MajestiLab-0.2.44.apk) |
| Windows x64 (experimental) | [Majesti Windows 0.5.6 EXE](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261105-002/MajestiWindows-0.5.6-win-x64.exe) |

Install the Android APK over an existing Majesti installation when Android accepts the matching signing identity. Do not uninstall just to update. Windows remains experimental and is not Authenticode-signed.

Android 0.2.44 signs in with Google and requires membership of @majestivpn for free use. Choose Verify with bot, press Start in @MajestiVPN_bot, use its private Return to Majesti link and confirm your Telegram account in the app. Join the channel and use Check again if needed. Existing Telegram-only users can sign in afresh with Google and explicitly choose Use existing account after proving their Telegram identity; original usage and limits stay on that account. There is no Telegram OIDC login page or in-app advertising. Free-hour reminders, routing and signed updates are preserved. Android 0.2.38 and later can use the signed Android-v2 updater; earlier clients need one manual installation of the current APK. Windows remains on 0.5.6, with its legacy channel unchanged. GitHub hosts downloads; account and VPN connections still use the Majesti service.

[Android 0.2.44 SHA256SUMS](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261115-005/SHA256SUMS) covers its APK and corresponding source. [Signed-channel checksums](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261105-002/SHA256SUMS) cover the retained Android 0.2.36 and Windows 0.5.6 files. Automatic updaters continue to verify the existing signed release information.

## Android source and notices

[Corresponding Android source for 0.2.44](https://github.com/scargosnail598/majesti-downloads/releases/download/clients-20261115-005/MajestiAndroid-source-0.2.44.tar.gz) includes build instructions, engine source, local patches and license notices. See [NOTICE.md](NOTICE.md).

GitHub's automatic “Source code” ZIP/TAR contains this downloads repository. Use the separately named Android source archive for the app's corresponding source.

Do not put passwords, account tokens, private activation files or identifying diagnostic logs in public issues.
