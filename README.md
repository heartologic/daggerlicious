# daggerlicious
A real-time, 3D spawnset editor for Devil Daggers in the FTEQW game engine.
## Installation
1. Download this repository by clicking on "Code", then "Download ZIP".
2. Download the [Asset Editor](https://devildaggers.info/tools/asset-editor).
3. Extract this repository's .zip file into a folder, and extract the Asset Editor.
4. Extract the "dd" binary into the _dl-side folder.
5. Move everything inside your Daggerlicious folder to wherever DD is in your computer.

Your game directory should now look somewhat similar to this:
```
_dl-main/
_dl-side/
core/
dd/
mods/
res/
default.fmf
dd.exe
dl.exe
```

If so, run dl.exe.
## Compilation
Open a command line inside the _dl-main/source/ folder and run `fteqcc64.exe make.source`.
## About
A big thank you to xvlv (Noah Stolk) for this documentation of the DD spawnset binary format and his work on DDSE/DDAE/DDCL/etc.
Another big thank you to the FTEQW team for developing FTEQW.
