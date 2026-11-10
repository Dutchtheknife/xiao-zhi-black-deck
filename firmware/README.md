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


## LCDWiki baseline


LCDWiki's official Quick Start package for the ES3C28P/ES3N28P boards includes XiaoZhi firmware builds labeled **1.7.6** and **2.0.2**. The newer LCDWiki baseline we identified is **XiaoZhi 2.0.2**—not XiaoZhi 2.3 or 2.4.

This Dutch CyberWorks build is a customized **XiaoZhi 2.5.1** firmware for the non-touch ES3N28P Black Deck, built to provide a newer, board-specific firmware option.


## Attribution and upstream source


This work is derived from the open-source [XiaoZhi ESP32 project](https://github.com/78/xiaozhi-esp32), maintained by the XiaoZhi project contributors and released under the MIT License. The local source archive credits Shenzhen Xinzhi Future Technology Co., Ltd. and project contributors.

Dutch CyberWorks modifications include the Black Deck ES3N28P target, board-specific display configuration, firmware build, and published binary documentation. This repository is intended to document and share our customized fork/derivative work; it does not claim ownership of the upstream XiaoZhi project or LCDWiki materials.

The upstream MIT license notice must be preserved with redistributed source or binaries where applicable.


## Quick Start guide


Download the [Dutch CyberWorks Black Deck Quick Start guide](../docs/Black%20deck%20qs.odt).


## Flashing


Use the verified procedure in the [Dutch CyberWorks Black Deck Quick Start guide](../docs/Black%20deck%20qs.odt). For the LCDWiki reference, use the official [ES3C28P/ES3N28P XiaoZhi Quick Start manual](https://www.lcdwiki.com/res/ES3C28P/2.8inch_ESP32-S3%E5%B0%8F%E6%99%BAAI%E5%BF%AB%E9%80%9F%E4%BD%BF%E7%94%A8%E6%89%8B%E5%86%8C.pdf). Confirm the board is **ES3N28P (non-touch)** before flashing.

This file documents the firmware artifact and our attribution. Third-party dependencies and assets may have separate licenses.
