# BEEFCAKE 
*The absolute unit of a dual-MCU, hardwired, matrix-slinging, analog-crunching dev board.*

## What is BEEFCAKE?
BEEFCAKE isn't just a microcontroller board; it's a statement. Built out of sheer spite for unreliable wireless dropouts and a desire to completely over-engineer a hardware project, BEEFCAKE combines dual RP2040 microcontrollers, rock-solid hardwired Ethernet, an 8x8 LED matrix driven by a dedicated controller, an NFC reader/writer, and an ungodly number of GPIOs into a single top-mounted layout masterpiece.

## Key Features
* **Dual RP2040 Architecture:** 
  * **The Master ("Pimp"):** Handles heavy networking, system logic, and boasts 30 usable GPIOs.
  * **The Peripheral Slave ("Whore"):** Dedicated purely to analog-crunching, keeping its full suite of ADC channels completely pristine and isolated from digital noise.
* **Hardwired Ethernet:** Powered by a W5500 Ethernet stack and an RJ45 port because Wi-Fi is weak and cables are forever.
* **Matrix Vision:** Features an 8x8 LED matrix driven by a MAX7219 IC, paired with a custom NeoPixel button for maximum tactile satisfaction.
* **NFC Integration:** Built-in STMicroelectronics NFC reader/writer capabilities (ST25R3911B) for contactless sorcery.
* **Expansion Galore:** 
  * A 6-pin JST expansion connector wired straight to a clean SPI bus (3.3V, GND, SCK, MOSI, MISO, CS) to leave zero digital pins wasted.
  * A USB-C receptacle for power and programming.
* **Tactile Input:** On-board tactile buttons and test points for debugging sanity.

## Pinout & Hardware Specs
* **Total Master GPIO:** 30 available pins.
* **Total System ADCs:** 8 channels across the board (isolated cleanly on the slave).
* **Display Driver:** MAX7219 (SOIC-24 Wide) driving the 8x8 LED grid.
* **Network:** W5500 SPI Ethernet Controller + RJ45 with integrated magnetics.

---

### Serious now: AI Usage declaration.
This project uses AI in the README.md and nowhere else.
