# Goldshell ARI31 Firmware

Community firmware archive and recovery resources for the Goldshell ARI31 ASIC miner.

## Firmware Download

[Download firmware from GitHub Releases](https://github.com/18650Engineer/Goldshell-ARI31-Firmware/releases)

| Specification | Details |
|---|---|
| Manufacturer | Goldshell |
| Model | ARI31 |
| Firmware version | 2.2.3 |
| Controller designation | MCB_V3_3 |
| Format | IMG disk image |
| File size | 268.4 MB |

## Recovery Image

`burn-Goldshell-ARI31_MCB_V3_3-2.2.3.img`

The original TAR archive contains this IMG file.

## MicroSD Recovery

The following is a general recovery procedure. Model-specific flashing instructions and controller compatibility still require verification.

1. Download the IMG firmware file.
2. Insert a microSD card into your computer.
3. Use an image-writing utility such as balenaEtcher or Raspberry Pi Imager to write the IMG file to the card.
4. Safely eject the microSD card.
5. Power off the miner.
6. Follow the Goldshell recovery procedure for your specific controller revision.

Writing the image will erase the contents of the microSD card.

## Compatibility and Support

Verify your controller revision before flashing. Compatibility with all ARI31 hardware revisions has not been established.

Users are encouraged to report successful recovery results, controller revisions, and firmware issues through GitHub Issues.

## Disclaimer

This is an unofficial community repository and is not affiliated with Goldshell. Firmware rights remain with their respective owners. Use at your own risk.
