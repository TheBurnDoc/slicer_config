# Slicer Configurations
Configurations for my 3D printer slicers.
## SuperSlicer
Configuration files are located in `superslicer` subdirectory of the repository, the locations and symlink commands for each operating system are in the following sections.  Note the `.gitignore` file has several directories in that SuperSlicer generates but do not make sense to be version controlled.

### Linux
 - Location: `~/.config/SuperSlicer`
 - Command: `ln -s ~/.config/SuperSlicer superslicer`
### macOS
 - Location: `~/Library/Application Support/SuperSlicer`
 - Command: `ln -s ~/Library/Application\ Support/SuperSlicer superslicer`

### Windows
 - Location: `%APPDATA%\SuperSlicer` (eg. `C:\Users\tgjon\AppData\Roaming\SuperSlicer`)
 - Command: `mklink \D %APPDATA%\SuperSlicer superslicer`
