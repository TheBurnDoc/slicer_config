# Slicer Configurations
Configurations for my 3D printer slicers.

## PrusaSlicer & SuperSlicer
For these slicers, there are specific `.gitignore` files that have several directories in that the slicer generates but do not make sense to be version controlled.

For SuperSlicer replace `PrusaSlicer` and `prusaslicer` with `SuperSlicer` and `superslicer`.

#### Linux (native)
 - Location: `~/.config/PrusaSlicer`
 - Command: `ln -s ~/.config/PrusaSlicer <workspace>\prusaslicer`

#### Linux (Snap)
 - Location: `~/snap/prusa-slicer/current/.config/PrusaSlicer`
 - Command: `ln -s ~/snap/prusa-slicer/current/.config/PrusaSlicer <workspace>\prusaslicer`
 
#### macOS
 - Location: `~/Library/Application Support/PrusaSlicer`
 - Command: `ln -s ~/Library/Application\ Support/PrusaSlicer <workspace>\prusaslicer`

#### Windows
 - Location: `%APPDATA%\PrusaSlicer`
 - Command (cmd.exe): `mklink \D %APPDATA%\PrusaSlicer <workspace>\prusaslicer`
