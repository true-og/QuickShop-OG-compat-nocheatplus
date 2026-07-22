# QuickShop-OG NoCheatPlus Compatibility

GPLv3 compatibility extension for QuickShop-OG and NoCheatPlus.

QuickShop-OG performs temporary fake protection checks while players create or use shops. This extension exempts the player from NoCheatPlus only for the duration of those checks, preventing false anti-cheat violations.

## Requirements

- Java 17
- QuickShop-OG, based on the 5.2.0.7 API
- NoCheatPlus

## Build

Run `./gradlew build` from this repository. The resulting plugin JAR is `build/libs/QuickShop-OG-compat-nocheatplus-5.9.jar`.

## Install

Place the built JAR in the server's `plugins/` directory beside `QuickShop-OG.jar` and the NoCheatPlus JAR. Restart the server; do not place this JAR in `plugins/QuickShop-OG/`.

## License

GPL-3.0-only. See [LICENSE](LICENSE).
