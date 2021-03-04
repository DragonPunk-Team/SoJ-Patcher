# SoJ-Patcher

Credits to [Scarlet Study](https://github.com/ScarletStudy/DGS1-Patcher) for the idea and to [d0k3](https://github.com/d0k3/GodMode9) for this patcher.

[comment]: <> (Source code for our patcher. The releases themselves are located at https://github.com/DragonPunkTeam/SoJ-3DS-Release/releases)
This is a standalone build of GodMode9 which boots straight to \data\autorun.gm9. Little of the GM9 code is changed, as changes are pushed upstream when possible.

Build `SoJ-Patcher.firm` via `make FLAVOR=SoJ-Patcher SCRIPT_RUNNER=1 FIXED_BRIGHTNESS=15`.
This requires [firmtool](https://github.com/TuxSH/firmtool), [Python 3.5+](https://www.python.org/downloads/) and [devkitARM](https://sourceforge.net/projects/devkitpro/) installed.
