## TS3-RTOS

A TeamSpeak 3 client for RTOS / cellular handheld PoC radios — portable C++ core,
real crypto and Opus voice, running on cellular modules and (feasibly) ESP32-class MCUs.

- **[ts3-core](https://github.com/cipheraenys/ts3-core)** — portable C++17 client core (crypto, TS3 protocol, Opus-ready) with ports for PC, FreeRTOS+lwIP, and Quectel EC600M.
- **[ts3-quecpython](https://github.com/cipheraenys/ts3-quecpython)** — QuecPython device layer (BQ280 / EC600M: LCD, audio, PTT).
- **[ts3-rtos](https://github.com/cipheraenys/ts3-rtos)** — umbrella tying the two together as submodules.
