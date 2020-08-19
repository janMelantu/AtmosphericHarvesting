# AtmosphericHarvesting
Melantu Atmospheric Harvesting (MAH) is a small KSP mod to complement the Stock ISRU with atmospheric harvesting and converting. Specifically, this mod is designed to turn Carbon Dioxide in the atmospheres of Duna, Eve, and Laythe (and Kerbin, though I'm not sure why you would need it) into Liquid Fuel and Oxidizer. This mod is inspired by Mars Direct, *The Martian*, and the MOXIE experiment on the Mars 2020 rover. 

## Features
As it is based partially on Mars Direct, the MAH converter parts are designed to take a small supply of Liquid Hydrogen and combine it with atmospheric Carbon Dioxide to create stock Liquid Fuel and Oxidizer. It is designed to run with minimal power requirements (a single PB-NUK RTG can power it) at very slow speeds, similar to the Mars Ascent Vehicle from *The Martian*. And since it was inspired by the MOXIE experiment on the Mars 2020 rover, it fits in a small form factor (the stock atmospheric analyzer), and will eventually include its own science experiment. 

The basic conversion ratio is 3:4, or 1200 units of Liquid Hydrogen (the smallest radial CryoTank) to 1600 units of LFO mix (the Rockomax 16). Below is a table time it takes to convert different amounts of fuel at 100% load (at least Sea Level at Laythe, at least 5 km up at Duna, and probably anywhere on Eve)

| Part | Electricity Requirement | FL-T100 | FL-T400 | Rockomax 16 | Jumbo 64/Big Orange Tank | S3-14400 (Biggest Stock Tank) |
| --- | --- | --- | --- | --- | --- | --- |
| MAH MOXIE | 0.5 ec/s | 33 hr (5.5 days) | 22.125 days | 88.5 days | 354 days | 796.5 days |

## Dependencies
This mod could not exist without other mods doing the heavy lifting. Specifically, this mod absolutely requires (and is bundled with)

* [Module Manager (4.1.4)](https://github.com/sarbian/ModuleManager)
* [Community Resource Pack (1.3.0)](https://github.com/BobPalmer/CommunityResourcePack)

Unless you want to create your own Hydrogen tanks, this mod also requires (but is *not* bundled with)

* [CryoTanks (1.5.2)](https://github.com/ChrisAdderley/CryoTanks)
* [B9PartSwitch (2.17.0) (Bundled with CryoTanks)](https://github.com/blowfishpro/B9PartSwitch)
* [DynamicBatteryStorage (2.1.7) (Bundled with CryoTanks)](https://github.com/ChrisAdderley/DynamicBatteryStorage)

## Installation
To install, place the GameData folder inside your Kerbal Space Program folder. If asked to overwrite files, please do so.

NOTE: Do NOT rename or move folders within the GameData folder - this mod uses absolute paths to assets and will break if this happens.

## External Mod Compatibility
This mod should be compatible with any mod using the Community Resource Pack. It is currently unknown if this mod is compatible with TAC Life Support or RealFuels.

## Translations
For translation instructions please see Localization Instructions

## Licensing
Any bundled mods are distributed under their own licenses:

* ModuleManager by ialdabaoth and sarbian is distributed under a Creative Commons Sharealike license. More details, including source code, can be found [here](https://forum.kerbalspaceprogram.com/index.php?/topic/50533-18x-110x-module-manager-414-july-7th-2020-locked-inside-edition/&tab=comments#comment-720814)
* The Community Resource Pack by RoverDude is also distributed under its own license. Please find source and more details [here](https://github.com/BobPalmer/CommunityResourcePack)

Everything else is distributed under the MIT license.

Copyright (c) 2020 jan Melantu

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
