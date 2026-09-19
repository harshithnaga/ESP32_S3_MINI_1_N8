
This Custom ESP32_S3 Dev board built around the ESP32-S3-MINI-1-N8 module, featuring native USB, an onboard RGB status LED, and an I2C temperature/humidity sensor. 
## Features

- **MCU:** ESP32-S3-MINI-1-N8 (dual-core Xtensa LX7 @ 240MHz, 8MB flash, Wi-Fi + BLE 5)
- **USB-C** with native USB (no external USB-UART bridge — uses the S3's built-in USB OTG/Serial-JTAG)
- **WS2812B addressable RGB LED** (GPIO48) for status indication
- **ENS210 I2C temperature + humidity sensor**
- **TLV75801PDRV LDO regulator** (5V → 3.3V)
- Boot/Reset buttons with standard debounce circuitry
- Two 22-pin headers breaking out all usable GPIOs, I2C, and power rails

## Hardware

| Component | Part               | Purpose                    |
| --------- | ------------------ | -------------------------- |
| U4        | ESP32-S3-MINI-1-N8 | Main MCU/Wi-Fi module      |
| U3        | TLV75801PDRV       | 3.3V LDO regulator         |
| U1        | ENS210             | Temp/humidity sensor (I2C) |
| D1        | WS2812B            | RGB status LED             |
| U2        | D3VXA4B10LP        | USB ESD protection         |
## Files

All design files are in `esp32-s3-pcb-design.zip`, including:

- KiCad schematic (`.kicad_sch`)
- PCB layout (`.kicad_pcb`)
- Project file (`.kicad_pro`)
- ESP32_S3_MINI_1_N8 3dmodel, Foot print, symbol files.
- D3VXA4B10LP 3d Model file

Open with [KiCad](https://www.kicad.org/) (free, open-source EDA software) version 7 or later.

## Tools Used

- KiCad

## License

CC BY 4.0 or CERN-OHL-S are common for open hardware designs

## Author

C. HARSHITH NAGA
