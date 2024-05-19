# Flipper Zero: Syntax Highlighting

This is a VSCode extension which adds syntax highlighting for Flipper Zero files like `.sub`, `.nfc`, `.rfid`, `.ir`, etc.

# Known Issues

Still missing support for BadUSB. I will add this soon. Also, probably missing support for older version of Flipper files since the some of the formats have changed a bit over time.

I'll also add highlighting for other various Flipper files related to common apps, or app development (.fam).

# Change Log

## [1.3.0] - 2024-05-19

- Added support for:
  - Bad USB scripts (DuckyScript), including the additional Flipper Zero commands
  - `.fam` - Flipper Application Manifest files

## [1.2.0] - 2024-05-05

- Added support for:
  - `.ibtn`
  - `.u2f`
  - `.fmf` (Flipper Music File)
- Fixed `NECext`, `NEC42` and `NEC42ext` highlighting in `.ir` and `.xr`

## [1.1.0] - 2024-04-18

- Added support for:
  - `.picopass` (Picopass app)
  - `.xr` (Cross Remote app)

## [1.0.0] - 2024-04-06

- Initial release
- Includes basic syntax highlighting for:
  - `.ir`
  - `.sub`
  - `.nfc`
  - `.rfid`