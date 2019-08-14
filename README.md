# Neun auf Zwölf

Translates D3D9 games to D3D12 using Microsoft's own D3D9On12
wrapper library.

### Requirements

Windows 10 Insider Preview 18956 or later is required for this to work properly.
(and an SDK >= 18956 to build)

### How to use

Just download the latest [release](https://github.com/Joshua-Ashton/neun-auf-zwoelf/releases),
copy the `d3d9.dll` next to the executable of the game you want to run, and start the game.
Make sure to use the `x64` one for 64-bit games, and the `x86` one for 32-bit games (you probably want the latter).

If everything works correctly, you will most likely experience reduced performance compared
to native D3D9, and in some cases rendering issues and/or driver crashes. Some games may
refuse to run entirely.

**Note:** Tools like MSI Afterburner will still show D3D9 in their overlay, this is because
D3D9On12 is implemented using DDI.

### Why?

Why not? Just don't expect any sort of support when running into issues.