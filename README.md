# Slicer Configurations
Configurations for my 3D printer slicers.

## Slic3r Deriviates
For these slicers, there are specific `.gitignore` files that have several directories in that the slicer generates but do not make sense to be version controlled.

### PrusaSlicer

#### Linux
 - TODO
 
#### macOS
 - TODO

#### Windows
 - Location: `%APPDATA%\PrusaSlicer` (eg. `C:\Users\tgjon\AppData\Roaming\PrusaSlicer`)
 - cme.exe: `mklink \D %APPDATA%\PrusaSlicer %USERPROFILE%\PrusaSlicer`

### SuperSlicer

#### Linux
 - Location: `~/.config/SuperSlicer`
 - Command: `ln -s ~/.config/SuperSlicer superslicer`

#### macOS
 - Location: `~/Library/Application Support/SuperSlicer`
 - Command: `ln -s ~/Library/Application\ Support/SuperSlicer superslicer`

#### Windows
 - Location: `%APPDATA%\SuperSlicer` (eg. `C:\Users\tgjon\AppData\Roaming\SuperSlicer`)
 - Command (cmd.exe): `mklink \D %APPDATA%\SuperSlicer %USERPROFILE%\superslicer`
