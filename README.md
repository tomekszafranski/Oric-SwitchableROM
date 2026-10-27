# Oric-1/Atmos Switchable ROM

## Description

Oric-1 and Oric Atmos were 8-bit machines designed in early 80's by Tangerine Computer Systems to compete with Sinclair ZX Spectrum. Unfortunatelly, their success was rather limited. One of the Oric-1's problems was buggy ROM. It has been partially improved in Atmos released later. So the first upgrade for Oric-1 user is replacing ROM. 

This is however, not trival, because of special masked ROM used that has two enable lines. One, standard /CS on pin 20 and another called /ROMDIS on pin 27. The result is that you can use standard 27128 EPROM only if you don't use external devices (like Erebus SD loader which is a must) that utilize /ROMDIS line to disable internal ROM. Additional logic must be impemented to enable internal ROM when /CS line is active and /ROMDIS line is inactive. Another problem is size of the case which requires low profile build. 

| PCB top              | PCB bottom             |
| ---------------------- | ---------------------- |
|<img width="600" height="1100" alt="Zrzut ekranu 2026-10-27 153028" src="https://github.com/user-attachments/assets/15da1de0-5f77-4301-979a-3f592adaf79c" /> | <img width="600" height="1100" alt="Zrzut ekranu 2026-10-27 153007" src="https://github.com/user-attachments/assets/39df6986-a068-42ef-bef9-6063063b8a59" /> |

<img width="1920" height="1258" alt="36d4787d-b264-48c8-aa42-d9c8ace489f6" src="https://github.com/user-attachments/assets/44fa477b-4d31-4ebd-9f19-677ff8d1569e" />

## Features

* Easily available W27C512 EEPROM used, no need for UV eraser
* Four vesions of ROMs selectable with DIP switch
* Low profile PCB - use low profile pin headers
* Easy reprogramming - if you want to reprogram EEPROM that is soldered - change jumpers to "programming", use EEPROM programmer and change settings to "operation"

## Remarks

* Oric-4ROMs.BIN file consists of: [ORIC Diagnostic ROM ver.1.08k](https://oric.signal11.org.uk/html/diagrom.htm), Oric 1.0, Oric 1.1, Oric 1.22 ROMs

Have fun !

Tommy

> [!NOTE]
> **Disclaimer**: This is my project that I’ve built and it works for me. You can do it as well but remember, you’re responsible for your own doings
> 
> **Licensed under**: CERN Open Hardware Licence Version 2 - Strongly Reciprocal. Read [CERN-OHL-S](https://ohwr.org/cern_ohl_s_v2.txt)
> 
