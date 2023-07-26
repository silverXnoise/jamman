# Hacking The DigiTech JamMan

## Summary

This repository holds files, links, and assets to facilitate the reverse engineering and modification of the DigiTech JamMan SoloXT looping pedal.

**Note**: *Other Digitech models may/may not work with the solutions here.*

### DigiTech JamMan SoloXT

> **Stereo Looping in a Compact Pedal with JamSync**
> 
> After inventing looping nearly three decades ago, DigiTech’s JamMan Solo XT brings you the definitive stereo looping experience. Build up the energy in your performance and find new inspiration with virtually limitless loops. Seamless transitions between looped phrases make the JamMan Solo XT an invaluable tool for composing and performing. Get the stereo looping experience you need from straight-forward backing loops to intricate loop layers by yourself or with your band. Perfect your performance with Auto-Record, Auto-Quantize, adjustable BPMs, and three different Stop modes. Use the powerful JamSync to link JamMan Solo XTs and create the ultimate multi-looping system. The JamMan Solo XT gives your musical performance a rich, full sound while staying true to the sound you compose. Get your JamMan Solo XT today and tear down your musical limitations.

#### Links

- [Product Page][1]
- [Owner's Manual][2]
- [Arduino Tempo Sync][3] - by @[joeSeggiola][3a]
- [Sync To MIDI Clock][4] - by @[Calde-github][4a]
- [Reverse Engineering Sync Signals][5]
- [Protocol Info (2018)][6]

#### Specifications

|     |     |
| --- | --- |
| **A/D/A Conversion** | 24-bit |
| **Sampling Frequency** | 44.1 kHz |
| **Frequency Response** | +0/-3 dB 20-20 kHz |
| **Loop File Format** | 44.1 kHz, 16-bit (stereo), uncompressed WAV file |
| **USB** | 2.0 High Speed (USB 1.1 compatible) |
| **Connector Type** | 5-Pin Mini B |
| **Max. Loop Length** | 10 minutes (stereo) |
| **Internal Memory Capacity** | Over 35 minutes total loop time (up to 200 loops total) |
| **External Memory Type** | Micro SD/SDHC up to 32GB (optional) |
| **External Memory Capacity** | Over 32 hours (10.6MB/minute) of recording time, when using 16GB or larger Micro SDHC card (up to 200 loops total) |
| **Power Consumption** | Less that 9 Watts |
| **Power Supply** | PS0920DC (Included), Output = 9.0VDC 2.0A |

#### Audio I/O

|     |     |
| --- | --- |
| **Input** | 2 x 1/4" (L/R) |
| **Aux Input Connector** | 1/8" |
| **Footswitch Input** | 1/4” Stereo (Tip-Ring-Sleeve), compatible with optional DigiTech® FS3X 3-button footswitch |
| **Output** | 2 x 1/4" (L/R) |

#### Dimensions

|     |     |
| --- | --- |
| **Length** | 5.0" |
| **Width** | 3.125" |
| **Height** | 2.25" |

#### JamManager Software

**Note**: *DigiTech discontinued the JamMan series, and no longer offers its software on their website. These point to Internet Archive links instead.*

| Name | D/L | Platform | Version | Released |
| --- | --- | --- | --- | --- |
| **JamManager XT** | [Download][win] | Windows | 2.3.5 | Aug 29, 2017 |
| **JamManager XT** | [Download][mac] | MacOS | 2.3.5 | Aug 29, 2017 |

**Minimum System Requirements:**

- OS X 10.8.5 – 10.12.6
- Intel Core Processor
- 2GB RAM 
- USB Port

---
[1]: https://digitech.com/dp/jamman-solo-xt/
[2]: https://eadn-wc05-7545739.nxedge.io/wp-content/uploads/2022/09/DigiTech_JamMan_Solo_XT_Manual.pdf
[win]: https://web.archive.org/web/20230212041405/https://adn.harmanpro.com/softwares/wares/604_1504020489/JamManagerXTSetup_2.3.5.exe
[mac]: https://web.archive.org/web/20170908204550/http://digitech.com/en-US/softwares/jammanager-xt-v2-3-5-mac-os-x-52ee012f-eff3-4a4d-98d4-b507b58b6ee8
[3]: https://github.com/joeSeggiola/jamman-arduino-sync
[3a]: https://github.com/joeSeggiola/jamman-arduino-sync
[4]: https://github.com/Calde-github/Looperino/tree/master
[4a]: https://github.com/Calde-github/Looperino
[5]: https://www.freestompboxes.org/viewtopic.php?f=1&t=26184
[6]: http://fuzzysynth.blogspot.com/2015/06/digitech-jam-man.html
