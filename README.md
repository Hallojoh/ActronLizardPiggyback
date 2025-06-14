# ActronLizardPiggyback
Lizard Piggyback KiCad Symbol &amp; Footprint
# Actron Lizard Piggyback KiCad Symbol & Footprint

This repository contains a KiCad schematic symbol and footprint designed to make it easy to create custom piggyback PCBs that mechanically and electrically connect to the **Lizard Board**. 
[Learn more about the Lizard Board at actron.de](https://www.actron.de/lizard/)

## Features

- Accurate **footprint** with:
  - Mechanical **cutouts** for clearance
  - Clearly labeled **pin positions**
  - Precisely placed **mounting holes**
- Matching **schematic symbol** for quick integration
- Ideal for rapid prototyping and extension boards

## Contents

- `Actron_Lizard.kicad_sym` – Schematic symbol
- `LizardBoardPiggyback.kicad_mod` – Footprint with cutouts and mount points

## Usage

1. Add the `.kicad_sym` file to your project's KiCad library paths.
2. Create new footprintlib and import `.kicad_mod` via footprinteditor.
3. Use the symbol in your schematic and connect it as needed.
4. Place the **Lizard Piggyback** footprint in your layout.
5. Create additional cutouts for USB or SD card in your piggyback board for better accessibility
6. Design your piggyback board.

This enables fast development of plug-on modules for your Lizard-based systems.
2x FTSH-113-01-L-DV are recommended.

## Preview

TBD

## License

This KiCad symbol and footprint are licensed under the **CERN-OHL-S v2**.

You may redistribute and modify the design files under the terms of the CERN Open Hardware Licence Version 2 - Strongly Reciprocal.

A copy of the license text is available here:  
https://ohwr.org/cern_ohl_s_v2.txt

By using this project, you agree to the terms of the license.

---

Created for fast and modular hardware development with the Lizard Board.
