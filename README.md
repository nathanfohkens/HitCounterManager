# HitCounterManager - A Dark Souls inspired Hit Counter

**Free Hit Counter** that is running in the background, so you can focus on your stream.  
No need to keep any windows open for a window capture any more.  
Initially designed for Dark Souls but supports any game.  
Just add the local HTML file to you broadcasting software and the setup is done.  
**Works completely offline, no account or login required.**

[![Get latest version here](https://img.shields.io/badge/-Get%20latest%20version%20here-brightgreen?longCache=true&style=for-the-badge)](../../releases/latest)

To see some **screenshots** of this application go to the **[Wiki pages](../../wiki)**.  
To see **how to** use the application watch the **[Tutorial on YouTube](https://www.youtube.com/watch?v=iXGExlS4xeM)**.

<p align="center"><a href="Images/Preview.png"><img src="Images/Preview.png" alt="Preview" width="700px"/></a></p>

[![Releases](https://img.shields.io/github/release/topeterk/HitCounterManager.svg?label=Latest%20release:&longCache=true&style=for-the-badge&colorB=0088FF)](../../releases/latest)
[![GitHub Releases](https://img.shields.io/github/downloads/topeterk/HitCounterManager/total.svg?label=Downloads:&longCache=true&style=for-the-badge&colorB=0088FF)](../../releases)
[![GitHub](https://img.shields.io/github/license/topeterk/HitCounterManager.svg?label=License:&longCache=true&style=for-the-badge&colorB=0088FF)](LICENSE)

## Key-Features

* Offline application
* No window capture needed for stream integration
* Hot key support for seamless use **ingame** (Windows only)
* Easy to use profile management
* On the fly configurable design

### Features in detail

* Configurable keyboard hot keys can be used while running fullscreen games (like Dark Souls III):
  * Increase/Decrease hit count of the current split (boss hits and hits on the way separately)
  * Go to next/previous split
  * Reset the run (sets all hit counts to 0 and selects first split)
  * Save the run as your PB (personal best)
  * Start/Stop the timer
* One single save file: **HitCounterManagerSave.xml**
  * Holds all your settings, profiles and is designed to work in newer/upcoming versions, too. Save and restore this file at any time.
* Create profiles for each challenge or game
  * Keeps the current progress and your personal bests saved
  * Keep track of each profile how many runs/attempts your already started
  * Multiple profiles can be created and switched very easily (e.g. multiple games for Dark Souls trilogy runs)
    * Switching to other profiles will remember the hit counts of the currently selected profile
* Build easy customizable succession, e.g. _Dark Souls Trilogy_
* Keep track of furthest progress in the current session
* Dark Mode
* Timer

### Pre-defined profiles

* Bloodborne + The old hunters
* Dark Souls 1 Prepare To Die Edition
* Dark Souls 2
* Dark Souls 3 + Ashes of Ariandel + The Ringed City
* Demon's Souls
* Salt and Sanctuary
* Sekiro
* The Surge + A walk in the park
* The Surge 2
* Mortal Shell

### Design configurations

The appearance of all designs can be modified via GUI on the fly:  
> Updates run with an interval of 1.5 seconds to spare performance  
> Previews can be found at the **[Wiki pages](../../wiki)**.

* Purpose
  
  * Split counter _(Traditional hit counter)_
  * Checklist _(Marking splits like on a checklist)_
  * No death _(Track how far you get without dying)_
  * Death counter _(Very simple death counter)_
* Choose severity of hits _(ends up in differnt split colors)_
  
  * Any hit counts as a critical hit
  * Boss hits are critical, hits on the way count normal
  * Splits having hits less than PB count normal, otherwise critically
* Appearance
  
  * Show/Hide amount of runs that has already been started
  * Show/Hide the headline and/or footer
  * Show/Hide the session progress icon
  * Show/Hide progress bar
  * Show the hits separately or as a combination of boss hits and hits on the way
  * Show numbers or images to represent hits
  * Show/Hide the personal best
  * Show/Hide split/total/personal best time
* Readability _(e.g. for lower bitrates or mobile devices)_
  
  * Limit the visible splits when you have lots of splits
  * Enable/Disable transparency
  * Enable/Disable colored split names
  * Enable/Disable superscripted PB sum
  * Enable/Disable roman numerals
  * Enable/Disable highlighting of current split
* Custom design
  
  * Switch to a different font
  * Choose an alternative CSS file _(pink colored alternative available)_

<p align="center"><a href="Images/SampleDesigns.gif"><img src="Images/SampleDesigns.gif" alt="Designs animation"/></a></p>

## Get the software
All available releases can be found at the [Releases page](../../releases) on GitHub.  
[![Get latest version here](https://img.shields.io/badge/-Get%20latest%20version%20here-brightgreen?longCache=true&style=for-the-badge)](../../releases/latest)

## Installation

### Systemrequirements
* OS: Windows Vista, Windows Server 2003 or newer (32/64 bit)
  * Portable version (ZIP)
    * [.Net Framework 2.0 or newer](https://www.microsoft.com/net)
    > **Note**: Version 1.13 and older requires [.Net Framework 4.5 or newer](https://www.microsoft.com/net)
  * Installer version (Setup)
    * [.Net Framework 4.5 or newer](https://www.microsoft.com/net)
* OS: Any (32/64 bit)
  > **Note**: This version is **not supporting global hot keys**  
  * Portable version (Tar ball)
    * Running with [Mono](https://www.mono-project.com/) (_tested with 5.14.0_)  
      Start the application in the application's directory with **mono HitCounterManager.exe**  
      > **Note**: Mono supports **32 bit mode only** (therefore it cannot be run on OS without 32 bit support!)

### Instructions, Guides, Help

How to setup the application, configure or modify designs and use it with a broadcasting sofware or browser can be found at the Wiki:  
* [Broadcasting-Software](../../wiki/SetupGuide#Broadcasting-Software)
* [Customizing designs](../../wiki/SetupGuide#Customizing-designs)
* [Show designs in a browser](../../wiki/SetupGuide#Show-designs-in-a-browser)
* [FAQ](#FAQ)

## Anything is missing, something is annoying/can be improved or you just found a bug?
Message me via GitHub / e-mail or simply open an issue and I will try to help you out. Alternatively you can also send me a whipser on Twitch: [GeneralGunrider](https://www.twitch.tv/generalgunrider)

## Community
There is a great growing community on Discord called [Team Hitless](https://discord.gg/4E7cSK7).
If you are seeking for help, guidance or just talk about no hit runs, this is the right place for it.  
Thanks to everyone for helping other community members!

## Special thanks
I would never have created this tool without the inspiration by watching the awesome 0 hit and no death runners...  
Thanks to (in alphabetical order):
* [CouchJockey](https://www.twitch.tv/couchjockey)
* [Dinossindgeil](https://www.twitch.tv/dinossindgeil)
* [DonnyRekt](https://www.twitch.tv/donnyrekt)
* [FaraazKhan](https://www.twitch.tv/faraazkhan)
* [Kazoodle](https://www.twitch.tv/kazoodle)
* [Sayvi](https://www.twitch.tv/sayvi)
* [SlipperySuzie](https://www.twitch.tv/slipperysuzie)
* [Soldi](https://www.twitch.tv/soldi)
* [SquillaKilla](https://www.twitch.tv/squillakilla)
* [The_Happy_Hob](https://www.twitch.tv/the_happy_hob)
* [TigerG92](https://www.twitch.tv/tigerg92)
* Every member of the [Hitless team on Twitch](https://www.twitch.tv/team/hitless)
* Every contributor and contestor of the [German No Hit League](https://www.dinossindgeil.de)
* And also all the other great challenge runners out there that I cannot name here all.
  
> Praise the sun!  :sunny: . . . :fire: . . .  :running: :dash: 
