**A complete 720x720 overlay pack for devices like the Anbernic RG Cube and RG Rotate**

**Design goals:** maximum use of screen space, no grids, and a consistent look across systems.
- **Handhelds:** styled as if you're looking through the front lens of the device.
- **Consoles:** sober and photorealistic.

# Contents
1. [Arcade - Capcom CPS](#arcade---capcom-cps)
2. [Bandai - WonderSwan Color](#bandai---wonderswan-color)
3. [NEC - PC Engine](#nec---pc-engine)
4. [Nintendo - Game Boy](#nintendo---game-boy)
5. [Nintendo - Game Boy Color](#nintendo---game-boy-color)
6. [Nintendo - Game Boy Advance](#nintendo---game-boy-advance)
7. [Nintendo - Nintendo Entertainment System](#nintendo---nintendo-entertainment-system)
8. [Nintendo - Super Nintendo Entertainment System](#nintendo---super-nintendo-entertainment-system)
9. [Nintendo - Nintendo 64](#nintendo---nintendo-64)
10. [Sega - Game Gear](#sega---game-gear)
11. [Sega - Master System](#sega---master-system)
12. [Sega - Mega Drive](#sega---mega-drive)
13. [Sega - Saturn](#sega---saturn)
14. [Sega - Dreamcast](#sega---dreamcast)
15. [SNK - Neo Geo Pocket](#snk---neo-geo-pocket)
16. [SNK - Neo Geo Pocket Color](#snk---neo-geo-pocket-color)
17. [SNK - Neo Geo](#snk---neo-geo)
18. [Sony - PlayStation Portable](#sony---playstation-portable)
19. [Sony - PlayStation](#sony---playstation)

# Credits & Reuse

Most of the handheld overlays are edited versions of other creators' work, mainly to remove the grids. Original authors are credited in each system's section. The console overlays are entirely my own creation and are free to reuse for any purpose.

# Installation

Download the `.zip` file from the [Releases](https://github.com/Atodarack/720p-square-overlays/releases) section and extract it into your `~/RetroArch/overlays` folder. This will create a `720p-square` folder containing all the necessary files.

For the content to be scaled and positioned correctly, follow the configuration guide below for each system.

# [Arcade - Capcom CPS](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/cps)

## Horizontal

![CPS horizontal overlay](https://github.com/user-attachments/assets/1e7e8cc7-fd62-4797-a895-061245bcfbc3)

<details>
  <summary>Click for configuration</summary>

### 1. Apply the Overlay

```
Quick Menu > On-Screen Overlay

    Display Overlay > ON

    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select cps.cfg

    Overlay Opacity > 1.00
```

### 2. Scaling Settings

```
Main Menu > Settings > Video > Scaling

    Integer Scale > OFF

    Integer Scale Axis > (shouldn't matter)

    Integer Scale Scaling > (shouldn't matter)

    Aspect Ratio > Custom

        Custom Aspect Ratio (X Position) > 0

        Custom Aspect Ratio (Y Position) > 70

        Custom Aspect Ratio (Width) > 720

        Custom Aspect Ratio (Height) > 540

    Viewport Anchor Bias X > 0.00

    Viewport Anchor Bias Y > 0.00

    Bilinear Filtering > OFF

    Crop Overscan > ON
```

### 3. Save an Override

```
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

### Notes

Since this configuration is saved for the whole content directory, vertical games need their own per-game configuration (see below). There are only a few of them, so it shouldn't be a hassle.

Shader used `~/RetroArch/shaders/shaders_glsl/crt/zfast_crt.glslp`

## Vertical

![CPS vertical overlay](https://github.com/user-attachments/assets/98e5cfc2-eff5-441b-9cd8-f8cdd5ca1bd2)

<details>
  <summary>Click for configuration</summary>

### 1. Apply the Overlay

```
Quick Menu > On-Screen Overlay

    Display Overlay > ON

    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select cps_vertical.cfg

    Overlay Opacity > 1.00
```

### 2. Scaling Settings

```
Main Menu > Settings > Video > Scaling

    Integer Scale > OFF

    Integer Scale Axis > (shouldn't matter)

    Integer Scale Scaling > (shouldn't matter)

    Aspect Ratio > Custom

        Custom Aspect Ratio (X Position) > 0

        Custom Aspect Ratio (Y Position) > 0

        Custom Aspect Ratio (Width) > 540

        Custom Aspect Ratio (Height) > 720

    Viewport Anchor Bias X > 0.50

    Viewport Anchor Bias Y > 0.00

    Bilinear Filtering > OFF

    Crop Overscan > ON
```

### 3. Save an Override

```
Quick Menu > Overrides > Save Game Overrides
```
</details>

### Notes

Shader used `~/RetroArch/shaders/shaders_glsl/crt/zfast_crt.glslp`

# [Bandai - WonderSwan Color](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/wonderswancolor)

## Horizontal

![WSC horizontal overlay](https://github.com/user-attachments/assets/80833c81-b424-439f-acd2-610b344dc7b5)

<details>
  <summary>Click for configuration</summary>

### 1. Apply the Overlay

```
Quick Menu > On-Screen Overlay

    Display Overlay > ON

    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select wonderswancolor.cfg

    Overlay Opacity > 1.00
```

### 2. Scaling Settings

```
Main Menu > Settings > Video > Scaling

    Integer Scale > OFF

    Integer Scale Axis > (shouldn't matter)

    Integer Scale Scaling > (shouldn't matter)

    Aspect Ratio > Custom

        Custom Aspect Ratio (X Position) > 0

        Custom Aspect Ratio (Y Position) > 124

        Custom Aspect Ratio (Width) > 720

        Custom Aspect Ratio (Height) > 462

    Viewport Anchor Bias X > 0.00

    Viewport Anchor Bias Y > 0.00

    Bilinear Filtering > OFF

    Crop Overscan > ON
```

### 3. Save an Override

```
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

### Notes

Since this configuration is saved for the whole content directory, vertical games need their own per-game configuration (see below). There are only a few of them, so it shouldn't be a hassle.

Shader used `~/RetroArch/shaders/shaders_glsl/handheld/lcd3x.glslp`

## Vertical

![WSC vertical overlay](https://github.com/user-attachments/assets/d4d2f4ff-3039-4f89-934a-db100b2bc37b)

<details>
  <summary>Click for configuration</summary>

### 1. Apply the Overlay

```
Quick Menu > On-Screen Overlay

    Display Overlay > ON

    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select wonderswancolor_vertical.cfg

    Overlay Opacity > 1.00
```

### 2. Scaling Settings

```
Main Menu > Settings > Video > Scaling

    Integer Scale > OFF

    Integer Scale Axis > (shouldn't matter)

    Integer Scale Scaling > (shouldn't matter)

    Aspect Ratio > Custom

        Custom Aspect Ratio (X Position) > 124

        Custom Aspect Ratio (Y Position) > 0

        Custom Aspect Ratio (Width) > 462

        Custom Aspect Ratio (Height) > 720

    Viewport Anchor Bias X > 0.00

    Viewport Anchor Bias Y > 0.00

    Bilinear Filtering > OFF

    Crop Overscan > ON
```

### 3. Save an Override

```
Quick Menu > Overrides > Save Game Overrides
```

</details>

### Notes

Shader used `~/RetroArch/shaders/shaders_glsl/handheld/lcd3x.glslp`

# [NEC - PC Engine](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/pcengine)

![PCE overlay](https://github.com/user-attachments/assets/ede6a896-c58a-401c-83fb-efc98c9ffa75)

<details>
  <summary>Click for configuration</summary>

### 1. Apply the Overlay

```
Quick Menu > On-Screen Overlay

    Display Overlay > ON

    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select pcengine.cfg

    Overlay Opacity > 1.00
```

### 2. Scaling Settings

```
Main Menu > Settings > Video > Scaling

    Integer Scale > OFF

    Integer Scale Axis > (shouldn't matter)

    Integer Scale Scaling > (shouldn't matter)

    Aspect Ratio > Custom

        Custom Aspect Ratio (X Position) > 0

        Custom Aspect Ratio (Y Position) > 70

        Custom Aspect Ratio (Width) > 720

        Custom Aspect Ratio (Height) > 540

    Viewport Anchor Bias X > 0.00

    Viewport Anchor Bias Y > 0.00

    Bilinear Filtering > OFF

    Crop Overscan > ON
```

### 3. Save an Override

```
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

### Notes

Shader used `~/RetroArch/shaders/shaders_glsl/crt/zfast_crt.glslp`

# [Nintendo - Game Boy](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/gb)

![GB overlay](https://github.com/user-attachments/assets/376930cb-3521-4a5e-8bb3-eef00fc4133d)

<details>
  <summary>Click for configuration</summary>

### 1. Apply the Overlay

```
Quick Menu > On-Screen Overlay

    Display Overlay > ON

    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select gb.cfg

    Overlay Opacity > 1.00
```

### 2. Scaling Settings

```
Main Menu > Settings > Video > Scaling

    Integer Scale > OFF

    Integer Scale Axis > (shouldn't matter)

    Integer Scale Scaling > (shouldn't matter)

    Aspect Ratio > Custom

        Custom Aspect Ratio (X Position) > 0

        Custom Aspect Ratio (Y Position) > 25

        Custom Aspect Ratio (Width) > 720

        Custom Aspect Ratio (Height) > 648

    Viewport Anchor Bias X > 0.00

    Viewport Anchor Bias Y > 0.00

    Bilinear Filtering > OFF

    Crop Overscan > ON
```

### 3. Save an Override

```
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

### Notes

Credit to [mugwomp93](https://github.com/mugwomp93/720x720_overlays/tree/main/720x720%20overlays/GB) for the original version of this overlay.

Color Palette using the Gambatte core `Quick Menu > Core Options > GB Colorization > Internal Palette > GB - Pocket`

Shader used `~/RetroArch/shaders/shaders_glsl/handheld/lcd3x.glslp`

# [Nintendo - Game Boy Color](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/gbc)

![GBC overlay](https://github.com/user-attachments/assets/f0651c84-ec3e-4458-9dc9-688f67e73e6d)

<details>
  <summary>Click for configuration</summary>

### 1. Apply the Overlay

```
Quick Menu > On-Screen Overlay

    Display Overlay > ON

    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select gbc.cfg

    Overlay Opacity > 1.00
```

### 2. Scaling Settings

```
Main Menu > Settings > Video > Scaling

    Integer Scale > OFF

    Integer Scale Axis > (shouldn't matter)

    Integer Scale Scaling > (shouldn't matter)

    Aspect Ratio > Custom

        Custom Aspect Ratio (X Position) > 0

        Custom Aspect Ratio (Y Position) > 25

        Custom Aspect Ratio (Width) > 720

        Custom Aspect Ratio (Height) > 648

    Viewport Anchor Bias X > 0.00

    Viewport Anchor Bias Y > 0.00

    Bilinear Filtering > OFF

    Crop Overscan > ON
```

### 3. Save an Override

```
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

### Notes

Credit to [mugwomp93](https://github.com/mugwomp93/720x720_overlays/tree/main/720x720%20overlays/GBC) for the original version of this overlay.

Shader used `~/RetroArch/shaders/shaders_glsl/handheld/lcd3x.glslp`

# [Nintendo - Game Boy Advance](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/gba)

![GBA overlay](https://github.com/user-attachments/assets/e777291c-88c7-4ee6-a259-d76f77cfcc53)

<details>
  <summary>Click for configuration</summary>

### 1. Apply the Overlay

```
Quick Menu > On-Screen Overlay

    Display Overlay > ON

    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select gba.cfg

    Overlay Opacity > 1.00
```

### 2. Scaling Settings

```
Main Menu > Settings > Video > Scaling

    Integer Scale > OFF

    Integer Scale Axis > (shouldn't matter)

    Integer Scale Scaling > (shouldn't matter)

    Aspect Ratio > Core provided

    Viewport Anchor Bias X > 0.00

    Viewport Anchor Bias Y > 0.50

    Bilinear Filtering > OFF

    Crop Overscan > ON
```

### 3. Save an Override

```
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

### Notes

Credit to [gonejack](https://github.com/gonejack/rgb30/blob/main/RGB30/RGB30_GBA_3x_HUI.png) for the original version of this overlay.

Shader used `~/RetroArch/shaders/shaders_glsl/handheld/lcd3x.glslp`

# [Nintendo - Nintendo Entertainment System](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/nes)

![NES overlay](https://github.com/user-attachments/assets/ecabb783-e99d-4359-be9c-e1fd0ef7ed65)

<details>
  <summary>Click for configuration</summary>

### 1. Apply the Overlay

```
Quick Menu > On-Screen Overlay

    Display Overlay > ON

    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select nes.cfg

    Overlay Opacity > 1.00
```

### 2. Scaling Settings

```
Main Menu > Settings > Video > Scaling

    Integer Scale > OFF

    Integer Scale Axis > (shouldn't matter)

    Integer Scale Scaling > (shouldn't matter)

    Aspect Ratio > Custom

        Custom Aspect Ratio (X Position) > 0

        Custom Aspect Ratio (Y Position) > 70

        Custom Aspect Ratio (Width) > 720

        Custom Aspect Ratio (Height) > 540

    Viewport Anchor Bias X > 0.00

    Viewport Anchor Bias Y > 0.00

    Bilinear Filtering > OFF

    Crop Overscan > ON
```

### 3. Save an Override

```
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

### Notes

Shader used `~/RetroArch/shaders/shaders_glsl/crt/zfast_crt.glslp`

# [Nintendo - Super Nintendo Entertainment System](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/snes)

![SNES overlay](https://github.com/user-attachments/assets/578c457e-d228-4d2a-8745-f364dea2c125)

<details>
  <summary>Click for configuration</summary>

### 1. Apply the Overlay

```
Quick Menu > On-Screen Overlay

    Display Overlay > ON

    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select snes.cfg

    Overlay Opacity > 1.00
```

### 2. Scaling Settings

```
Main Menu > Settings > Video > Scaling

    Integer Scale > OFF

    Integer Scale Axis > (shouldn't matter)

    Integer Scale Scaling > (shouldn't matter)

    Aspect Ratio > Custom

        Custom Aspect Ratio (X Position) > 0

        Custom Aspect Ratio (Y Position) > 70

        Custom Aspect Ratio (Width) > 720

        Custom Aspect Ratio (Height) > 540

    Viewport Anchor Bias X > 0.00

    Viewport Anchor Bias Y > 0.00

    Bilinear Filtering > OFF

    Crop Overscan > ON
```

### 3. Save an Override

```
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

### Notes

Shader used `~/RetroArch/shaders/shaders_glsl/crt/zfast_crt.glslp`

# [Nintendo - Nintendo 64](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/n64)

![N64 overlay](https://github.com/user-attachments/assets/1948157b-aa85-4973-9bfd-65fb6bec449b)

<details>
  <summary>Click for configuration</summary>

### 1. Apply the Overlay

```
Quick Menu > On-Screen Overlay

    Display Overlay > ON

    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select n64.cfg

    Overlay Opacity > 1.00
```

### 2. Scaling Settings

```
Main Menu > Settings > Video > Scaling

    Integer Scale > OFF

    Integer Scale Axis > (shouldn't matter)

    Integer Scale Scaling > (shouldn't matter)

    Aspect Ratio > Custom

        Custom Aspect Ratio (X Position) > 0

        Custom Aspect Ratio (Y Position) > 70

        Custom Aspect Ratio (Width) > 720

        Custom Aspect Ratio (Height) > 540

    Viewport Anchor Bias X > 0.00

    Viewport Anchor Bias Y > 0.00

    Bilinear Filtering > OFF

    Crop Overscan > ON
```

### 3. Save an Override

```
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

### Notes

For this system you'll probably have to play with overscan settings to make your games fit properly, while using the Mupen64Plus-Next core do `Quick Menu > Core Options > GlideN64 > Overscan Offset` and adjust them however you want.

# [Sega - Game Gear](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/gamegear)

![GG overlay](https://github.com/user-attachments/assets/81fbf3c4-ccfa-4f90-a2e8-4231db879bfb)

<details>
  <summary>Click for configuration</summary>

### 1. Apply the Overlay

```
Quick Menu > On-Screen Overlay

    Display Overlay > ON

    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select gamegear.cfg

    Overlay Opacity > 1.00
```

### 2. Scaling Settings

```
Main Menu > Settings > Video > Scaling

    Integer Scale > OFF

    Integer Scale Axis > (shouldn't matter)

    Integer Scale Scaling > (shouldn't matter)

    Aspect Ratio > Custom

        Custom Aspect Ratio (X Position) > 0

        Custom Aspect Ratio (Y Position) > 25

        Custom Aspect Ratio (Width) > 720

        Custom Aspect Ratio (Height) > 648

    Viewport Anchor Bias X > 0.00

    Viewport Anchor Bias Y > 0.00

    Bilinear Filtering > OFF

    Crop Overscan > ON
```

### 3. Save an Override

```
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

### Notes

Credit to [mugwomp93](https://github.com/mugwomp93/720x720_overlays/tree/main/720x720%20overlays/GG) for the original version of this overlay.

Shader used `~/RetroArch/shaders/shaders_glsl/handheld/lcd3x.glslp`

# [Sega - Master System](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/mastersystem)

![SMS overlay](https://github.com/user-attachments/assets/da47e6be-3bf7-4ae6-9e9b-66154624b637)

<details>
  <summary>Click for configuration</summary>

### 1. Apply the Overlay

```
Quick Menu > On-Screen Overlay

    Display Overlay > ON

    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select mastersystem.cfg

    Overlay Opacity > 1.00
```

### 2. Scaling Settings

```
Main Menu > Settings > Video > Scaling

    Integer Scale > OFF

    Integer Scale Axis > (shouldn't matter)

    Integer Scale Scaling > (shouldn't matter)

    Aspect Ratio > Custom

        Custom Aspect Ratio (X Position) > 0

        Custom Aspect Ratio (Y Position) > 70

        Custom Aspect Ratio (Width) > 720

        Custom Aspect Ratio (Height) > 540

    Viewport Anchor Bias X > 0.00

    Viewport Anchor Bias Y > 0.00

    Bilinear Filtering > OFF

    Crop Overscan > ON
```

### 3. Save an Override

```
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

### Notes

Shader used `~/RetroArch/shaders/shaders_glsl/crt/zfast_crt.glslp`

# [Sega - Mega Drive](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/megadrive)

![SMD overlay](https://github.com/user-attachments/assets/2f00d66e-acd9-40f9-bd20-407c7b816468)

<details>
  <summary>Click for configuration</summary>

### 1. Apply the Overlay

```
Quick Menu > On-Screen Overlay

    Display Overlay > ON

    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select megadrive.cfg

    Overlay Opacity > 1.00
```

### 2. Scaling Settings

```
Main Menu > Settings > Video > Scaling

    Integer Scale > OFF

    Integer Scale Axis > (shouldn't matter)

    Integer Scale Scaling > (shouldn't matter)

    Aspect Ratio > Custom

        Custom Aspect Ratio (X Position) > 0

        Custom Aspect Ratio (Y Position) > 70

        Custom Aspect Ratio (Width) > 720

        Custom Aspect Ratio (Height) > 540

    Viewport Anchor Bias X > 0.00

    Viewport Anchor Bias Y > 0.00

    Bilinear Filtering > OFF

    Crop Overscan > ON
```

### 3. Save an Override

```
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

### Notes

Shader used `~/RetroArch/shaders/shaders_glsl/crt/zfast_crt.glslp`
