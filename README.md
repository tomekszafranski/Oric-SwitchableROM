# ORIC-1/Atmos ROM x4

## Description

Oric-1 and Oric Atmos were 8-bit machines designed in early 80's by Tangerine Computer Systems to compete with Sinclair ZX Spectrum. Unfortunatelly, their success was rather limited. One of the Oric-1's problems was buggy ROM. It has been partially improved in Atmos. So the first upgrade for Oric-1 user is exchanging ROM. However this is not trival because of special masked ROM used that has two enable lines. One, standard CS on pin xx and another called ROMDIS on pin 27. The effect is that you can use standard 27128 EPROM only if you dont use external devices (like Erebus SD loader which is a must). Additional logic must be impemented to enable ROM only when ROMDIS line is inactive. Another problem is size of the case which requires low profile build. 

## Features

* Four vesions of ROMS with swicth
* extremely low profile

Have fun !

Tommy


> [!NOTE]
> **Disclaimer**: This is my project that I’ve built and it works for me. You can do it as well but remember, you’re responsible for your own doings 
