# Tiny Gamer

## Project Owner

**Name:** Krish Shah  
**Virginia Tech Email:** TBD

## Project Overview

Tiny Gamer is a small handheld gaming device built around the ATtiny85 microcontroller. The goal is to create a compact, battery-powered system that can run simple games on a small OLED display using a custom PCB.

The device uses four gameplay/directional buttons, one action button, a power control, and a reset button. It is powered by a coin cell battery and programmed using the Arduino development environment.

The exact games are still being selected and will be chosen based on the memory and processing limits of the ATtiny85.

## What I Hope to Learn

Through this project, I hope to gain more hands-on experience with:

- ATtiny85 embedded programming
- OLED graphics and simple game development
- PCB design and hardware bring-up
- Button input and user-interface design
- Coin-cell power constraints
- Hardware/software integration
- Debugging a complete embedded system

## Design and Implementation

### Hardware

- ATtiny85 microcontroller
- Small OLED display
- Custom PCB designed in EasyEDA
- 4 gameplay/directional buttons
- 1 action button
- 1 power button/switch
- 1 reset button
- Coin cell battery and holder

### Software

The device will be programmed using the Arduino development environment. The game software will be kept lightweight so that it can run within the ATtiny85's limited memory and processing resources.

### Current Design Status

The PCB design has been completed in EasyEDA and is ready to order.

### Planned Implementation

1. Order the custom PCB.
2. Assemble and inspect the board.
3. Verify power operation.
4. Test the ATtiny85 and OLED display.
5. Test all buttons and reset/power functions.
6. Select and implement simple games.
7. Debug and optimize the software for the ATtiny85.
8. Complete final system testing.

Possible games include a Pong-style game, Snake-style game, endless runner, reaction game, or another small arcade-style game.

## Bill of Materials

| ID | Item | Designator | Qty | Package | Manufacturer Part | Unit Cost | Total Cost | Link |
|---:|---|---|---:|---|---|---:|---:|---|
| 1 | Buzzer | BUZZER1 | 1 | BUZZER-4.0X4.0-2P-SMD | SMT-0440-T-HT-R | $3.21 | $3.21 | [DigiKey](https://www.digikey.com/en/products/detail/pui-audio-inc/SMT-0440-T-HT-R/13165922) |
| 2 | 2k | R7, R9 | 2 | 0603 | RC0603FR-072KL | $0.11 | $0.22 | [DigiKey](https://www.digikey.com/en/products/detail/yageo/RC0603FR-072KL/727009) |
| 3 | 20k | R6 | 1 | 0603 | RC0603FR-0720KL | $0.10 | $0.10 | [DigiKey](https://www.digikey.com/en/products/detail/yageo/RC0603FR-0720KL/727040) |
| 4 | 4.7k | R3, R2 | 2 | 0603 | RC0603FR-074K7L | $0.10 | $0.20 | [DigiKey](https://www.digikey.com/en/products/detail/yageo/RC0603FR-074K7L/727212) |
| 5 | 10k | R1, R8 | 2 | 0603 | RC0201FR-0710KL | $0.10 | $0.20 | [DigiKey](https://www.digikey.com/en/products/detail/yageo/RC0201FR-0710KL/1948870) |
| 6 | 3.9k | R5 | 1 | 0603 | RC0603FR-073K9L | $0.11 | $0.11 | [DigiKey](https://www.digikey.com/en/products/detail/yageo/RC0603FR-073K9L/727136) |
| 7 | 8.2k | R4 | 1 | 0603 | RC0201FR-078K2L | $0.10 | $0.10 | [DigiKey](https://www.digikey.com/en/products/detail/yageo/RC0201FR-078K2L/3202425) |
| 8 | Battery Holder | B1 | 1 | BATTERY-3 | BHSD-2032-SM | $1.68 | $1.68 | [DigiKey](https://www.digikey.com/en/products/detail/mpd-memory-protection-devices-/BHSD-2032-SM/2647817) |
| 9 | OLED | OLED | 1 | OLED | OLED | $1.00 | $1.00 | [AliExpress](https://www.aliexpress.us/item/3256811978952578.html) |
| 10 | Tackel Switch | ACTION, UP, DOWN, RIGHT, LEFT | 5 | 6.00mm x 6.00mm | TS04-66-50-BK-260-SMT | $0.20 | $1.00 | [DigiKey](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices-/TS04-66-50-BK-260-SMT/15634371) |
| 11 | ATtiny x5-20SU | U1 | 1 | SOIC-8_208MIL | ATTINY85-20SU | $1.50 | $1.50 | [DigiKey](https://www.digikey.com/en/products/detail/microchip-technology/ATTINY85-20SU/735470) |
| 12 | Slide Switch | POWER | 1 | SLIDE SWITCH | EG1270 | $1.09 | $1.09 | [DigiKey](https://www.digikey.com/en/products/detail/e-switch/EG1270/6076) |
| 13 | 3x6x2.5mm | RESET | 1 | KEY-3.0*6.0 | PTS636SM25FSMTR LFS | $0.28 | $0.28 | [DigiKey](https://www.digikey.com/en/products/detail/c-k/PTS636SM25FSMTR-LFS/10071742) |
| 14 | 100nF | C1 | 1 | 0603 | CL10E104KC8VPNC | $0.32 | $0.32 | [DigiKey](https://www.digikey.com/en/products/detail/samsung-electro-mechanics/CL10E104KC8VPNC/20498486) |
| 15 | 47uF | C2 | 1 | 1206 | CL31A476MPHNNNE | $0.63 | $0.63 | [DigiKey](https://www.digikey.com/en/products/detail/samsung-electro-mechanics/CL31A476MPHNNNE/3888721) |
| 16 | Battery | — | 1 | - | CR2032 | $0.39 | $0.39 | [DigiKey](https://www.digikey.com/en/products/detail/panasonic-energy/CR2032/31939) |
| 17 | SOIC 8-Pin Test Clip | — | 1 | - | 5315 | $14.95 | $14.95 | [Adafruit](https://www.adafruit.com/product/5315) |

**Estimated Total Cost:** $26.98


## Timeline and Milestones

| Milestone | Target Date | Status |
|---|---|---|
| Project planning | October 2026 | Complete |
| PCB design in EasyEDA | October 2026 | Complete |
| Order PCB | October 2026 | In Progress |
| PCB assembly and hardware bring-up | TBD | Not Started |
| OLED and button testing | TBD | Not Started |
| Game development | TBD | Not Started |
| Final testing | TBD | Not Started |
| Project completion | TBD | Not Started |

## Progress Log

### 2026-10-05

- Defined the Tiny Gamer project concept.
- Selected the ATtiny85 as the main microcontroller.
- Selected a small OLED display for the user interface.
- Designed the custom PCB in EasyEDA.
- PCB is ready to order.
- Next step: order the PCB and begin hardware bring-up after it arrives.

## Project Files

Project files will be added as the project develops. These may include:

- EasyEDA PCB design files
- Schematic exports
- Gerber files
- Arduino source code
- Datasheets
- Test results
- Project documentation

## Useful Links

Useful datasheets, programming references, and component links will be added as components and games are finalized.

## Project Image

A project image will be added later.

The final cover image will be stored in the repository root as `hero.png` so it can be displayed correctly on the AMP Lab website.
