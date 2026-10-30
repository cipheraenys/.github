## TS3-RTOS

A TeamSpeak 3 client for RTOS / cellular handheld PoC radios. The C++17 core is
tested on PC and on FreeRTOS in QEMU; the Quectel EC600M port builds but has not
run on hardware.

- [ts3-core](https://github.com/cipheraenys/ts3-core) — portable C++17 client core (TS3 protocol and crypto) with ports for PC, FreeRTOS+TCP (QEMU) and Quectel EC600M (QuecOpen).
- [ts3-quecpython](https://github.com/cipheraenys/ts3-quecpython) — QuecPython device layer (BQ280 / EC600M: LCD, audio, PTT).
- [ts3-rtos](https://github.com/cipheraenys/ts3-rtos) — umbrella tying the two together as submodules.
