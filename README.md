# Oric-1/Atmos Switchable ROM

## Description

Oric-1 and Oric Atmos were 8-bit machines designed in early 80's by Tangerine Computer Systems to compete with Sinclair ZX Spectrum. Unfortunatelly, their success was rather limited. One of the Oric-1's problems was buggy ROM. It has been partially improved in Atmos released later. So the first upgrade for Oric-1 user is replacing ROM. This is however, not trival, because of special masked ROM used that has two enable lines. One, standard /CS on pin 20 and another called /ROMDIS on pin 27. The result is that you can use standard 27128 EPROM only if you dont use external devices (like Erebus SD loader which is a must) that utilize /ROMDIS line to disable internal ROM. So additional logic must be impemented to enable internal ROM when /CS line is active and /ROMDIS line is inactive. Another problem is size of the case which requires low profile build. 

## Features

* Easily available W27C512 EEPROM used, no need for UV eraser
* Four vesions of ROMs selected with DIP switch - Oric-4ROMs.BIN file consists of: [ORIC Diagnostic ROM ver.1.08k](https://oric.signal11.org.uk/html/diagrom.htm), Oric 1.0, Oric 1.1, Oric 1.22 ROMs
* Extremly low profile PCB

Have fun !

Tommy


> [!NOTE]
> **Disclaimer**: This is my project that I’ve built and it works for me. You can do it as well but remember, you’re responsible for your own doings 
