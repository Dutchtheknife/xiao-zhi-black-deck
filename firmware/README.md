# Black Deck 2.8 Firmware

## Verified firmware

- File: [BlackDeck_2.8_LCDWiki_ES3N28P_2.5.1.bin](./BlackDeck_2.8_LCDWiki_ES3N28P_2.5.1.bin)
- Target board: LCDWiki ES3N28P
- Hardware variant: 2.8-inch IPS ESP32-S3, non-touch
- Display controller: ILI9341V
- Firmware: Customized XiaoZhi AI 2.5.1
- SHA-256: 06E1FD99AF492EADB545B41E7E372C7B7F839BC9682EA2DE27542C34AE327CBA

## Important variant distinction

ES3N28P is the no-touch board. ES3C28P is the capacitive-touch variant using the FT6336G controller. Do not flash this ES3N28P binary to an ES3C28P touch board without confirming compatibility.

## Attribution

This build is based on the XiaoZhi ESP32 project. The local source archive identifies the project under the MIT License and credits Shenzhen Xinzhi Future Technology Co., Ltd. and project contributors. The upstream license notice must be preserved with redistributed source or binaries where applicable.

## Quick Start guide

Download the [Dutch CyberWorks Black Deck Quick Start guide](../docs/Black%20deck%20qs.odt).

## Flashing

Flashing instructions will be added after the exact Black Deck hardware and download procedure are verified against the Quick Start guide and LCDWiki documentation.

This file documents the firmware artifact; it is not a claim that every bundled dependency or asset has identical licensing.
