
# ECVII Releases

This repository houses release version of the Fire Emblem: Thracia 776 mod `Emblem Chronicle VII`.

`.ups` patches should be applied to unmodified, headerless cartridge release versions of Fire Emblem: Thracia 776 (sha1 checksum: 75B504921D08E313FF58150E40121AC701884517).

See the `CREDITS.md` file for credits. See the `CHANGELOG.md` file for what has changed between versions.

As of Version 0.1, the cartridge header contains information about the version of the game:
- The special version byte (at offset 0x7FBE) denotes the minor version (the `0` in `1.0`).
- The version byte (at offset 0x7FDB) denotes the major version (the `1` in `1.0`).
- The cartridge name string (at offset 0x7FC0) contains the build date in YYYY-MM-DD format.
