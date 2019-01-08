# PictoChat Protocol Adapter
The PictoChat Protocol Adapter (PCPA) set of tools is designed to interact with the Nintendo DS PictoChat protocol, via a compatible Prism54 USB WiFi adapter.

## Distribution
The core `pcpa` library allows for a computer to send and receive black-and-white bitmap data to a PictoChat chatroom. When active, the PC is counted as a connected user.

The `pctt` library (PictoChat Text Toolkit) allows recognition and exchange of plain text through PictoChat, by recognizing the standard PictoChat font. When recognition fails, `pctt` falls back to bitmap data by default.

## Build process
This project not being ready for release yet, there is no official build toolchain for the moment.

## Why it exists
A while ago, a piece of software called `pictosniff` was created, which allowed users to decode incoming PictoChat messages, but not to interact with them. This library re-uses code from `pictosniff`, which is courtesy of Sebastien Bourdeauducq under the GNU GPL.

## Where I can get a Prism54 WiFi adapter
The official Nintendo USB WiFi adapter, with which this library was tested, is powered by the Prism54 chipset, the same which can be found inside of a Nintendo DS, DSi and 3DS.
