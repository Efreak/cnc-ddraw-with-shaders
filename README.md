## Usage

1. Download the master zip, and extract it into your game folder
2. In ddraw.ini, set your [shader](ddraw.ini#L36) to anything you like, and set the [renderer](ddraw.ini#L43) to opengl (`renderer=opengl`) as it says above that line..

## About

This is an expanded official *release* of [cnc-ddraw](https://github.com/CnCNet/cnc-ddraw). Along with the shaders that comes it, it contains [more](#changes).

I *think* xbrz-freescale (which is what I personally use) dynamically chooses which scaling level to use, but I'm *not sure*.

If the scalers don't work nicely on your system, you might want to skip them and instead use something like [IntegerScaler](https://tanalin.com/en/projects/integer-scaler/). Just keep in mind the ctrl+alt+f11 hotkey may conflict with graphics drivers.

#### Changes:

- Renamed crt-lottes-fast.glsl to crt-lottes-fast-no-warp.glsl
- Added crt-lottes-fast.glsl with curvature set
- Added 4xbrz.glsl, 5xbrz.glsl, 6xbrz.glsl (I personally don't see the need)
- Added jinc2-params.glsl
- Added jinc2-sharp.glsl
- Added jinc2-sharper.glsl
- Added jinc2.glsl
- Added lanczos2-sharp.glsl

I *think* all of these came from [libretro/glsl-shaders](https://github.com/libretro/glsl-shaders), but I'm not 100% sure.

Licensing: Some of the files have licenses, some don't. The licenses themselves are varied, including Unlicense/public domain, GPL, and MIT/expat. If there's no license in the file itself (bilinear, etc), then I have no idea.

