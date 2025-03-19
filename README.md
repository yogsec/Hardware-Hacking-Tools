# 🔧 Hardware Hacking Tools

**Hardware Hacking Tools**! 🚀 lists various tools used in hardware hacking, categorized by attack methods. Whether you're a security researcher, penetration tester, or just curious about hardware security, this repo is for you! 🔍💻

---

### 1. Firmware Analysis & Extraction 🖥️

#### 🛠️ JTAG/SWD Debugging
- **[JTAGulator](http://www.grandideastudio.com/jtagulator/)** – Identifies JTAG pinouts on embedded devices.
- **[OpenOCD](http://openocd.org/)** – Open-source debugging and programming tool for embedded devices.
- **[UrJTAG](http://urjtag.org/)** – Universal JTAG library supporting multiple devices.
- **[Segger J-Link](https://www.segger.com/products/debug-probes/j-link/)** – A commercial JTAG/SWD debugger with high-speed debugging.
- **[Xilinx Platform Cable USB II](https://www.xilinx.com/products/boards-and-kits/hw-usb-ii-g.html)** – Used for debugging and programming Xilinx devices.
- **[STM32 ST-Link](https://www.st.com/en/development-tools/st-link-v2.html)** – Debugging and flashing STM32 microcontrollers.
- **[Black Magic Probe](https://github.com/blacksphere/blackmagic)** – Open-source JTAG debugger supporting SWD.

#### 🔌 UART/SPI/I2C Debugging
- **[Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate)** – Universal interface for SPI, I2C, and UART debugging.
- **[Logic Analyzers](https://www.saleae.com/)** – Capture and analyze signals (Saleae, Sigrok, etc.).
- **[FTDI Adapters](https://www.ftdichip.com/)** – Convert USB to UART/SPI/I2C for debugging.
- **[Beagle I2C/SPI Protocol Analyzer](https://www.totalphase.com/products/beagle-i2cspi/)** – Monitors I2C and SPI traffic.
- **[TI MSP-FET](https://www.ti.com/tool/MSP-FET)** – Debugger for MSP430 microcontrollers.

#### 📥 Firmware Dumping
- **[CH341A Programmer](https://www.aliexpress.com/wholesale?SearchText=CH341A+Programmer)** – Reads and writes SPI flash chips.
- **[Flashrom](https://flashrom.org/Flashrom)** – Open-source tool for reading, writing, and erasing firmware.
- **[Dediprog SF100](https://www.dediprog.com/products/SF100)** – High-speed SPI Flash programmer.
- **[Shikra](https://int3.cc/products/the-shikra)** – Debug and communicate with UART, JTAG, and SPI devices.
- **[RT809H](https://www.aliexpress.com/wholesale?SearchText=RT809H)** – Universal programmer for dumping firmware from EEPROMs.
- **[Teensy](https://www.pjrc.com/teensy/)** – Custom DIY method for SPI flash dumping.

#### 📂 Reverse Engineering Firmware
- **[Ghidra](https://ghidra-sre.org/)** – NSA’s open-source reverse engineering framework.
- **[IDA Pro](https://hex-rays.com/ida-pro/)** – Industry-standard tool for disassembling firmware binaries.
- **[Binwalk](https://github.com/ReFirmLabs/binwalk)** – Extracts and analyzes firmware images.
- **[Firmware-Mod-Kit](https://github.com/rampageX/firmware-mod-kit)** – Extracts and modifies firmware.
- **[Unblob](https://github.com/onekey-sec/unblob)** – Extracts and analyzes binary blobs.
- **[GDB (GNU Debugger)](https://www.sourceware.org/gdb/)** – Debugging firmware in real-time.
- **[Radare2](https://rada.re/n/)** – Open-source framework for binary analysis.
- **[Capstone](http://www.capstone-engine.org/)** – Disassembly framework for analyzing instruction sets.
- **[Angr](https://angr.io/)** – Python-based binary analysis tool.
- **[Cutter](https://cutter.re/)** – GUI-based alternative to Radare2 for reverse engineering.

---

# 2. 🔨 Physical Attacks Toolkit

---

## 🛠️ Side-Channel Attacks & Fault Injection
- [**ChipWhisperer**](https://newae.com/) – Open-source side-channel analysis and fault injection tool.
- [**ChipSHOUTER**](https://newae.com/chipshouter/) – Advanced electromagnetic fault injection (EMFI) tool.
- [**GlitchKit**](https://github.com/hexanaut/glitchkit) – Tool for voltage glitching on embedded devices.
- [**Raspberry Pi Pico + PicoEMP**](https://github.com/33Y0KHz/PicoEMP) – DIY EM fault injection tool.
- [**OpenQASM**](https://github.com/Qiskit/openqasm) – Side-channel vulnerability analysis tool for quantum computing.
- [**Riscure Inspector**](https://www.riscure.com/) – Commercial side-channel analysis tool.

## 🔥 Voltage & Clock Glitching
- [**GlitchKit**](https://github.com/hexanaut/glitchkit) – Software/hardware glitching toolkit.
- [**ChipWhisperer-Lite**](https://newae.com/) – Hardware fault injection tool for glitching.
- [**Proxmark3**](https://proxmark.com/) – RFID/NFC analysis and glitching attacks.
- [**HackRF One**](https://greatscottgadgets.com/hackrf/) – SDR for RF glitching.

## 🔩 Hardware Debugging & Tampering
- [**JTAGulator**](http://www.grandideastudio.com/jtagulator/) – Finds JTAG pinouts for debugging.
- [**Shikra**](https://int3.cc/products/the-shikra) – Works with JTAG, UART, and SPI.
- [**Bus Pirate**](http://dangerousprototypes.com/docs/Bus_Pirate) – Multi-protocol debugging interface.
- [**GoodFET**](https://github.com/travisgoodspeed/goodfet) – Open-source JTAG debugging tool.
- [**OpenOCD**](http://openocd.org/) – Open-source JTAG/SWD debugging tool.
- [**Black Magic Probe**](https://github.com/blacksphere/blackmagic) – Open-source debugging tool.

## 🏴‍☠️ Chip Decapping & Microprobing
- [**Chemical Decapping Kits**](https://www.micross.com/products/services/die-processing/decapsulation.aspx) – Removes IC protective layers.
- [**FIB (Focused Ion Beam) Tools**](https://www.zeiss.com/microscopy/en/products/fib-sem.html) – Modifies IC internals.
- [**Probe Stations**](https://www.signatone.com/) – Allows direct electrical contact with microchips.

## 📡 RFID/NFC Cloning & Attacks
- [**Proxmark3**](https://proxmark.com/) – RFID/NFC cloning and hacking device.
- [**ChameleonMini**](https://github.com/emsec/ChameleonMini) – Open-source NFC emulation tool.
- [**Flipper Zero**](https://flipperzero.one/) – Multi-tool for RFID, NFC, and other hardware hacking.
- [**MFCUK**](https://github.com/nfc-tools/mfcuk) – Cracks Mifare Classic RFID cards.
- [**MFOC**](https://github.com/nfc-tools/mfoc) – Dumps and cracks Mifare Classic keys.

## 🧲 Electromagnetic Attacks & TEMPEST
- [**TempestSDR**](https://github.com/martinmarinov/TempestSDR) – Reads screen emissions via radio signals.
- [**Van Eck Phreaking Kits**](https://github.com/van-eck-phreaking) – Exploits electromagnetic leaks.
- [**USBKill**](https://github.com/hephaest0s/usbkill) – Physically destroys hardware via high-voltage USB.

---


