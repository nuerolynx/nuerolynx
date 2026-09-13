# Mathew Dutton

I have always wanted to know how things work. What interests me most is seeing how the pieces work together.

That curiosity has taken me through construction, networking, physical security, PLC controls, microcontrollers, firmware, authorized penetration testing, and reverse engineering. I learn by building, taking things apart, tracing failures, testing ideas in my home lab, and deploying solutions that have to work outside the lab.

Creating something beautiful and functional is usually a byproduct of understanding the system and caring about the details.

## Current work

### [Embedded Systems Lab](https://github.com/nuerolynx/embedded-systems-lab)

This is my main public code collection. It covers Arduino UNO R4 WiFi and ESP32 projects for access control, relay automation, displays, environmental monitoring, camera streaming, and Bluetooth audio.

Each project includes the source, wiring information, dependencies, configuration, and the limits I found while testing it.

### [ESP32 P4 Touch Display](https://github.com/nuerolynx/NueroLynx-ESP32-P4-Touch-Display)

This project combines ESP32 firmware, a touch interface, USB video transport, Windows display support, and touch input. It can run as a local interface or as an 800 x 1280 Windows display.

### PLC and industrial controls

I write and troubleshoot PLC logic, discrete input and output sequences, relay control, and equipment integrations. This work taught me to think clearly about states, timing, failure conditions, and what the hardware is actually doing.

### Security research and Flipper Zero

I use authorized penetration testing and reverse engineering to understand devices, protocols, and where they fail.

### Nuerolynx Flipper Zero firmware

Nuerolynx Firmware is my custom Flipper Zero build based on Momentum Firmware. I made it because I wanted one dependable field and lab tool that fits the way I work. It keeps the broad protocol and application support of Momentum while giving me a more focused interface and clearer paths between tools for physical security, electronics, and system diagnostics.

The firmware carries the Nuerolynx identity through the boot screen, update screen, menus, icons, and default asset pack. Its animated status trace advances when the display already redraws, which adds motion without a separate wake timer and limits the effect on battery life. Upgrade migration preserves settings, menu entries, and keybinds so a new build does not needlessly reset the device.

My current development build adds the NLX Credential Suite. It provides one passive scan flow for NFC smart cards, Picopass and iCLASS, 125 kHz RFID, and iButton credentials. It can recognize cards that combine more than one technology, decode supported Wiegand formats, save inspection reports, and open a specialist tool when deeper authorized testing is needed. Normal scanning does not write, emulate, recover keys, or fuzz credentials. Those actions require a deliberate Authorized Lab acknowledgment.

The build also includes the NLX Electrical Calculator for Ohm's law, voltage drop, wire loss, delivered voltage, run length, and conductor sizing. A GPIO logic analyzer helps trace digital signals, while a smart meter radio monitor helps observe compatible meter activity. These additions make the Flipper more useful for troubleshooting field wiring, inspecting credential systems, following signals, and learning how devices communicate.

This firmware is for Flipper Zero owners who are comfortable maintaining custom firmware and want a practical lab and field toolkit. It is especially useful for physical security technicians, embedded developers, electronics troubleshooters, and curious builders working on equipment they own or have clear permission to assess. Anyone who wants the official Flipper Devices support path should remain on official firmware.

Before loading it, users should back up the device and SD card. The current update package installs through qFlipper or Flipper Lab. The source preserves the licenses and credits from Momentum Firmware, Flipper Devices, and the individual application authors whose work it includes.

### Home lab

My home lab is where I test networks, servers, virtualization, embedded hardware, and system integrations before I deploy them. It gives me a place to find failure points, document what matters, and learn from the whole system instead of looking at one component at a time.

### [Nuerolynx](https://www.nuerolynx.com)

Nuerolynx is where I apply that experience to communications infrastructure, electronic security, system design, permitting support, and project management.

## Languages and tools

I use C, C++, C#, Python, JavaScript, HTML, CSS, PowerShell, and CMake.

My hardware and platform work includes ESP32, Arduino, STM32, Raspberry Pi, Flipper Zero, .NET, Windows drivers, Docker, virtualization, enterprise networking, and PLC control systems.

## How I work

I start by learning what the system actually needs to do. Then I prototype the smallest useful version, test the complete path, document the decisions that matter, and deploy something that can be understood and maintained.

## Find me

[Nuerolynx website](https://www.nuerolynx.com)

[Founder profile](https://www.nuerolynx.com/founder.html)
