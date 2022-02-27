# ta-65 rev4
65% PCB compatible with the Tada68 case and keyboards like it.

![ta-65 PCB front](https://i.imgur.com/nIENaIw.png)
![ta-65 PCB back](https://i.imgur.com/xAmKRDy.png)

## The many revisions

This board originally started out as a custom PCB for the Aanzee by westfoxtrot. I decided to make more of them, and with some changes, the ta-65 was born. It had always come with a Mini USB connector up until the third revision, and since then it has not been compatible anymore with the M65-a, however, I am willing to make that happen if someone asks about it :)


## Features

- Uses QMK Firmware and VIA
- Compatible with any case that uses the TADA68 PCB in its design
- USB-C connector
- ESD protection and fuse
- No in-switch LEDs
- Supports underglow with less likely to fail WS281**3**B LEDs
- ISP header
- JST header for use with a daughterboard


## Supported layouts
![ta-65 PCB supported layouts](https://i.imgur.com/R9Nojqu.png)


------------------------------


# Design files
Of course, as with any of my boards, you are responsible for what you do with this power. Before opening the files: read the license, of course, and also make sure you have the latest (stable finally!) version of KiCad, 6.0.2 or higher.

## Manufacturing
Manufacturing files and a 3d model (.step) are in here as well. Have fun!


------------------------------


# Changelog

- ### Rev 1 (e.a. feb 2019)
  First release

- ### Rev 2 (e.a. jan 2020)
  Added a JST header and switched the crystal over to a resonator.
First attempt at compatibility with the M65-a (but unsuccesful; PCB too wide)

- ### Rev 3 (e.a. april 2020)
  First revision to include USB-C (which ended up breaking compat with the M65-a *again*).

- ### Rev 3.1 (e.a. ???)
  Change daughterboard connector to fit the Unified Daughterboard specification. Probably nothing else.

- ### Rev 4 (e.a. feb 2022)
  Mostly redone routing, added solder header for pin B7 (free pin), moved daughterboard connector, made PCB outline somewhat prettier, changed WS2812B LEDs to WS281**3**B LEDs.