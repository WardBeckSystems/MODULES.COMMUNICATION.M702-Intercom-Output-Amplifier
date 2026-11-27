# M702 · Communication

Ward-Beck Systems M702, 1975|8. Wiki page: [M702 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M702.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 15 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 16 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 2 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 7 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 4 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 16 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

## Specifications

From the technical data sheet: [19xx - M702 - DOC - promo - 7000 series - 004.jpg](MANUALS/19xx%20-%20M702%20-%20DOC%20-%20promo%20-%207000%20series%20-%20004.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **PREAMPLIFIER SECTION (M7O1) GAIN** | 80dB (Max.) +2dB FREQUENCY RESPONSE: + IdB 100 Hz to 1OkHz NOISE: Equivalent to 122dBm relative input noise TOTAL HARMONIC DISTORLess than 1% measured at +18dBm TION: output INPUT: 60dBm, 150 ohms balanced (conditional strapping determines dynamic or carbon source) OUTPUT: 8dBm, 600 ohms balanced (+18dBm Max:) COMPRESSION: 25dB range (may be switched out) POWER +24 to 36 volts dc unregulated. REQUIREMENTS: 35mA approx M712 1 x 12 Crosspoint mother board GAIN: Unity (+6dB pre-set control incorported FREQUENCY RESPONSE: +0.5dB 50Hz to 10kHz NOISE: S/N better than 7OdB measured from +8dBm TOTAL HARMONIC DISTORLess than 0.5% measured at TION: +18dBm INPUT: +8dBm nominal (+18dBm Max:) balanced from direct line or from M703 preamplifier INPUT IMPEDANCE: 30k ohm balanced bridging OUTPUT: OdBm to +8dBm nominal (+18dBm Max:) CROSSPOINT ISOLATION/CUT OFF: 1OOdB TURN ON/OFF TRANSIENT: Inaudible POWER REQUIREMENTS: 24 volts dc regulated 15mA |
| **POWER AMPLIFIER SECTION (M702) GAIN** | 35dB (Max:) +2dB FREQUENCY RESPONSE: + IdB 100 Hz to 8kHz NOISE: S/N better than 75dB measured from 3W output TOTAL HARMONIC DISTORLess than 15% measured at 3W TION: INPUT: OdBm to 18dBm, 600 ohms balanced from crosspoint matrix OUTPUT: 3 Watts directly into 8 ohms (not balanced) COMPRESSION: POWER +24 to 36 volts dc unregulated, 25mA REQUIREMENTS: (quiescent), 30OmA (at Max_ output) |

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1DLTtW-wrQCzaPS8Bfl3haRiz5kjB9uSX/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1DLTtW-wrQCzaPS8Bfl3haRiz5kjB9uSX" width="240" alt="19xx - M702 - DOC - 702-03-003 - REMOVE ALL BURRS AND SHARP EDGES.jpg"></a><br><sub>19xx - M702 - DOC - 702-03-003 - REMOVE ALL BURRS AND SHARP EDGES</sub></td></tr>
</table>

Not on Google Drive yet: `1984 - 702-03-001 - M702B HEATSINK - CKD GEB - ISS 5.jpg`, `1988 - 702-03-002 - M702C HEATSINK - DRN BD -88 - ENG WS - ISS 1.jpg`, `19xx - 702-03-003 - M702D HEATSINK - DRN WS - ISS 1.jpg`

## 3-D model

[`MECHANICAL/M702.stl`](MECHANICAL/M702.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M702)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (assumed: 1.6" x 7" x 6.5", the common module)
- **From the drawing:** 0 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M702 - front panel.svg`)
- no drawing of the front panel: the panel is blank
- Made by `tools/module_models.py` (→ `MECHANICAL/M702.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1cbM0egWVODvvWU4f95tfNVWyIDYWLT6I/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1cbM0egWVODvvWU4f95tfNVWyIDYWLT6I" width="240" alt="19xx - M702 - DOC - 703-02-001 - INTERCOM AMPLIFIERS CONNECTOR STRAPPINGS ISSU.png"></a><br><sub>19xx - M702 - DOC - 703-02-001 - INTERCOM AMPLIFIERS CONNECTOR STRAPPINGS ISSU</sub></td></tr>
</table>

Not on Google Drive yet: `1978 - 702-02-101 - M702B INTERCOM OUTPUT AMPLIFIER SCHEMATIC - DRN MRW - ENG MRW - ISS 5.jpg`, `1978 - 702-02-101 - M702B INTERCOM OUTPUT AMPLIFIER SCHEMATIC - DRN MRW - ENG MRW.png`, `1982 - 702-01-011 - INTERCOM OUTPUT AMPLIFIER FUNCTIONAL DIAGRAM - DRN P. Mahoney - ISS 2.jpg`

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ/view?resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ&resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" width="240" alt="1975 - M702 - PRICE LIST - PRICE LIST.jpg"></a><br><sub>1975|8 · PRICE LIST - PRICE LIST</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNnlHRlZkM3JsTm8/view?resourcekey=0-revQ6vu3rMBcMR5nVFaNdw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNnlHRlZkM3JsTm8&resourcekey=0-revQ6vu3rMBcMR5nVFaNdw" width="240" alt="1977 - M702 - PRICE LIST - 7000 series - price list.jpg"></a><br><sub>1977|10 · PRICE LIST - 7000 series - price list</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYXo5Qlg1WHhSVFU/view?resourcekey=0-w8rjcBS4MPo85YWFx8ocVg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYXo5Qlg1WHhSVFU&resourcekey=0-w8rjcBS4MPo85YWFx8ocVg" width="240" alt="1977 - M702 - PRICE LIST - price list.jpg"></a><br><sub>1977|10 · PRICE LIST - price list</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUHFONVE3R2lZeEk/view?resourcekey=0--zLmPVtRl3x81ljGMdSuNQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUHFONVE3R2lZeEk&resourcekey=0--zLmPVtRl3x81ljGMdSuNQ" width="240" alt="19xx - M702 - DOC - 7000 series - promo - 003.jpg"></a><br><sub>19xx - M702 - DOC - 7000 series - promo - 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMHItYXZndkV6RzQ/view?resourcekey=0-hPzwxujvl48SsPZZXRCqMQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMHItYXZndkV6RzQ&resourcekey=0-hPzwxujvl48SsPZZXRCqMQ" width="240" alt="19xx - M702 - DOC - 7000 series - promo - 004.jpg"></a><br><sub>19xx - M702 - DOC - 7000 series - promo - 004</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU18zSWp5RWMyb0k/view?resourcekey=0-b1mkkSaaCbTCVCqJ67urww" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU18zSWp5RWMyb0k&resourcekey=0-b1mkkSaaCbTCVCqJ67urww" width="240" alt="19xx - M702 - DOC - promo - 7000 series - 003.jpg"></a><br><sub>19xx - M702 - DOC - promo - 7000 series - 003</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVmRYSDJwZ1lmWE0/view?resourcekey=0-NygdkiuhQYLAYXP5dnAvcg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVmRYSDJwZ1lmWE0&resourcekey=0-NygdkiuhQYLAYXP5dnAvcg" width="240" alt="19xx - M702 - DOC - promo - 7000 series - 004.jpg"></a><br><sub>19xx - M702 - DOC - promo - 7000 series - 004</sub></td></tr>
</table>

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

**To check:**

- polarity assumed: 4 contacts given + / − that the drawing does not mark (e.g. P1-21 SPEAKER OUTPUT) (M703: 1977 - M703 - B 703-02-001 - INTERCOM 701, 702, 703 INPUT OUTPUT AMP PIN CONNECTIONS &amp; STRAPPING.jpg)

**Inserts:** PRE OUT / POWER AMP IN: PRE OUTPUT → POWER AMP INPUT

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | +24..36 V UNREG | power |  | medium |
| 3 | MIC INPUT A | in | MIC INPUT | medium |
| 4 | MIC INPUT B | in | MIC INPUT | medium |
| 5 | MIC SHIELD | shield | MIC INPUT shield | medium |
| 6 | CARBON MIC SUPPLY STRAP | strap |  | medium |
| 7 | MIC STRAP | strap |  | medium |
| 8 | PRE OUTPUT A | insert_send | PRE OUTPUT | medium |
| 10 | COMMON (-C) | ground |  | medium |
| 13 | +24..36 V UNREG | power |  | medium |
| 16 | POWER AMP INPUT SHIELD | shield | POWER AMP INPUT shield | medium |
| 17 | POWER AMP INPUT A | insert_return | POWER AMP INPUT | medium |
| 18 | POWER AMP INPUT B | insert_return | POWER AMP INPUT | medium |
| 19 | MUTE | control_in | MUTE | medium |
| 21 | SPEAKER OUTPUT | out | SPEAKER OUTPUT + | medium |
| 22 | SPEAKER OUTPUT RETURN / GROUND | ground | SPEAKER OUTPUT - | medium |
| A | +24..36 V UNREG | power |  | medium |
| C | MIC STRAP | strap |  | medium |
| D | MIC STRAP | strap |  | medium |
| E | MIC STRAP | strap |  | medium |
| F | CARBON MIC SUPPLY STRAP | strap |  | medium |
| H | MIC STRAP | strap |  | medium |
| J | PRE OUTPUT B | insert_send | PRE OUTPUT | medium |
| L | COMMON (-C) | ground |  | medium |
| P | +24..36 V UNREG | power |  | medium |
| T | POWER AMP INPUT SHIELD | shield | POWER AMP INPUT shield | medium |
| U | POWER AMP INPUT A | insert_return | POWER AMP INPUT | medium |
| V | POWER AMP INPUT B | insert_return | POWER AMP INPUT | medium |
| W | MUTE | control_in | MUTE | medium |
| Y | SPEAKER OUTPUT | out | SPEAKER OUTPUT + | medium |
| Z | SPEAKER OUTPUT RETURN / GROUND | ground | SPEAKER OUTPUT - | medium |

**Straps:** DYNAMIC MIC (-60): P1-5 P1-6 · CARBON MIC (-30): P1-6 P1-7 · CARBON + DYNAMIC: P1-6 P1-7

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - 702-02-101 - M702B INTERCOM OUTPUT AMPLIFIER SCHEMATIC - DRN MRW - ENG MRW - ISS 5.kicad_sch](KICAD/1978%20-%20702-02-101%20-%20M702B%20INTERCOM%20OUTPUT%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20MRW%20-%20ENG%20MRW%20-%20ISS%205.kicad_sch)
- [1978 - 702-02-101 - M702B INTERCOM OUTPUT AMPLIFIER SCHEMATIC - DRN MRW - ENG MRW.kicad_sch](KICAD/1978%20-%20702-02-101%20-%20M702B%20INTERCOM%20OUTPUT%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20MRW%20-%20ENG%20MRW.kicad_sch)
- [1982 - 702-01-011 - INTERCOM OUTPUT AMPLIFIER FUNCTIONAL DIAGRAM - DRN P. Mahoney - ISS 2.kicad_sch](KICAD/1982%20-%20702-01-011%20-%20INTERCOM%20OUTPUT%20AMPLIFIER%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20P.%20Mahoney%20-%20ISS%202.kicad_sch)
- [M702.kicad_sym](KICAD/M702.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
