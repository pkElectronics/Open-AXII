# Open AXII
 Open AXII aims to provide convenient, ready to use board designs to interface with optical signals commonly found in power electronics.
 The designs aim for fit for purpose solutions without adding too much overhead due to overengineering and provide a starting point for evaluation and customized designs.
 
 This project is in a work in progress state, changes, especially to the naming scheme of the boards may happen without further notice.

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

Currently there are three designs in more or less finished states and a long list of things to do.

| Design             | Receiver                | Transmitter  | Other                  | Modular | State |
| ------------------ | ----------------------- |------------- | ---------------------- | ------- | ----- |
| Open AXII 0x10 FP  | 16x Broadcom AFBR2529Z  | none         | 5V 0.5A DCDC Converter | no      | Layout Done |
| Open AXII 0x00 PWR | none                    | none         | 5V 5A DCDC Converter   | yes     | Concept |
| Open AXII 0x02 ST  | 2x Broadcom AFBR2529Z   | none         | 2x RSSI Out            | yes     | Concept |
| Open AXII 0x02 ??  | none                    | 2x Broadcom AFBR | none               | yes     | ToDo |

Supported Interfaces:
- Avago/Broadcom Versatile Link (wip)
- Firecomms RedLink (planned)
- EIAJ/JEITA RC-5720 / TOSLINK (planned)
- KD9351 FOT + KD1053 Controller (gigabit ethernet, planned)
- Broadcom ST & SMA type links (planned)
