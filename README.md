# CrustyNX
A simple title installer manager for the switch

## Installation
1. Install FS sig patches, there are two ways of doing this:
    - Using the latest [hekate](https://github.com/CTCaer/hekate) with the option ``kip1patch=nosigchk`` in ``hekate_ipl.ini``.
    - Using [ReiNX](https://github.com/Reisyukaku/ReiNX)
2. Place the tinfoil nro in the "switch" folder on your sd card, and run using the homebrew menu.

## Usage
1. Place NSPs in ``/tinfoil/nsp`` or extracted NSPs in ``/tinfoil/extracted``.
2. Launch Tinfoil via the homebrew menu and install your NSPs.

## Network Install Instructions
1. Download and install Python 3.6.6 from https://www.python.org/downloads/
2. Download remote_install_pc.py from https://github.com/Adubbz/Tinfoil/blob/master/tools/remote_install_pc.py by right clicking on Raw and clicking "Save link as..."
3. Open the Network Install menu in Tinfoil
4. Run ``remote_install_pc.py`` on your PC on the same network as your Switch with python ``remote_install_pc.py <switch ip> <nsp directory>``, or alternatively with no arguments for interactive mode.
5. ???
6. Profit
