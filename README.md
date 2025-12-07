# PC/XT Software Collection under SvarDOS

Imagine an alternative reality, in which Microsoft's contract with IBM never happened, and MS-DOS never came into being. The [CP/M](https://en.wikipedia.org/wiki/CP/M) operating system evolved into [DR-DOS](https://en.wikipedia.org/wiki/DR-DOS). Decades passed, and in 2022, [DRDOS Inc. released the source code](https://github.com/SvarDOS/edrdos/blob/main/license.htm) and authorized its open-source use. This is our reality, not an imaginary one. The result is the [SvarDOS](http://svardos.org/) project.

This repository contains a curated set of software suitable for IBM PC/XT-class machines and their Turbo XT derivatives under SvarDOS.
The collection is **reconstructed entirely from publicly available Internet archives** and organized to represent a realistic, period-correct software environment for an 8088-based system.

## System Requirements

* **Hardware**: IBM PC/XT-class machines (8088/8086 processor)
* **Memory**: Minimum 256 KiB RAM (512 KiB+ recommended)
* **Storage**: Hard disk or large capacity floppy disk setup
* **Operating System**: SvarDOS (compatible with DR-DOS)

## Contents

The collection includes:

* **Core DOS Utilities** (`SVARDOS/`): ATTRIB, CHKDSK, DEBUG, DELTREE, DISKCOPY, FDISK, FORMAT, SYS, and other essential system tools
* **Development Tools** (`TC/`): Turbo C 2.01 compiler with IDE, libraries, and example programs
* **File Manager** (`VC/`): Volkov Commander 4.05 - dual-pane file manager with built-in editor and viewer
* **Utilities** (`UTIL/`): Disk imaging tools (DSKIMAGE, RAWRITE), compression utilities (PKZIP, PKUNZIP), and system utilities
* **Documentation**: Help files, manuals, and license information for included software

The goal of this project is to provide **a clean, organized, and historically informed snapshot** of what a functional Turbo XT system of the era might contain—useful for restoration, emulation, research, and retro-computing exploration.

## Quick Start

The system is pre-configured with `CONFIG.SYS` and `AUTOEXEC.BAT` files. Key paths are set automatically:
* DOS utilities: `C:\SVARDOS`
* Development tools: `C:\TC`
* File manager: `C:\VC`
* Utilities: `C:\UTIL`

Volkov Commander launches automatically on boot. Use `F10` to exit to DOS prompt.

## Sources

* [SvarDOS](http://svardos.org/)
* [WinWorld](https://winworldpc.com/home)
* [My Abandonware](https://www.myabandonware.com)
* [DOSGames.com](https://dosgames.com)

## Licensing

The **selection, arrangement, and organization** of the files in this repository are released under the
**Creative Commons Zero v1.0 Universal (CC0 1.0)** license.

However, the **software files themselves** remain the property of their respective authors, copyright holders, or original publishers.
They may be subject to separate licenses or usage restrictions.
This repository does **not** claim copyright over the original software.
