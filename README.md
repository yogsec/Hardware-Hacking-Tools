# 🔧 Hardware Hacking Tools

![Hardware Hacking Tools](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExcXB2M3l1cHFmdXpyaXJldXplOWwwb3E1OXJoMG90ZDFiY2dyeXptMiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/z9g6xLr5C0H1m/giphy.gif)

**Hardware Hacking Tools**! 🚀 lists various tools used in hardware hacking, categorized by attack methods. Whether you're a security researcher, penetration tester, or just curious about hardware security, this repo is for you! 🔍💻

---

# Firmware Analysis & Extraction 🖥️

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

# 🔨 Physical Attacks Toolkit

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

# Wireless & Radio Hacking Tools

## 📡 Wi-Fi Hacking Tools
- **[Aircrack-ng](https://www.aircrack-ng.org/)** – Suite for Wi-Fi penetration testing.
- **[Wifite](https://github.com/derv82/wifite2)** – Automated Wi-Fi cracking tool.
- **[Fern Wi-Fi Cracker](https://github.com/savio-code/fern-wifi-cracker)** – GUI tool for Wi-Fi auditing.
- **[Reaver](https://github.com/t6x/reaver-wps-fork-t6x)** – WPS attack tool.
- **[PixieWPS](https://github.com/wiire-a/pixiewps)** – Offline WPS attack tool.
- **[Bettercap](https://www.bettercap.org/)** – Powerful network attack tool, including Wi-Fi attacks.
- **[MDK3](https://github.com/wi-fi-analyzer/mdk3-master)** – Wi-Fi testing and deauthentication tool.
- **[Kismet](https://www.kismetwireless.net/)** – Wireless network detection and monitoring.
- **[Wigle.net](https://wigle.net/)** – Database for mapping Wi-Fi networks.

## 📶 Bluetooth & BLE Hacking
- **[Blue Hydra](https://github.com/pwnieexpress/blue_hydra)** – Bluetooth device scanner.
- **[Bluesniff](https://github.com/andrewmichaelsmith/bluesniff)** – Bluetooth packet sniffer.
- **[BtleJack](https://github.com/virtualabs/btlejack)** – Bluetooth Low Energy hijacking tool.
- **[BLE CTF](https://github.com/hackgnar/ble_ctf)** – Bluetooth attack training tool.
- **[Bleah](https://github.com/evilsocket/bleah)** – Bluetooth hacking framework.
- **[BlueRanger](https://github.com/OJ/BlueRanger)** – Detect Bluetooth device distances.
- **[Ubertooth One](https://greatscottgadgets.com/ubertoothone/)** – Open-source Bluetooth monitoring tool.

## 📻 Software-Defined Radio (SDR) Hacking
- **[GNU Radio](https://www.gnuradio.org/)** – Signal processing toolkit for SDR.
- **[HackRF One](https://greatscottgadgets.com/hackrf/)** – Software-defined radio device for hacking.
- **[RTL-SDR](https://www.rtl-sdr.com/)** – Cheap USB SDR receiver.
- **[SDR# (SDRSharp)](https://airspy.com/download/)** – Popular SDR software.
- **[GQRX](http://gqrx.dk/)** – Open-source SDR software.
- **[BladeRF](https://nuand.com/)** – USB 3.0 SDR device for signal analysis.
- **[Red Pitaya](https://www.redpitaya.com/)** – SDR and signal processing platform.
- **[OsmoSDR](https://osmocom.org/projects/sdr/wiki/OsmoSDR)** – Open-source SDR framework.
- **[RFExplorer](https://rfexplorer.com/)** – Portable RF spectrum analyzer.
- **[GR-GSM](https://github.com/ptrkrysik/gr-gsm)** – GSM signal analysis tool.

## 📡 RFID/NFC Hacking
- **[Proxmark3](https://proxmark.com/)** – RFID/NFC research tool.
- **[ChameleonMini](https://kasper-oswald.de/chameleonmini/)** – RFID emulator and cloning device.
- **[Flipper Zero](https://flipperzero.one/)** – Multi-tool for wireless attacks, RFID cloning, and more.
- **[MFCUK](https://github.com/nfc-tools/mfcuk)** – Tool for MIFARE Classic card attacks.
- **[MFOC](https://github.com/nfc-tools/mfoc)** – MIFARE Classic offline cracking tool.
- **[NFC Tools](https://www.wakdev.com/en/apps/nfc-tools.html)** – Mobile app for NFC analysis.
- **[RFIDler](https://rfidler.com/)** – Software-defined RFID tool.
- **[Libnfc](https://github.com/nfc-tools/libnfc)** – Library for NFC communication.
- **[ICopy-X](https://icopyx.com/)** – RFID cloning and hacking device.

## 📞 GSM & Mobile Network Hacking
- **[OsmocomBB](https://osmocom.org/projects/baseband/wiki)** – Open-source GSM baseband software.
- **[OpenBTS](https://github.com/RangeNetworks/openbts)** – Build your own GSM network.
- **[IMSI Catcher](https://github.com/Oros42/IMSI-catcher)** – Detect IMSI catchers and rogue cell towers.
- **[Stingray Detector](https://github.com/CellularPrivacy/Android-IMSI-Catcher-Detector)** – Mobile IMSI catcher detection.
- **[SIMtrace](https://osmocom.org/projects/simtrace/wiki)** – Intercept SIM card communication.

---

# 🔬 Chip-Level Attack Tools

### 🏴‍☠️ 1. Chip Decapping & Microscopy
- **[Razor Blade & Nitric Acid](https://en.wikipedia.org/wiki/Die_destruction)** – Basic method for removing chip packaging.
- **[FIB (Focused Ion Beam)](https://en.wikipedia.org/wiki/Focused_ion_beam)** – High-end method for modifying IC structures.
- **[Delayering Kits](https://www.microscopy-and-analysis.com/)** – Chemical solutions for peeling off IC layers.
- **[Optical Microscopes](https://www.edmundoptics.com/)** – Inspecting chips post-decapping.
- **[Scanning Electron Microscope (SEM)](https://www.thermofisher.com/)** – Advanced chip imaging.

### ⚡ 2. Fault Injection & Glitching
- **[ChipWhisperer](https://chipwhisperer.io/)** – Side-channel analysis and fault injection tool.
- **[ChipSHOUTER](https://www.newae.com/chipshouter/)** – Electromagnetic fault injection (EMFI).
- **[GlitchKit](https://github.com/gmbnomis/GlitchKit)** – Glitching framework for embedded systems.
- **[VoltageGlitcher](https://github.com/astarasikov/VoltageGlitcher)** – Fault injection via voltage control.
- **[SPIDriver](https://github.com/robotic-controls/spidriver)** – SPI communication and glitching.

### 🔑 3. Power Analysis & Side-Channel Attacks
- **[ChipWhisperer-Nano](https://wiki.newae.com/ChipWhisperer-Nano)** – Low-cost power analysis tool.
- **[Riscure Inspector](https://www.riscure.com/security-tools/inspector-sca/)** – Commercial side-channel attack framework.
- **[OpenADC](https://www.newae.com/chipwhisperer/)** – ADC-based power analysis module.
- **[EM Probe](https://www.langer-emv.de/en/emc-probes/)** – Captures electromagnetic signals from chips.
- **[Kocher’s DPA Toolkit](https://www.cryptography.com/publications/dpa.html)** – Differential Power Analysis (DPA) framework.

### 🛡 4. Secure Chip Extraction & Key Recovery
- **[Glitching AES Chips](https://github.com/sidechannel-aes-glitching)** – Bypassing AES protection via fault injection.
- **[Voltage EMIF Fault Injection](https://www.emfi.eu/)** – Extracting keys via voltage spikes.
- **[X-Ray Chip Inspection](https://www.hitachi-hightech.com/)** – Identifying hidden security fuses.
- **[Laser Fault Injection](https://www.riscure.com/)** – Disrupting chip execution to leak data.

### 📥 5. Firmware & ROM Dumping
- **[JTAGulator](http://www.grandideastudio.com/jtagulator/)** – Identifying JTAG pinouts on unknown chips.
- **[Flashrom](https://flashrom.org/)** – Dumping flash memory from ICs.
- **[Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate)** – Dumping firmware from SPI/I2C/UART chips.
- **[Dediprog SF100](https://www.dediprog.com/products/SF100)** – High-speed SPI Flash programmer.
- **[EEPROM Dumper](https://github.com/devttys0/firmware-analysis-toolkit)** – Extracting EEPROM contents.

---

# 🔌 USB & Peripheral Attack Tools

### 🏴‍☠️ 1. USB Exploitation & HID Attacks
- **[Rubber Ducky](https://shop.hak5.org/)** – HID-based keystroke injection tool.
- **[Bash Bunny](https://shop.hak5.org/)** – Advanced automation & attack payloads.
- **[OMG Cable](https://o.mg.lol/)** – Malicious USB cable for remote access.
- **[Evil Crow Cable](https://github.com/EvilCROW-Cables)** – Open-source keystroke injection.
- **[Cactus WHID](https://github.com/whid-injector/WHID)** – USB HID injection with WiFi.
- **[PHUKD/URFUKED](https://samy.pl/urfu/)** – HID-based payload execution.

### 💾 2. USB Data Extraction & Exfiltration
- **[USBHarpoon](https://github.com/0xdea/USBharpoon)** – Data exfiltration via USB.
- **[USaBUSe](https://github.com/jkcvb/USaBUSe)** – Automated USB data theft.
- **[USBExfil](https://github.com/usbexfil/usbexfil)** – Auto-copy data from plugged-in devices.

### 🎭 3. USB Impersonation & Spoofing
- **[P4wnP1 A.L.O.A.](https://github.com/RoganDawes/P4wnP1_aloa)** – USB attack framework (HID, WiFi, storage).
- **[USBProxy](https://github.com/dominicgs/USBProxy)** – Man-in-the-Middle (MitM) for USB devices.
- **[USBDriveBy](https://samy.pl/usbdriveby/)** – USB device emulation for bypassing security.
- **[BadUSB](https://github.com/LaBlueFrog/badusb)** – Create malicious USB payloads.

### 📡 4. USB Network Attacks
- **[LAN Turtle](https://shop.hak5.org/)** – USB network implant for remote access.
- **[Packet Squirrel](https://shop.hak5.org/)** – USB network sniffing and payload execution.
- **[WiFi Pineapple](https://shop.hak5.org/)** – Rogue WiFi access point for network MITM.

### 🔥 5. USB Firmware & Debugging Exploits
- **[USBKill](https://github.com/hephaest0s/usbkill)** – Automatically disable a system when a USB device is removed.
- **[USBlyzer](https://www.usblyzer.com/)** – USB protocol analyzer for debugging.
- **[USBGuard](https://github.com/dkopecek/usbguard)** – Policy-based USB protection.
- **[FaceDancer](https://github.com/usb-tools/Facedancer)** – USB attack framework for fuzzing & reversing.
- **[GreatFET One](https://greatscottgadgets.com/greatfet/)** – USB debugging and analysis tool.

---

# 🛠 Hardware Modification & Implantation

### 🏴‍☠️ 1. Hardware Backdoor Implants
- **[NSA COTTONMOUTH](https://en.wikipedia.org/wiki/ANT_catalog)** – USB implant for covert data exfiltration.
- **[NSA IRONCHEF](https://www.schneier.com/blog/archives/2013/12/the_nsas_ironch.html)** – Malicious BIOS/firmware modification for persistence.
- **[NSA DEITYBOUNCE](https://en.wikipedia.org/wiki/ANT_catalog)** – BIOS-level malware for remote access.
- **[BadUSB](https://github.com/samyk/usbdriveby)** – USB firmware modification for keystroke injection.
- **[USBNinja](https://usb-ninja.com/)** – Wireless USB payload injector for remote attacks.
- **[OMG Cable](https://shop.hak5.org/products/omg-cable)** – Malicious USB cable for payload execution.

### 🎛 2. BIOS & Firmware Modification
- **[Flashrom](https://flashrom.org/)** – Reads, writes, erases, and verifies BIOS firmware.
- **[UEFI Tool](https://github.com/LongSoft/UEFITool)** – Analyzes and modifies UEFI firmware.
- **[CH341A Programmer](https://www.aliexpress.com/item/32820954869.html)** – USB flash programmer for BIOS modifications.
- **[Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate)** – SPI/I2C interface for firmware modifications.
- **[Dediprog SF100](https://www.dediprog.com/products/SF100)** – SPI flash programmer for BIOS recovery.
- **[Intel ME Cleaner](https://github.com/corna/me_cleaner)** – Disables Intel Management Engine.

### 🔌 3. Hardware Keyloggers & Data Interceptors
- **[KeyGrabber](https://www.keelog.com/)** – Hardware keylogger that records keystrokes invisibly.
- **[WiFi Keylogger](https://www.keelog.com/wifi-keylogger/)** – Wirelessly transmits keystroke logs over WiFi.
- **[USB Keylogger](https://www.keelog.com/usb-keylogger/)** – Plug-and-play keylogger for USB keyboards.
- **[LAN Tap](https://greatscottgadgets.com/throwingstar/)** – Passive network traffic sniffer.
- **[PS/2 Hardware Keylogger](https://www.keelog.com/ps2-keylogger/)** – Keystroke logger for older PS/2 keyboards.

### 🔩 4. Covert Implants & Surveillance Devices
- **[PwnPlug](https://www.pwnieexpress.com/)** – Covert network implant disguised as a power adapter.
- **[Pwnagotchi](https://pwnagotchi.ai/)** – AI-driven WiFi hacking device.
- **[HackRF One](https://greatscottgadgets.com/hackrf/)** – Wireless SDR for sniffing and modifying radio signals.
- **[Flipper Zero](https://flipperzero.one/)** – Multi-functional hacking device for RFID/NFC access.
- **[NSA RAGEMASTER](https://wikileaks.org/spyfiles/document/National-Security-Agency-NSA-RAGEMASTER-Monitor-Tapping-Hardware-Im-Plant-Description/)** – Covert RF implant that transmits monitor data remotely.
- **[WiFi Pineapple](https://shop.hak5.org/products/wifi-pineapple)** – Wireless network penetration testing device.

### ⚡ 5. Peripheral Device Hijacking
- **[USB Rubber Ducky](https://shop.hak5.org/products/usb-rubber-ducky)** – Keystroke injection tool disguised as a USB drive.
- **[MalDuino](https://malduino.com/)** – Open-source BadUSB keystroke injection tool.
- **[ESPloitV2](https://github.com/exploitagency/ESPLoiter)** – ESP8266-based WiFi HID attack device.
- **[MouseJack](https://github.com/BastilleResearch/mousejack)** – Exploits vulnerabilities in wireless mice.
- **[AirDrive Forensic Keylogger](https://www.keelog.com/airdrive-keylogger/)** – Wireless keylogger with real-time keystroke transmission.

### 🔬 6. Chip-Level Hardware Trojans
- **[ChipWhisperer](https://chipwhisperer.io/)** – Power analysis and fault injection tool.
- **[ChipSHOUTER](https://www.newae.com/chipshouter/)** – Electromagnetic fault injection for security bypassing.
- **[JTAGulator](http://www.grandideastudio.com/jtagulator/)** – Identifies JTAG interfaces on unknown chips.
- **[GlitchKit](https://github.com/gmbnomis/GlitchKit)** – Firmware glitching and fault injection framework.
- **[X-Ray Chip Inspection](https://www.hitachi-hightech.com/)** – Scans chips for hidden implants and modifications.

---

# ⚡ Power & Battery Attack Tools

### 🔋 1. Power Analysis & Side-Channel Attacks
- **[ChipWhisperer](https://chipwhisperer.io/)** – Side-channel power analysis and fault injection.
- **[Riscure Inspector](https://www.riscure.com/security-tools/inspector-sca/)** – Commercial tool for Differential Power Analysis (DPA).
- **[OpenADC](https://www.newae.com/chipwhisperer/)** – Analog-to-digital converter for power monitoring.
- **[Kocher’s DPA Toolkit](https://www.cryptography.com/publications/dpa.html)** – Used for differential power analysis.
- **[Langer EM Probe](https://www.langer-emv.de/en/emc-probes/)** – Captures electromagnetic emissions from chips.

### ⚡ 2. Voltage Fault Injection & Glitching
- **[ChipSHOUTER](https://www.newae.com/chipshouter/)** – Electromagnetic fault injection (EMFI).
- **[VoltageGlitcher](https://github.com/astarasikov/VoltageGlitcher)** – Injects voltage glitches to bypass security.
- **[GlitchKit](https://github.com/gmbnomis/GlitchKit)** – Framework for hardware glitching.
- **[SPIDriver](https://github.com/robotic-controls/spidriver)** – SPI-based power glitching tool.
- **[EMFI Kit](https://www.riscure.com/)** – Voltage and electromagnetic fault injection toolkit.

### 🔌 3. Power Consumption & Tampering Attacks
- **[USBKill](https://github.com/hephaest0s/usbkill)** – Kills power to devices via USB ports.
- **[Proxmark3](https://github.com/Proxmark/proxmark3/)** – RFID power analysis tool.
- **[Flipper Zero](https://flipperzero.one/)** – Multi-functional device for power manipulation.
- **[Lab Power Supplies](https://www.keysight.com/)** – Precision voltage control for attacks.
- **[Raspberry Pi Pico](https://www.raspberrypi.com/products/raspberry-pi-pico/)** – Can be used for power analysis and manipulation.

### 🔥 4. Battery-Based Attacks
- **[Supercapacitor Surge](https://www.supercaptech.com/)** – Disrupts devices with sudden power bursts.
- **[Battery Spoofing](https://www.pentestpartners.com/security-blog/battery-attacks/)** – Modifies power reports to bypass security.
- **[DC Power Attack](https://www.analog.com/en/technical-articles/dc-power-analysis.html)** – Manipulates voltage to damage components.
- **[Inductive Coupling](https://www.researchgate.net/publication/Inductive-Power-Analysis)** – Extracts data through power fluctuations.
- **[Battery Overload](https://www.teardown.com/)** – Overcharges or overheats batteries for attack vectors.

---

# 🏴‍☠️ Supply Chain Attack Tools

### 🔩 1. Hardware Supply Chain Attacks
- **[NSA Cottonmouth](https://en.wikipedia.org/wiki/Cottonmouth_(exploit))** – Covert USB implant with espionage capabilities.
- **[NSA IRATEMONK](https://en.wikipedia.org/wiki/Equation_Group)** – Hard drive firmware injection.
- **[NSA JETPLOW](https://www.schneier.com/blog/archives/2014/03/more_nsa_attacks.html)** – Persistent backdoors in Cisco devices.
- **[NSA SURLYSPAWN](https://electrospaces.blogspot.com/2015/03/nsas-catalog-of-tools-for-hardware.html)** – Secure chip manipulation.
- **[NSA FEEDTHROUGH](https://electrospaces.blogspot.com/2015/03/nsas-catalog-of-tools-for-hardware.html)** – BIOS-level malware persistence.

### 🔗 2. Firmware & BIOS Manipulation
- **[UEFI Implant](https://github.com/chipsec/chipsec)** – UEFI firmware analysis and modification.
- **[Thunderstrike](https://trmm.net/Thunderstrike/)** – Exploiting MacBook boot ROM.
- **[BIOS Implant Tools](https://github.com/Cr4sh/BIOS_Intelligence)** – BIOS dumping and modification.
- **[Coreboot](https://www.coreboot.org/)** – Open-source firmware alternative.
- **[Heads](https://github.com/osresearch/heads)** – Secure boot with tamper detection.

### 🎭 3. Software Supply Chain Attacks
- **[Poisoned Dependencies](https://github.com/coinbase/supply-chain-security)** – Detecting malicious npm/PyPI packages.
- **[Typosquatting Malware](https://typosquatting-tester.readthedocs.io/en/latest/)** – Identifying typo-based dependency attacks.
- **[Dependency Confusion Attack](https://github.com/visma-prodsec/confused)** – Checking for dependency confusion vulnerabilities.
- **[BadUSB Firmware](https://github.com/hak5darren/USB-Rubber-Ducky)** – Exploiting firmware on USB devices.
- **[Firmware Patching](https://github.com/ReFirmLabs/binwalk)** – Extract and modify firmware images.

### 🏗 4. Hardware Implantation
- **[Rogue Raspberry Pi](https://github.com/xychelsea/Raspberry-Pi-Payloads)** – Concealed MITM attack device.
- **[Malicious USB Keylogger](https://github.com/hak5darren/USB-Rubber-Ducky)** – USB-based keystroke logging.
- **[Trojanned ICs](https://www.mitre.org/publications/technical-papers/trust-in-integrated-circuits)** – Compromised microchips.
- **[Intercepted Shipment Attacks](https://www.schneier.com/blog/archives/2013/12/how_the_nsa_tam.html)** – Tampering with hardware in transit.

### 🛡 5. Detection & Prevention
- **[SigMF](https://github.com/gnuradio/sigmf-ninja)** – Spectrum analysis to detect implants.
- **[Osquery](https://osquery.io/)** – Querying firmware for anomalies.
- **[YARA Rules](https://github.com/VirusTotal/yara)** – Malware detection in software supply chains.
- **[Binwalk](https://github.com/ReFirmLabs/binwalk)** – Firmware backdoor analysis.
- **[Firmware Integrity Checker](https://github.com/chipsec/chipsec)** – Comparing firmware to clean versions.

---

## 🌟 Let's Connect!

Hello, Hacker! 👋 We'd love to stay connected with you. Reach out to us on any of these platforms and let's build something amazing together:

🌐 **Website:** [https://yogsec.github.io/yogsec/](https://yogsec.github.io/yogsec/)  
📜 **Linktree:** [https://linktr.ee/yogsec](https://linktr.ee/yogsec)  
🔗 **GitHub:** [https://github.com/yogsec](https://github.com/yogsec)  
💼 **LinkedIn (Company):** [https://www.linkedin.com/company/yogsec/](https://www.linkedin.com/company/yogsec/)  
📷 **Instagram:** [https://www.instagram.com/yogsec.io/](https://www.instagram.com/yogsec.io/)  
🐦 **Twitter (X):** [https://x.com/yogsec](https://x.com/yogsec)  
👨‍💼 **Personal LinkedIn:** [https://www.linkedin.com/in/cybersecurity-pentester/](https://www.linkedin.com/in/cybersecurity-pentester/)  
📧 **Email:** abhinavsingwal@gmail.com

---

## ☕ Buy Me a Coffee

If you find our work helpful and would like to support us, consider buying us a coffee. Your support keeps us motivated and helps us create more awesome content. ❤️

☕ **Support Us Here:** [https://buymeacoffee.com/yogsec](https://buymeacoffee.com/yogsec)
