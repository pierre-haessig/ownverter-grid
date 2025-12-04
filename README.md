# OwnVerter application: grid connected inverter

This repository host embedded microcontroller code for using the [OwnTech OwnVerter](https://www.owntech.io/ownverter/) board as a **grid connected three-phase inverter**, with closed loop **current control** (d and q current regulation). It is a grid following control using a PLL for grid synchronization.

This code is very similar to https://github.com/pierre-haessig/ownverter-sync, which already contains the PLL for grid synchronization, but feeds an islanded load. This application adds the closed loop current control.

This code is used in the context of a power electronics course at CentralSupélec, Rennes campus: [http://éole.net/courses/onduleur/](http://éole.net/courses/onduleur/) (in French). List of code repositories of the lab series:

1. DC/DC converter: https://github.com/pierre-haessig/ownverter-dcdc
2. Islanded inverter (autonomous operation): https://github.com/pierre-haessig/ownverter-islanded
3. Islanded inverter with grid synchronization: https://github.com/pierre-haessig/ownverter-sync
4. **Grid connected inverter**: https://github.com/pierre-haessig/ownverter-grid (here)

## Experiment schematics

Wiring diagram:

![wiring diagram of the inverter](images/ownverter_wiring_inverter_grid.png)

## Usage

This code derives from the [OwnTech Power API Core repository](https://github.com/owntech-foundation/Core). It is designed to be used with VS Code and PlatformIO. The usage of this type of repository is documented at https://docs.owntech.org (e.g. Getting Started section).

