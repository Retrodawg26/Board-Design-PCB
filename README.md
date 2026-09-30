# Board-Design-PCB

ESP32 development board design — schematic complete, PCB in progress (WIP).

This repository is a public portfolio snapshot of my board design work. It shows the schematic design, the PCB project file, and the current work-in-progress state for an ESP32-based development board.

Project status
- Schematic design: complete
- PCB layout: in progress
- BOM: preliminary BOM export available from the schematic
- Manufacturing outputs (Gerbers / NC drill): not yet generated

Included design files
- ESP32_Dev_Board.PrjPcb
- ESP32_Dev_Board.PcbDoc
- 5V-to-3.3V_Voltage _Regulator.SchDoc
- Micro_USB_&_USB-UART.SchDoc
- Connectors_&_Switch_Buttons.SchDoc
- ESP32_Module.SchDoc
- ESP-WROOM-32D.IntLib
- LESD5D5.0CT1G.IntLib
- Esp32_Dev_Board.BomDoc

Exported documentation
- 5V-to-3.3V_Voltage _Regulator.pdf
- Micro_USB_&_USB-UART.pdf
- Connectors_&_Switch_Buttons.pdf
- ESP32_Module.pdf

BOM
- The BOM export is included as the Altium-generated BOM document: Esp32_Dev_Board.BomDoc
- A CSV export version can be added later once the final BOM is cleaned up for release.

Repository structure
- README.md — project overview and status
- DESIGN_STATUS.md — current tasks and outstanding design work
- hardware/ — for future organization of library and PCB source files
- docs/ — exported PDFs and review files
- bom/ — BOM exports
- LICENSE — MIT license

Design notes
- This project is intentionally kept as a WIP portfolio project.
- The board is not yet final, and fabrication outputs are not included because the PCB is still under development.
- The goal of this repo is to show the engineering progression, not to present a finished production board.

License
This project is licensed under the MIT License. See LICENSE for details.
