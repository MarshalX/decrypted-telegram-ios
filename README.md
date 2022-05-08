## Decrypted versions of Telegram for iOS

I publish here decrypted versions of Telegram for iOS using my jailbroken device.

### Why?

1. According to 8th step of [Telegram's reproducible builds for iOS](https://core.telegram.org/reproducible-builds#reproducible-builds-for-ios) (official page) we need to get decrypted version by ourselves.

> This step requires a jailbroken device equipped with tools for decrypting apps. We‘d love to make this process more simple but that’s what you get for using Apple tech.

2. I want to be able to compare versions in my [Telegram Crawler](https://github.com/MarshalX/telegram-crawler) and log changes.

### How?

I extract decrypted .ipa files manually using [frida](https://github.com/frida/frida) and [frida-ios-dump](https://github.com/AloneMonkey/frida-ios-dump).

### Where?

I make releases in the "[Releases](https://github.com/MarshalX/decrypted-telegram-ios/releases)" section of this repository. I mark TestFlight's versions using this semantic: `MAJOR.MINOR.?PATCH.BUILD`, for versions from App Store I use this one: `MAJOR.MINOR.?PATCH`.
